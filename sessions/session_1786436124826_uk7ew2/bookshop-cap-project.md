<h2><span class="sec-num">1</span> Bookshop CAP Application</h2>

<p>This is a complete SAP CAP (Cloud Application Programming) sample application with a Fiori Elements UI. It includes a <strong>Books</strong> and <strong>Authors</strong> catalog with full CRUD support, filtering, and object page navigation.</p>

<div class="callout tip">
<strong>Quick Start:</strong> Create a folder, save each file below to the specified path, then run <code>npm install</code> followed by <code>cds watch</code>. Open the Fiori app at the URL shown in the console.
</div>

<h2><span class="sec-num">2</span> Project Structure</h2>

<table class="data">
<thead><tr><th>File</th><th>Purpose</th></tr></thead>
<tbody>
<tr><td><code>db/schema.cds</code></td><td>Entity definitions (Books, Authors)</td></tr>
<tr><td><code>srv/service.cds</code></td><td>OData service exposure with draft support</td></tr>
<tr><td><code>srv/annotations.cds</code></td><td>Fiori Elements UI annotations</td></tr>
<tr><td><code>db/data/*.csv</code></td><td>Sample seed data</td></tr>
<tr><td><code>app/bookshop/webapp/*</code></td><td>Fiori Elements frontend (3 files)</td></tr>
<tr><td><code>package.json</code></td><td>Dependencies and scripts</td></tr>
</tbody>
</table>

<h2><span class="sec-num">3</span> db/schema.cds</h2>

<details><summary>View Code</summary>
<pre><code>namespace my.bookshop;

entity Books {
  key ID           : Integer;
      title        : String(200);
      author       : String(100);
      genre        : String(50);
      price        : Decimal(10,2);
      stock        : Integer;
      publishedYear: Integer;
}

entity Authors {
  key ID        : Integer;
      name      : String(100);
      country   : String(50);
      birthYear : Integer;
}</code></pre>
</details>

<h2><span class="sec-num">4</span> srv/service.cds</h2>

<details><summary>View Code</summary>
<pre><code>using my.bookshop as db from '../db/schema';
using from './annotations';

service CatalogService {
  @odata.draft.enabled
  entity Books as projection on db.Books;

  @odata.draft.enabled  
  entity Authors as projection on db.Authors;
}</code></pre>
</details>

<h2><span class="sec-num">5</span> srv/annotations.cds</h2>

<details><summary>View Code</summary>
<pre><code>using CatalogService as service from './service';

// ========== BOOKS ANNOTATIONS ==========
annotate service.Books with @(
  UI.HeaderInfo: {
    TypeName: 'Book',
    TypeNamePlural: 'Books',
    Title: { $Type: 'UI.DataField', Value: title },
    Description: { $Type: 'UI.DataField', Value: author }
  },

  UI.SelectionFields: [ genre, author, publishedYear ],

  UI.LineItem: [
    { $Type: 'UI.DataField', Value: ID, Label: 'ID' },
    { $Type: 'UI.DataField', Value: title, Label: 'Title' },
    { $Type: 'UI.DataField', Value: author, Label: 'Author' },
    { $Type: 'UI.DataField', Value: genre, Label: 'Genre' },
    { $Type: 'UI.DataField', Value: price, Label: 'Price' },
    { $Type: 'UI.DataField', Value: stock, Label: 'Stock' },
    { $Type: 'UI.DataField', Value: publishedYear, Label: 'Year' }
  ],

  UI.Facets: [
    { $Type: 'UI.ReferenceFacet', ID: 'BookDetails', 
      Target: '@UI.FieldGroup#BookDetails', Label: 'Book Details' },
    { $Type: 'UI.ReferenceFacet', ID: 'Inventory', 
      Target: '@UI.FieldGroup#Inventory', Label: 'Inventory' }
  ],

  UI.FieldGroup#BookDetails: { Data: [
    { $Type: 'UI.DataField', Value: title, Label: 'Title' },
    { $Type: 'UI.DataField', Value: author, Label: 'Author' },
    { $Type: 'UI.DataField', Value: genre, Label: 'Genre' },
    { $Type: 'UI.DataField', Value: publishedYear, Label: 'Published Year' }
  ]},

  UI.FieldGroup#Inventory: { Data: [
    { $Type: 'UI.DataField', Value: price, Label: 'Price' },
    { $Type: 'UI.DataField', Value: stock, Label: 'Stock Available' }
  ]}
);

// ========== AUTHORS ANNOTATIONS ==========
annotate service.Authors with @(
  UI.HeaderInfo: {
    TypeName: 'Author',
    TypeNamePlural: 'Authors',
    Title: { $Type: 'UI.DataField', Value: name },
    Description: { $Type: 'UI.DataField', Value: country }
  },

  UI.SelectionFields: [ country ],

  UI.LineItem: [
    { $Type: 'UI.DataField', Value: ID, Label: 'ID' },
    { $Type: 'UI.DataField', Value: name, Label: 'Name' },
    { $Type: 'UI.DataField', Value: country, Label: 'Country' },
    { $Type: 'UI.DataField', Value: birthYear, Label: 'Birth Year' }
  ],

  UI.Facets: [
    { $Type: 'UI.ReferenceFacet', ID: 'AuthorDetails', 
      Target: '@UI.FieldGroup#AuthorDetails', Label: 'Author Details' }
  ],

  UI.FieldGroup#AuthorDetails: { Data: [
    { $Type: 'UI.DataField', Value: name, Label: 'Name' },
    { $Type: 'UI.DataField', Value: country, Label: 'Country' },
    { $Type: 'UI.DataField', Value: birthYear, Label: 'Birth Year' }
  ]}
);</code></pre>
</details>

<h2><span class="sec-num">6</span> db/data/my.bookshop-Books.csv</h2>

<details><summary>View Code</summary>
<pre><code>ID,title,author,genre,price,stock,publishedYear
1,The Hitchhiker's Guide to the Galaxy,Douglas Adams,Science Fiction,12.99,25,1979
2,1984,George Orwell,Dystopian,10.50,42,1949
3,Pride and Prejudice,Jane Austen,Romance,8.99,18,1813
4,The Great Gatsby,F. Scott Fitzgerald,Classic,11.25,30,1925
5,To Kill a Mockingbird,Harper Lee,Classic,9.99,55,1960</code></pre>
</details>

<h2><span class="sec-num">7</span> db/data/my.bookshop-Authors.csv</h2>

<details><summary>View Code</summary>
<pre><code>ID,name,country,birthYear
1,Douglas Adams,United Kingdom,1952
2,George Orwell,United Kingdom,1903
3,Jane Austen,United Kingdom,1775
4,F. Scott Fitzgerald,United States,1896
5,Harper Lee,United States,1926</code></pre>
</details>

<h2><span class="sec-num">8</span> app/bookshop/webapp/manifest.json</h2>

<details><summary>View Code</summary>
<pre><code>{
  "_version": "1.59.0",
  "sap.app": {
    "id": "com.c16.bookshop",
    "type": "application",
    "title": "Bookshop Catalog",
    "description": "Manage Books and Authors",
    "applicationVersion": { "version": "1.0.0" },
    "dataSources": {
      "mainService": {
        "uri": "/odata/v4/catalog/",
        "type": "OData",
        "settings": { "odataVersion": "4.0" }
      }
    }
  },
  "sap.ui": {
    "technology": "UI5",
    "icons": { "icon": "sap-icon://education" }
  },
  "sap.ui5": {
    "flexEnabled": false,
    "dependencies": {
      "minUI5Version": "1.120.0",
      "libs": { 
        "sap.m": {}, 
        "sap.ui.core": {}, 
        "sap.ushell": {}, 
        "sap.fe.templates": {} 
      }
    },
    "models": {
      "": {
        "dataSource": "mainService",
        "preload": true,
        "settings": {
          "synchronizationMode": "None",
          "operationMode": "Server",
          "autoExpandSelect": true,
          "earlyRequests": true
        }
      }
    },
    "routing": {
      "routes": [
        { "pattern": ":?query:", "name": "BooksList", "target": "BooksList" },
        { "pattern": "Books({key}):?query:", "name": "BooksDetail", "target": "BooksDetail" }
      ],
      "targets": {
        "BooksList": {
          "type": "Component",
          "id": "BooksList",
          "name": "sap.fe.templates.ListReport",
          "options": {
            "settings": {
              "contextPath": "/Books",
              "variantManagement": "Page",
              "initialLoad": "Enabled",
              "navigation": {
                "Books": { "detail": { "route": "BooksDetail" } }
              }
            }
          }
        },
        "BooksDetail": {
          "type": "Component",
          "id": "BooksDetail",
          "name": "sap.fe.templates.ObjectPage",
          "options": {
            "settings": {
              "contextPath": "/Books",
              "editableHeaderContent": false
            }
          }
        }
      }
    }
  }
}</code></pre>
</details>

<h2><span class="sec-num">9</span> app/bookshop/webapp/index.html</h2>

<details><summary>View Code</summary>
<pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8"&gt;
  &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  &lt;title&gt;Bookshop Catalog&lt;/title&gt;
  &lt;script&gt;
    window["sap-ushell-config"] = {
      defaultRenderer: "fiori2",
      applications: {
        "bookshop-display": {
          title: "Bookshop Catalog",
          description: "Manage Books and Authors",
          additionalInformation: "SAPUI5.Component=com.c16.bookshop",
          applicationType: "URL",
          url: ".",
          navigationMode: "embedded"
        }
      }
    };
  &lt;/script&gt;
  &lt;script id="sap-ushell-bootstrap"
    src="https://sapui5.hana.ondemand.com/1.120.43/test-resources/sap/ushell/bootstrap/sandbox.js"&gt;&lt;/script&gt;
  &lt;script id="sap-ui-bootstrap"
    src="https://sapui5.hana.ondemand.com/1.120.43/resources/sap-ui-core.js"
    data-sap-ui-theme="sap_horizon"
    data-sap-ui-resourceroots='{"com.c16.bookshop": "./"}'
    data-sap-ui-compatVersion="edge"
    data-sap-ui-async="true"
    data-sap-ui-frameOptions="allow"
    data-sap-ui-flexibilityServices='[]'
    data-sap-ui-libs="sap.m, sap.ushell, sap.fe.templates"
    data-sap-ui-xx-componentPreload="off"&gt;
  &lt;/script&gt;
  &lt;script&gt;
    sap.ui.getCore().attachInit(function() {
      sap.ushell.Container.createRenderer().placeAt("content");
    });
  &lt;/script&gt;
  &lt;style&gt;html, body, #content { height: 100%; margin: 0; padding: 0; }&lt;/style&gt;
&lt;/head&gt;
&lt;body class="sapUiBody sapUiSizeCompact" id="content"&gt;&lt;/body&gt;
&lt;/html&gt;</code></pre>
</details>

<h2><span class="sec-num">10</span> app/bookshop/webapp/Component.js</h2>

<details><summary>View Code</summary>
<pre><code>sap.ui.define(["sap/fe/core/AppComponent"], function (AppComponent) {
  "use strict";
  return AppComponent.extend("com.c16.bookshop.Component", {
    metadata: { manifest: "json" }
  });
});</code></pre>
</details>

<h2><span class="sec-num">11</span> package.json</h2>

<details><summary>View Code</summary>
<pre><code>{
  "name": "bookshop",
  "version": "1.0.0",
  "dependencies": {
    "@sap/cds": "^8",
    "express": "^4"
  },
  "devDependencies": {
    "@cap-js/sqlite": "^1"
  },
  "scripts": {
    "start": "cds-serve",
    "watch": "cds watch"
  },
  "cds": {
    "requires": {
      "db": {
        "kind": "sqlite",
        "impl": "@cap-js/sqlite",
        "credentials": { "url": ":memory:" }
      }
    }
  }
}</code></pre>
</details>

<h2><span class="sec-num">12</span> Features Included</h2>

<table class="data">
<thead><tr><th>Feature</th><th>Description</th></tr></thead>
<tbody>
<tr><td><strong>List Report</strong></td><td>Displays all books with sortable columns</td></tr>
<tr><td><strong>Object Page</strong></td><td>Detailed view with Book Details and Inventory sections</td></tr>
<tr><td><strong>Draft Support</strong></td><td>Create and edit with auto-save drafts</td></tr>
<tr><td><strong>Filters</strong></td><td>Filter by Genre, Author, and Published Year</td></tr>
<tr><td><strong>Sample Data</strong></td><td>5 classic books and 5 authors pre-loaded</td></tr>
<tr><td><strong>SAP Horizon Theme</strong></td><td>Modern SAP Fiori design system</td></tr>
</tbody>
</table>

<h2><span class="sec-num">13</span> Running the Application</h2>

<p><strong>Prerequisites:</strong> Node.js 18+ and npm installed.</p>

<ol>
<li>Create a new folder called <code>bookshop</code></li>
<li>Save each file above to its specified path</li>
<li>Open a terminal in the bookshop folder</li>
<li>Run <code>npm install</code> to install dependencies</li>
<li>Run <code>cds watch</code> to start the development server</li>
<li>Open the Fiori Elements URL shown in the console output</li>
</ol>

<div class="callout">
<strong>Tip:</strong> The app loads with sample data. Click any row to open the Object Page. Use the <strong>Create</strong> button to add new books.
</div>
