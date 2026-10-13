  TS EN MO 0613 Auto Complete Revision Network WBS @page { size: A4; margin: 20mm 18mm 20mm 18mm; } \* { box-sizing: border-box; margin: 0; padding: 0; } body { font-family: 'Segoe UI', Calibri, Arial, sans-serif; font-size: 10.5pt; line-height: 1.55; color: #1a1a1a; background: #f4f5f6; -webkit-print-color-adjust: exact; print-color-adjust: exact; } .doc-wrapper { max-width: 1100px; margin: 24px auto; background: #ffffff; box-shadow: 0 1px 8px rgba(0,0,0,0.08); border: 1px solid #d0d4d8; } /\* HEADER \*/ .doc-header { background: #003366; color: #ffffff; padding: 28px 36px 24px 36px; border-bottom: 4px solid #7fb3e0; } .doc-header-top { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 14px; } .doc-logo img { height: 40px; display: block; } .doc-classification { font-size: 8.5pt; letter-spacing: 1.2px; text-transform: uppercase; color: #7fb3e0; border: 1px solid #7fb3e0; padding: 3px 12px; border-radius: 2px; white-space: nowrap; } .doc-header h1 { font-size: 22pt; font-weight: 600; letter-spacing: -0.3px; margin: 0 0 4px 0; line-height: 1.2; } .doc-header .doc-subtitle { font-size: 11pt; color: #7fb3e0; font-weight: 400; } /\* META \*/ .doc-meta { padding: 16px 36px; background: #f7f8fa; border-bottom: 1px solid #d0d4d8; font-size: 9.5pt; color: #444; } .doc-meta table { width: 100%; border-collapse: collapse; } .doc-meta td { padding: 3px 12px 3px 0; vertical-align: top; } .doc-meta .meta-label { font-weight: 600; color: #003366; width: 90px; } /\* BODY \*/ .doc-body { padding: 28px 36px 36px 36px; background: #ffffff; } .doc-body p { margin: 8px 0; } .doc-body h2 { font-size: 14pt; color: #003366; margin: 24px 0 12px 0; padding-bottom: 6px; border-bottom: 2px solid #7fb3e0; display: flex; align-items: center; gap: 10px; } .doc-body h2 .sec-num { display: inline-block; background: #003366; color: white; font-size: 11pt; font-weight: 700; padding: 2px 9px; border-radius: 3px; line-height: 1; min-width: 26px; text-align: center; } .doc-body h3 { font-size: 11.5pt; color: #003366; margin: 18px 0 8px 0; font-weight: 600; } .doc-body h4 { font-size: 10.5pt; color: #1a5c8a; margin: 12px 0 6px 0; font-weight: 600; } .doc-body ul, .doc-body ol { margin: 8px 0 8px 22px; } .doc-body li { margin: 4px 0; } /\* TABLES \*/ table.data { width: 100%; border-collapse: collapse; margin: 10px 0 14px 0; font-size: 9.5pt; } table.data th, table.data td { border: 1px solid #d0d4d8; padding: 7px 10px; text-align: left; vertical-align: top; } table.data th { background: #003366; color: white; font-weight: 600; letter-spacing: 0.2px; } table.data tr:nth-child(even) td { background: #f7f8fa; } table.data td.center { text-align: center; } /\* CALLOUTS \*/ .callout { background: #f0f6fa; border-left: 4px solid #1a5c8a; padding: 12px 16px; margin: 14px 0; font-size: 10pt; color: #1f2937; } .callout.tip { border-left-color: #15803D; background: #f0fdf4; } .callout.warning { border-left-color: #C2410C; background: #fff7ed; } /\* PILLS — Clean Core levels \*/ .pill { display: inline-block; font-size: 8.5pt; font-weight: 600; padding: 2px 9px; border-radius: 10px; letter-spacing: 0.3px; white-space: nowrap; } .pill-a { background: #dcfce7; color: #15803D; } .pill-b { background: #dbeafe; color: #1D4ED8; } .pill-c { background: #fef3c7; color: #A16207; } .pill-d { background: #fee2e2; color: #B91C1C; } /\* SYSTEM PILLS — engagement context strip under the header \*/ .doc-pills { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 14px; } .doc-pills .doc-pill { display: inline-flex; align-items: center; gap: 6px; font-size: 8.5pt; font-weight: 500; padding: 4px 12px; border-radius: 16px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.28); color: #ffffff; letter-spacing: 0.2px; white-space: nowrap; } .doc-pills .doc-pill .doc-pill-icon { font-size: 9pt; opacity: 0.9; } .doc-pills .doc-pill.danger { background: rgba(254, 226, 226, 0.18); border-color: rgba(254, 226, 226, 0.35); } .doc-pills .doc-pill.warn { background: rgba(254, 243, 199, 0.15); border-color: rgba(254, 243, 199, 0.35); } /\* KPI STRIP — volume counters under the pills \*/ .doc-kpi-strip { display: flex; flex-wrap: wrap; gap: 18px; margin-top: 14px; padding-top: 12px; border-top: 1px solid rgba(255, 255, 255, 0.18); font-size: 9pt; color: rgba(255, 255, 255, 0.92); } .doc-kpi-strip .doc-kpi { display: inline-flex; align-items: center; gap: 5px; white-space: nowrap; } .doc-kpi-strip .doc-kpi-icon { font-size: 10.5pt; } .doc-kpi-strip .doc-kpi-value { font-weight: 700; color: #ffffff; } .doc-kpi-strip .doc-kpi-label { color: rgba(255, 255, 255, 0.78); } /\* PHASE TIMELINE \*/ .phase { border-left: 3px solid #7fb3e0; padding: 10px 16px; margin: 10px 0; background: #f7f8fa; } .phase strong { color: #003366; } .phase .phase-dur { color: #1a5c8a; font-size: 9pt; } /\* DOC FOOTER (inside wrapper) \*/ .doc-footer { background: #f7f8fa; border-top: 1px solid #d0d4d8; padding: 16px 36px; font-size: 9pt; color: #555; } .doc-footer table { width: 100%; } .doc-footer .footer-right { text-align: right; color: #003366; font-weight: 600; } @media print { body { background: white; } .doc-wrapper { box-shadow: none; border: none; margin: 0; max-width: 100%; } h2, h3 { page-break-after: avoid; } table.data { page-break-inside: avoid; } .phase, .callout { page-break-inside: avoid; } }

![C16](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABLAAAAEuCAYAAACedetbAAAmsElEQVR42u3dd7hvV13v+/eANJJQIggkQOgtoTdpgQNI8VK9gEcUFFFE5Cioj3qVg+eCwFX04AGkiVSliIXiAanSiwZBWpAiJaGqBIQQ0sf5Yy24ISTZe6+991pz/dbr9Ty/Z/OQvdb8/sYY87fW/OzvHLMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA2CGGIQDY2eac8wJ/SIzh5wQAAJAAC4CWFFoJswAAgARYALSNgitBFgAAsNUuYggAEl5twfcBAABIBxYAtX8DJ91YAABAOrAAaMHdUrqxAACABFgAAAAAJMACIN1X6cICAAASYAHQioVXCbEAAIAEWAAAAAAkwAIg3VfpwgIAABJgAQAAAEACLAAAAAASYAGQ2wdzGyEAAJAACwAAAIAEWAAAAACQAAsAAAAANuQAQwAA0FbtG3dkdc3qitWV1v+8fHXE+utS1cWrg9ZfB1ajOr067Tyvr1VfrL50rtcXqhPGGF802rBSnx2XrI6prlVd7Tyv/zbG+GujBCTAAgBgDy82D6luVN2suml13eo61SU3+C0PXX/t7vG/Vn20+kj14epd1YfGGB68AMv+7DigtaDqptUN1v/3sdUVLuTL7lgJsICVMwwBgKcQ7tMfLGP42YJzcc7Dq9tVd1h/3bDl/cPhV6u3V2+p3jLG+IiZgy3/7LhqdVx1i9YC7xtWh+zht/nYGOMYowkkwAJAiCW8gvM5965R3au6d3Xrtl+n+2eqV1R/U71njHGOWYX9/rlxTGsdU7dtLbg6ah996yPHGF82wkACLAAEWAIsWO+WeGD1X1u7rWdVfLm1IOvPxhjv3YvxuXv1F9Vhu/irh44xvm1FsQM+M36g+uHqrtVdWtv3bn/4iTHGS404kAALAAGWAIsde44dVv1E9VPVbXbA71OfqP6stTDrc3swTg+vnlZddDf++iXHGN+wuljRz4wrV/epfrS1TquLbsJhnzPG+HmjDyTAAkCIJbxix51X165+sfrpNr75+nZ2TvWa6qljjDddyDiN6verX9+D733pMcbJVhkr9HlxdPWT1f2rG29BCf86xriGmQASYAEgwBJgsWPOp9tUv1Xd3Wh818eqp1QvGGOcfp6nLb5o/aJ9T1x+jPEVw8o2/6y41Praf2Br+1lt9c/Fo8cYJ5kZIAEWAEIs4RUrfQ7duXrM+oUo5+/z1e9Vf1pdvHpVaxvY76krjjG+YDjZxiH3w1oLrw5ZUGkPHmO80AwBCbAAEGIJr1jJ8+Zmrd0Cd8cllVWdvP46vTqztY3RDz/X6yJtbZB1RnW1DX79VccYn7X62EafE4e3djvxL1TXa+tv7/109ZHqo+t/fqT6+BjjTLMFrIoDDAEAQM05r1T9YWtdFFsZzJ5Uvbt6b3VC9fHqC2OMsy6k9oOra1TXrK7VWhfU7atLbVLNV/Q7KTvkc+LI6peqh2/i+XVuX63+sf8/pPpodYKneALpwAJAF5buK1b+HDmw+tXWbhc8bIvK+Gj159XfjjE+uo/e10Va2zz6Hq09MfFqC56GY8YYH7MaWfDnxDVb2wvvJ6uDNvnwn2vt9txXVO8YY5xtRgAAWOkga18xmqzQefFDc84T5tY4c8750jnnzTfhfY4553FzzheuH3dprm81stDPiKvPOV8w5zxrk8+JT885HzfnvIlZAABAiCW8YueeCwfNOZ+4BRelc855zpzzJXPOq++wC/IL4yKdpX1GXHHO+aebHPieOef86znnXeecOpwBAEBwxQ5f/9eZc35wi4Kaj8w5b72Qcbj2nPNtCwmwbmFlspDz4rD1zqdTN3H9nzjnfPT6/loAAMB5Hf/Rzwmt2GkXpz8x5/zmFnVdPXnOedDCxmPMOR825/z6FgdYt7E6WcC58OA55xc3cd1/fs75iKV9LgDkKYQALNH7TjjRILBTNmp/SmtPDttsp1Q/OcZ49dLGZYwxq2fPOf+u+pvqpn4nZQd+PhxbPbvarCD1y9XvVc8eY5xmBgB2z0UMAQCw4henR1Sva2vCqy9Ut1lieNX3BlknVretXpgAi53z2XCxOecTqw9sUnh1RvW46mpjjKcIrwD8sgAA8N0Ny6vXVNfegsN/rrrjGOPT22Gs1i+mHzzn/Gj1pE0+/IFWK5v82XCr6kXVNTbpkO+qfn6McYLRB0gHFgDAuS5Qb7B+0bgV4dUXq/+yXcKrvjfI+oPqEdX0j6qs4u3Ec84nVO9oc8Krb6yfT8cJrwD8sgAAcN6L1FtWr62O2ILD/2d1tzHGZ7fr+I0xnjHnPK16TpvzD546sNiMz4XrVi+pbrRJh3x/db8xxmeMPkA6sAAAznORetvqTW1NeHVO9RNjjA9v93EcYzyv+tX8oyor8gTS6vg2L7x6bmv73wmvABJgAQCc9yL1Zq3teXXYFpXw2DHGa1dlPMcYT6melg4stu9nwsFzzmdWL96kz4XTqoeMMX7OJu0A+dcuAIDzuVC9fvX66hJbVMI7q8ev4NA+qrpKdU+/k7LNPhOOql5V3WyTDnlydY8xxnuMPkA6sAAAzudC9YrV66of2KISvlU9aIxxzqqN7fp7emD1r+nAYvt8Jtyk+sc2L7w6qbqt8AogARYAwAVcqF68tdsGj9rCMn5nO2/a3q5DrG9UP16dmQ4slv+ZcN/WnjJ4hU065Mda2+/qY0YfIAEWAMD5XKhetHp5dYMtLOPD1VNWfazHGO+rfisdWCz7M+GXqr+sDt2kQ360Om6McZLRB0iABQBwAR5f3W2La/jtMcbZO2S8n9zaEx7TgUXLC68eWz21Gpt0yM9UdxljfNXoAyTAAgC4gIvVe1e/ucVlvHuM8b93ypiPMWb1sOrb6cBiOZ8FY875jOp3NvGwX6ruPMb4ohkASIAFAHABF6xXq17Y5nVaXJDf2mljP8b4dPXYdGCxkPCqek718E087Dequ44x/tUMACTAAgC4kH2v/qy65BaX8voxxtt36DT8z+qDCbDY+vDqWdXPbuZhq58eY3zYDAAkwAIA6MK7nm69gDr+cKdOwBjjrOoRuYWQrfWM6uc3+Zi/P8Z4paEHSIAFANAFd1zcuM3d5+aCfKJ6806eizHGu6q/SQcWW/NZ8MTqFzb5sH9f/XejD5AACwBgF7cOPqdldOs8Y31D853u/6nOTAcWm/tZ8Ig2f/+5/6gesIOeOAqQAAsAYGN+qbrpAur4VvUC01FjjE9Wf5IOLNq08Oq+1VO34NC/PMb4NzMAkAALAOBCLlqvWP3uQsp52RjjP83Kdz22OjUdWBtd29eac54y997Hd8BY3bS1Bzhs9jXM344xXupUB0iABQCwC0+sDl9ILS8zHZ27C+vf2/surAN2aHh1SPXS6rD2TWfgKo/VZatXVBfb5EN/o3q4Mx0gARYAwC4uXG9SPXAh5ZxcvdWsdH5PZDw9HVh76unVTfbR9zplhT8DDqz+qrrSFhz+cWOMLzjFARJgAQDswpOrsZBaXjXGOMuUdN4urC+0d/uCHbADg9lHVQ/Zh9/ylBUerj+ojtuC455Y/bEzHCABFgDALi7y71zdfkEl/bVZuUC/X52lA2u31vW9qv/Zvn+4wCqO1d2rR27R4f/7GON0pzZAAiwAgF34Hwuq5ZvVm0xJF9SF9ZnqlenAaheBzG1a2/dqX/8efuoKjtWR1fO36PAfrF7szAZIgAUAsIuL1ztVt1lQSW/XjbFLT0sH1oWt6ZtXr60O3Q/f/lsrNlajelH1g1tUwhPGGOc4pQESYAEA7MKjF1bP20xJu+rCenv1oXRgdT6BzB1b6+C7xH46xKp1YD20+uEtOvZnq79xRgMkwAIA2MXF/g2qOyTA2o7+WID1fev5QdXftf/Cq1qhAGvOeVT1pC0s4SljjLOdygAJsAAAduFRC6vnlOr9pmW3vLj6Wm4hbM554JzzKa3dCnfQfj7cKnVgPbO65BYd+z+r5zqNARJgAQDs4qL/MtUDFlbWu8cYZ5mdduc2wlOrl7TDO7DmnNes3lX98iYd8tsr9ITGe21hCX8+xvimMxkgARYAwC48qDpkYTW907TskRe0Qzuw5pwHzDkfWX2guvkmHvrUFRi7g6o/3OIy/szpC5AACwBgN/zMAmv6oGlpT7qw3ld9pB3WgTXn/OHWgqv/VR22yYdfhQ6sX66uuYXH/9QY4x+cwQAJsAAAdhEA3LS6/gJL+5DZ2WMvbId0YM057zbnfFf1xup6W1TGt1fg1uHHpPsKgARYAEDb4vbBpflm9TlTs8f+vDprVTuw5pxHzDkfNef8WGtPGLz1Fpe03Tuwfr39+5TG3fESpy3Ach1gCAB2rld+dlzof3/0a06cT7j70cNIsYl+dIE1fXiMMU1Ne3ob4ZfnnG+sfqQV6cCacx5e3aP6sfX3taS92r69jbuvfrB6xBaXccIY41POXIAEWABsvUe/5sS5t18j0GI/XsTevDp6gaV92Oxs2F+2ewHWAQtdkwdXN63usP66Tct7wMB3nLaN18lvtvl7hp3Xq52uAAmwAGjbBVe7+l6CLNoZ3Ve1Z5uR871eWT27XXdYHbiJodRoLYQ6eP11aHW56vLrrytUx1THVteoLrpNxvq0bRpcH1E9fAGlCLAAEmAB0PYPrgRZbIK7L7Qu+1+14dsIvzbnfFO77sI6YH9srN7a3lQ7xXbtwHpYayHiVvr3ytMHARJgAdDqBFeCLNo/XRiXbZlPHywBVptwG+GBhmmvnb4Nz/sD2vq9r6reMMY4Zz+8v0tVN6quXl1x/XWF6qjq8Opi53odWJ1anbL++s/qs9Un118fr94/xjjNUgcSYAGQ8GqvjivEYi/cqVrq+jnR9OyVV7Tr2wj9Trr3ztiGNd+/tVBnq72xvQ+rDqxu2dpeaTdpLbi68h5+m4uvv77jZuf576fNOd9TvaV6c/UeD5gAdhIXGgAJr/YlIRYbvPh7TvVzCyztm2OMS5ihbbmmdtothJcbY/zbNpujt1a3X0ApVxxjfGED9R9d3bu6c/Vf+t7waTN8pvrz6kWeoAjsBBcxBAAJr1awDradW+f2QWindGDNOa9W3W4BpfzLnoRXc85D5pw/M+d8e2u3+D21umebH15VXbV6TPXJOeeb5py3cxoACbAASHiVEIv9dCF78eo6uX0Q9saZ26zeB7eMu0H+fnefljjnfFz1+ep51XELu5vlTtXb5px/P+e8vdMBSIAFQMKrhFjsYzdf8O8kXzE9bBNntX1C61H99ELKeecuaj1szvn/ttZt9Zjq0gsf3jtUb51zvmzOeTmnBZAAC4CERAmx2EdutuDavmZ6SIC1r/1QdfRCanlXFxxePbD6RPU/qu22F95/rT4253yIUwNIgAVAwqGEWOwDxybAgr0xxxhnb6N677uQOj4/xjjxfIKrq8w531D9WXXUNl4XR1TPnXO+es55SacJkAALAGCvHJMAi31sjPG6sQmq0xfwds/eZtPzowup4919f3j1kOojrT1ZcFXcszp+znmsTwYgARYA6WpKFxZtbC+c6yy4xJPNEtvhVNpG5/z1q6svpJzjz1XXJeacf1k9tzpsBdfINav3zjnv43QBEmABAOyxI6vD04EF7YQAq7rrgmr5wHp4dUxrYdb9VnydHF791ZzzQU4ZIAEWAOlmShcWe+DohdcnwCIB1j51pwXV8s9zzntX/1Bda4eslYtWL5hz/rzTBthuDjAEAEACrAvybVME7avbBw+qjltIOSdWP1X9YRv7R/0zW7vF+FvVKevXVUdUl6kObPlNDM+ecx44xni6lQmkAwuAdDGlC4tduNLC6zvTFME+80MtZ3+pI6sn7+b10BnVO6rHVT/S2n5Sh44xLj/GuPoY44ZjjGPHGEe1dpvezatHVf+48Pl46noHGkA6sAAAdn0RmQALdoRbLaiW3emS+ufqT6sXjzG+3u49/fKM6n3rr6esb1r/+OpeLbOZ4SVzztuNMf7J8gTSgQUAcIF+YOH1nWGKYJ+5xTap85PVPcYYNx5jPH13w6vOP9D68Bjj3tVdqi8v8L0eWv3tnPNKlieQAAsA4AIdkQ4sSIC1GH9S3XCM8Zp9+U3HGG+sbli9q2V2wv75nNO1IZAAC4DsH5V9sEiABe3UDdwv17L3vDun+sUxxsPGGPvl4Q1jjH+r7lq9eYHv/3bVr1qpQAIsAIDzdYncQgg7wfVbdnj1wDHGM/f3gcYY36ru2doeWUvz+PU9uwASYAEAfK+DFl7fOaYI9onrLri2h44xXrpZB1vv8LpPy9sT6+DqBXPOYbkCCbAAANpOAdZFTRG0ygHW48cYz9vsg44xvlA9eIHjcZPqgZYrkAALAKA9fZT9VjrAFEGrGmC9pvqdrTr4GOP11fNb5q2Eh1iyQAIsAIC2S4eTDizYN662sHpOqh40xtjqB4v8WvW1hY3N0dUjLVkgARYAwHedlQ4xaMWfQHiR6qiFlfVTY4wtD47Wa3jSAqft13VhAQmwAAC+68yF13eoKYK9dmTLux33PQuq5Sktb0P3S1cPsHSBBFgAAFWdkQALVt2VFlbPXNJnz/pTCZ+1wHn7JUsXSIAFwJ56wt2PHt4HK+j0BFjQDujAWpJTF7D31Xk9q+UF+jeec97G8gUSYAEA9J8Lr+8wUwR77YiF1XPK0gZojPGV6pULnLufsnyBBFgAAIt7+tbSL7whAdZe++ZCx+nlC6zpXnNOndNAAiwAYKc7eeH1/YApglYtwPrWQsfptQus7fLVD1nCQAIsANpB+0fZ/4q2X4ClAwv23qUWVs+pSxyk9c3c37jA0u5tCQMJsADYE8d/9HNzu9e/3d8D+9wXFl7fZUwR7LVDEmDtrrcssKa7WsLAEhxgCADaVsHVfa4ye+Vnt18j032uMr/v/dz82CvryOKkhdd3lCmCvXbQwur59oLH6u8XWNP155wXW+8QA0gHFgDttI4l3Vi0/ADrSFMEe+3AhdVz+oLH6qPV11te08NNLGMgARYA7WFwde5uprZZ95XbCjmPz6UDCxJgbaozlzpQY4xZfWiBpd3CMgYSYAGQriRB1g41xviP6qsLLvFKHiEPe3+qL6yecxY+Xv+8wJpuZhkDCbAAqD0PcLZLF9ae1inI2pE+tuDaLpbbCKEV3nNqiT68wJqublqABFgACa42GNg84e5HL7oz5Al3P3psdKN2IdaOcsLC67uqKYJWKcBa+oOsPrPAmo62jIEEWAAJrvbQzY+98neDoaWGWOeu69z16sbifHxk4fVdwxRBAqx2dIB1+TnnwZYykAALIPtctWfBVQvuxLqgevamG0uQtdqnxMLrO8YUwV45NQHWnjixOrvl7WN2JUsZSIAFoOuqDQRXLTDE2lUdG+3GEmSttA9UZyy4vuuZImiVOrAu2rIfbnFW9bUFlmY/QCABFkCCqy4k8Gmb7Im1J8ff2yDLqmqVnkR4est8bHwCLEgH1tY4eYE1HWYpAwmwADbfvBAtbJ+rtsHG7hs97hL2x9qMtcAuvWPBtR0957y0KYIN+/eF1XNIAqw2+FRWgPzrA0CbE1rt6d8bY4zN7BDaaFdS5xMmPfo1J86lBlfn9743Mm7f+Zo9HbfNWgvstjdXv7Lg+m5R/Z1pgja6p9OSXDwB1kYcaikDCbAAWkRwdWFfu7vhxWbcKtgCgqz90en1nTHYn0HWZq4F9sjbqjOrAxNgQQKsdnqAdXoCLIAEWEDCq419nwsLLra666pNCrI24xbFvQ2yLmg8N2st0Eb2wTplzvne6riFlngbswQbdlI1159ktwSHb4MxO8P2MwDf/zhUgARXe3yxPbZDcLUruxNoLeHphnvb1bZZa4G9Pmd/vXpSy92E+ogxxhlmivOs29Oqg7e4jNPHGIcsfJy+XF1uIeWcMsa4+MLH60XVgxZW1gPHGC921gMJsAC2R3j1He874cS2a3DVNn2S40a+7mbHHL0Z3UPmc9+ct1evPrXgEo8bY7zTTCHA2tA4/WN186WUUx0wxjhnweP13OohCyvr3mOMVzvrgbSBAqy+jT5xD2PXzriN8F+rDy24xLuYJdiwTyzsH/Evk61e9tQpljGQAAugbdV9VXvW2SN8aUuCrM3ovtrMNbdDvHzBtd3D9MCG/dPC6rncwsfrQAEWQAIsIOFVmxdiCa7akiBrs8IrIdY+96Jqqbf13HjOeQVTBBty/MLquWwCrD11smUMJMACyC1v2E+MxhgnVW9acIn3MUvtq9D3knPOd80572Y0doT3V2enA6ttGmCdWX3WMgYSYAFs3w6Y83b6CK7a8rBws7uvdGHtc89bcG0/Znr2md+tbl393Zzzr+acVzQkrXI4fWr1sQRYu+vwhdXz6THGWVYykM0BAdIJxD6bA0HStveK6svV5RdY223nnEeOMb5kmtqbsPeG1S+e6/+6b3XXOedjq//lQrlVvo3wegup5SoLH6tLZhN+gHRgASS8gpbbqXFG9cwF/+70QLPU3oRXo3p6ddG+v+PkD6oPzDmPM1Ir6e0LquVqCx+rSy2sno9bvoAAC2AFbt3S8WMtWAv73DOr0xda28+Ynr3y8Oo2F/Lfr1e9bc75gjnnDxqulfKalvOQhqunA2tPfNjyBRJgAQB03i6sf2/tiYRLdN05563MUhsJeK9c/d7uLIHqp6uXGbWVO6/fs5ByrrreDbjE8+Qi1RELK+stVjCQAAsA4Hz9f609+WqJ/pvp2ZDnVBffg7//ZEO2cl69kDoOqa6w0DG6fMvaq/iT60+IBUiABQDQ93VrfKbldmHdf855pFlqT7pKfqG68x58yXvHGK8xcgmw9p/rL3SMlvZEzjdbtkACLACAC/WE6owF1nVg9UjT0+6GV8e0591U/93ItYrB9L+0nA3Bb7TQYbqCAAsgARYAsO26sJ6+0PJ+cc55KbPUrsKrQ1rby+pie/BlbxljuGheXc9bSB03XOj4XHVBtZxavcGSBRJgAQDs0u9WJy+wrotXv2p62p19rPbkVq2zq18xbCvtudVpCbAuyDELquWvxxjfsGSBBFgA7asujbGTj4+1sOJz+rXqsQst71fnnJczS11Q99WDq4fv4Zc9Z4zxQaO30uf0V6u/WEAp15pzHrHAIbpuuuUAEmABANvR06v3L7Cuw6rHmZ7OL7y6RfWsPfyyr1WPMXo75pxewrXQcQmwLsinq7dZqkACLACAdrdj4+zqoa3dXrY0P7ce1tB3w6sjq1dUB+/hl/7OGOM/jOCOOKePr45fQCm3X9i5c41qKV1hfzrGmFYrkAALYDVu3XLLmLVgLWza+L6/+qOF/j71rDnnAWap5pyXqP6uOmoPv/Q91TOMYDvtKaMJsL7HrRZSx8kt9wEaQAIsAICle0z1kQXWdWO3vtWc86Dqle355tinVw8ZY5xjibeTQulXVe/Y6nN3znnZBQ3LrRdSx5Ns3g4kwAJYnQ4YHTfWgrWw6fN6WvUTrQUeS/Pbc87j2rnh1UWrF1d32MCXP3aM8S9W+I706wu4Hrr3gsZjCR1hX6meZmkCCbAAViNIEFhYC9bCls3rh6vfWGBpB1R/M+e8ejsvvDqgekl1vw18+fHVH1jZO/Z8/ofqr7a4jP97IefRVVvGBu5PHGOcanUCCbAAAPb6ovep1UsXWNplqtfMOS/VzgqvXlb92Aa+/BvVj48xzrKqd7Tfqs7cwuPfcc55yQWMwz0XUMMHq2dakkACLIDV6LzRcWMtWAuL8HPVhxZY17Wrv55zHtjqh1eHV6+u7rvBb/HQMcanLeUd/zn9qerxW1jCQdVPLmAotvpWxjOrB48xzrQqgQRYAJsbXOzrcGF/fE+sBTY8B6euX/B9ZYHl3bG1EOuQVje8OrJ6e/UjG/wWfzLGeLmVvE8cvL4HWdv8iYT/sIXHf9gWn09XbmP7x7WPbx38Z6cTkAALYHt34AgrrAVrYZFz+tnq7tUpCyzvntXr55yXaPXCq5tW723t6Ysb8Y/VI1dk4/qDF1LOpbf5uXx29aDqW1tUwg3mnFv5BMAHV2OLbx18gp8qQAIsgO3bgaPTxlqwFhY/p/9U3b9a4j5Kt6veOue8bKsTXj28eld19Aa/xUnVvdefKLndLSmcPHYFzuVPVr+2hSU8aovOqQOrh2zh+/5G9QC3DgIJsACWF17sKoTY3b+HtcBi5vN11Y+3zBDrxtXxc87btr2Dq0vPOf+iekYb7zo6pbrHGOPLK7L0rrWgWm6/Iufys6tXbtHh7zfnvN4WHPdBbTwQ3ltnrz9I4WN+kgAAALRpIcv95pxnzmU6a875uPWn9m23cb3/nPMre/n+z5hz/l8rtt4evqD19dEVGtfD5pzv26Jx/MvNvg11zvmJLVw3v+InBwAAwNZc/N5nzvntuVzvnnMeu03G8jpzzr/dB+/5zDnn/VZwrb15YWvrnis0tpefc352C8bwnDnnLTfxfT5iC9fLc/3EAAAA2NqL39vNOb++4BDr7Dnn8+ecRy90/I6acz57vWtsX3Se/fgKrrEbrc/jknxyznnYCo3xMXPOr23BOH5wMzol55w/OOc8eas6zdb33gIAAGCLL36vP+c8cS7baXPOP5pzXnlBY/b8Oefp+/C2yQeu4No6cM75roWuqZfPOS+yQmN9h/XzZLP9xia8t5du0Rp52Xa8lRkAAKAVDrEuN+d851y+c+acb5pzPmDOecgmj9Gl5pw/N+d86z5+T6es2p5X59qz6EULX08vm3MeukJjfqc55zc3eQxP35+3Es45H7pFa+PFc86L+ukAAACwvIvfg+acfzK3j6/NOV+yHipddT+NyXXnnL+0vr/V6fvhPXx5znnTFVxLV5pzvmGbrKMT5pw/vEJjf4s551c3eQxPmnNedj+8l1vOOU/dgjXx/FXqzgN2Ho8EBwB2SpD1k9Uzq4tvs9I/U72n+nj1ifXXJ8cY39zF+x3V5aorVlerbrj+ukl15H6s98PVvcYYn12htXO96qHVz1bbbY+p46sXVn87xjhxm8/DsdUbqqM28bAfqH54jHHyPnoPN6zeWl1qE9/DOdVvjzF+308CIAEWAMC2uAC+RvXS6mYr8HbOqr5ZnbL+Oq06uLrY+uvS1WZv0vz86hFjjG9v0/UxqitVx1TXr25a3Xr9/1sF/1K9q3p39f7qhDHGGdtsjq5avaa67iYe9oPVXcYY/7aXtd+xevn6ublZvl49YIzxOj8BgARYAADb6gL4gOo3qt9pLfBh751a/eIY44VL37+qunxrXWlHV1de//MqrXWpXa218G+nOKu1zr4Tqo+1FnB9svrUGOPrC57Hw6pnVD+1iYf9UvWgMcabN7Lpf/Vr1e9WB2xyYHmvMcYnfUQBCbAAANquQdZ1qj+tbmM09sp7qoeMMf5lgXP8R9U1W7uV8sjWwisbWO+er1WfrT5fvXGM8bQFzu/PVH9cHbqJt+K9sHriGONTuxmY3qt6QpvbMTarZ1W/McY4xVIGEmABALTdQ6xRPaj6vfbvvlCr6FvVo6unjTHOWej8fr66gqnaa68aY9xnoXN8TGu35R27iYc9u3p99brqHa11Z51cHd7a7YE3qm5b3b/N3a+r6l+rnx1jvM2yBRJgAQC0akHWxavfqh7Z5nVzbGevr35h6Ru1C7Ba+QDrO08arR5VPaa1EGknOqd6WmubtZ9qyQKryGNUAYAdb4zxzTHGb7e2B9LTqtONShf0hMG7jzHutkpPGWTbn79njDGeVF27evEOHIJXVzccYzxKeAUkwAIA2BEXwl8ZY/xydY3qya095Y+1fZAeUt1ojPFaw8FCz98vjjEeWB1X/cMOeMtvqW41xrj3GOMjVgCQAAsAYMddCH9+jPFr1ZWq32xtM+ud6JPVI6prjjGev9S9ruA85+87xxi3rG5Xvaq12+taoVsFX1vdeYxxxzHGe804YA8sAACqmnNepLpL9bDqHtUBK/6W31394freR+ds43mzB1arvwfWbqyDa1W/Uv10dbFt+ja+XD2v+pMxxucsSSABFgAAu7gYvkxrTxf78dZuVVqV36f+o3pZ9YIxxj+tyFwJsBJgnWs9HF7dc/38vVvLD7O+3tqTDv+qevUY40xLEUiABQDABi6Ij2qtI+vu1Z2qw7bZWzittduRXlS91gUyO+jcPWz93L1vdfvqsgsp7RPV/15/vWOMcZbZAkiABQCwDy+ID65uvX4xfPvqltUhLfNJgm9Yf719jHGa2cP5O69W3epcrxu0/28V/kr1T9X71l/HjzG+bDYAEmABAGziBfGB1fWrm6y/blhdu7r0ZpXQ2ubzH6w+tP7nu10gw26fv0dXV6mueq4/r1AdXh16rtdhrYXVZ1bfXn+duv7nt1oLqk481+uk6jNjjC8ZaYAEWAAAC70w/oHWgqyrrF8MX6E6qrVg61Lrr0tUB1cHVge19uToM1q75e/cr1Orf6++WH3pXH+eVJ0wxjjFiAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABA/R81FA7Y8Ft1EQAAAABJRU5ErkJggg==)

Reference

# TS EN MO 0613 Auto Complete Revision Network WBS

Topic

TS EN MO 0613 Auto Complete Revision Network WBS

Date

13 October 2026

Audience

CIOs, SAP program leaders, transformation architects

Author

C16 — AI for SAP operational efficiency

Scope

Version

1.0

## 1 Document Organization

### 1.1 Document Log

Version

Status

Date

Created By

Role

Comments

0.1

Draft

2026-10-13

C16 (Auto-generated)

Author

Initial Technical Specification — derived from FSD\_EN-MO-0613 v0.1 (Muralikrishna K, 10 Sep 2026). FS reviewed by Shigeo Yamaguchi 22 Sep 2026.

### 1.2 Integration, Document Reference

S. No.

Referred Document Name

Version

URL / Location

1

FSD\_EN-MO-0613 Auto Complete Revision, Network and WBS

0.1

Project Polaris Lodestar Phase 2A document repository

2

MO-0595 Email Template

Current

Referenced for WBS TECO email notification to EC FI

## 2 Code Quality

Final Solution

Category

Comments

Custom ABAP Executable Report with Level B BAPIs

**Tier 3 — Legacy Development**

Uses custom BAPI /AXONEBX/GET\_REV\_CLOSE (not released), standard Level B BAPIs (BAPI\_BUS2002\_SET\_STATUS in FG CNIF\_STATUS\_2002, BAPI\_BUS2054\_SET\_STATUS in FG CNIF\_STATUS\_2054), and direct SAP transparent table reads (T352R, JEST, AUFK, QMEL, DIWPS\_RV\_CR). Email via SO\_NEW\_DOCUMENT\_ATT\_SEND\_API1 (FG SOI1). All Level B — fully functional on S/4HANA on-premise per the classic ABAP language version contract.

## 3 Program Attributes

**Program Title**

Auto Complete Revision, Network and WBS

**Program Name**

ZPM\_AUTO\_COMP\_REV\_NW\_WBS

**Program Type**

Executable (Type 1)

**Package**

ZPM\_REVISION (to be created per project standards)

**Authorization Group**

As per BU decision

**Transaction Code**

N/A — Runs as background batch job only (SM36/SM37)

**Include Programs**

N/A

**Function Modules**

/AXONEBX/GET\_REV\_CLOSE, BAPI\_BUS2002\_SET\_STATUS (FG: CNIF\_STATUS\_2002), BAPI\_BUS2054\_SET\_STATUS (FG: CNIF\_STATUS\_2054), BAPI\_TRANSACTION\_COMMIT (FG: BAPT), SO\_NEW\_DOCUMENT\_ATT\_SEND\_API1 (FG: SOI1)

**Message Class**

ZPM\_REVCOMP (to be created)

**SAP Tables Read**

T352R (Revision Master), JEST (Object Status), DIWPS\_RV\_CR (Revision Work Packages), QMEL (Notification Master), AUFK (Order Master), T325R (Revision–Network Assignment), TJ02T (Status Texts)

**Custom Tables**

N/A — No custom tables required

**Custom Indexes**

N/A

**CDS Views**

N/A — Classic ABAP executable program

**OData Service**

N/A — Background batch job

**Business Object**

N/A

**Fiori App Name**

Fiori Tile planned as separate deliverable per SIA Code Quality Strategy

**Group Name**

TBD during Fiori Tile development

**Catalog Name**

TBD during Fiori Tile development

### 3.1 Selection Screen

Block Name: **Revision Selection Criteria**

P / S

Type / Field Name

Mandatory

Default

Parameter ID

Search Help

Selection Screen Text

S

T352R-REVNR (TYPE REVNI, CHAR 8)

No

—

S\_REVNR

Standard

Revision Number

S

T352R-REVTY (TYPE DIWPS\_REVTY\_CORE, CHAR 2)

No

—

S\_REVTY

Standard

Revision Type

S

T352R-REVBD (TYPE REVBD, DATS 8)

No

—

S\_REVBD

Standard

Revision Start Date

S

T352R-REVED (TYPE REVED, DATS 8)

No

—

S\_REVED

Standard

Revision End Date

S

T352R-IWERK (TYPE IWERK, CHAR 4)

No

—

S\_IWERK

Standard

Planning Plant

S

T352R-VAPLZ (TYPE GEWRK, CHAR 8)

No

—

S\_VAPLZ

Standard

Main Workcenter

S

T352R-VAWRK (TYPE WERGW, CHAR 4)

No

—

S\_VAWRK

Standard

Main Workcenter Plant

S

T352R-ZZ\_ESLOT\_START (DATS 8)

No

—

S\_ESLOTS

Standard

eSLOT Start Date

S

T352R-ZZ\_ESLOT\_END (DATS 8)

No

—

S\_ESLOTE

Standard

eSLOT End Date

P

TYPE i (integer, default 60)

No

60

P\_DAYS

N/A

Days after Revision End Date

### 3.2 Validation of Selection Criteria

1\. At least one selection criterion must be provided. If all selection fields are empty → display error message ZPM\_REVCOMP 009 "No revisions found matching selection criteria" (Type E) and stop processing.

2\. **P\_DAYS**: validated as a positive integer > 0. Default value = 60. Non-numeric or negative values raise an error.

3\. **Date range**: If both S\_REVBD (start) and S\_REVED (end) are provided, start must be <= end date.

4\. All selection parameters are optional — allows flexible batch variant configuration.

### 3.3 CDS Views / AMDP / Table Function

Not applicable for this object. This is a classic ABAP executable program that reads directly from SAP transparent tables. No CDS views, AMDP classes, or table functions are created.

### 3.3.1 Selection Condition

Not applicable — no CDS views are used.

### 3.3.2 Join Condition

Table joins performed in ABAP:

Source Table → Field

Target Table → Field

Purpose

T352R.OBJNR

JEST.OBJNR

Revision status check (REL)

T352R.REVNR

DIWPS\_RV\_CR.WPID

Get linked Notifications and Orders

DIWPS\_RV\_CR.NOTIFID

QMEL.QMNUM → QMEL.OBJNR → JEST.OBJNR

Notification status (NOCO)

DIWPS\_RV\_CR.ORDER\_NO

AUFK.AUFNR → AUFK.OBJNR → JEST.OBJNR

Order status (CLSD)

T325R.REVNR

T325R.AUFNR

Revision to Network assignment

AUFK.AUFNR

AUFK.PSPEL

Network to WBS Element

### 3.3.3 Fields

Key fields read per table (verified via DD03L batch\_field\_lookup):

Table

Fields

**T352R**

REVNR (CHAR 8, DE: REVNI), REVTY (CHAR 2, DE: DIWPS\_REVTY\_CORE), REVBD (DATS, DE: REVBD), REVED (DATS, DE: REVED), IWERK (CHAR 4, DE: IWERK), VAPLZ (CHAR 8, DE: GEWRK), VAWRK (CHAR 4, DE: WERGW), AUFNR (CHAR 12, DE: NW\_AUFNR), OBJNR (CHAR 22, DE: J\_OBJNR), PSPEL (NUMC 8, DE: PS\_PSP\_ELE), ZZ\_ESLOT\_START, ZZ\_ESLOT\_END

**JEST**

OBJNR (CHAR 22, DE: J\_OBJNR), STAT (CHAR 5, DE: J\_STATUS), INACT (CHAR 1, DE: J\_INACT)

**DIWPS\_RV\_CR**

WPID (CHAR 8, DE: REVNI), NOTIFID (CHAR 12, DE: QMNUM), ORDER\_NO (CHAR 12, DE: AUFNR)

**QMEL**

QMNUM (CHAR 12, DE: QMNUM), OBJNR (CHAR 22, DE: QMOBJNR)

**AUFK**

AUFNR (CHAR 12, DE: AUFNR), OBJNR (CHAR 22, DE: J\_OBJNR), PSPEL (NUMC 8, DE: PS\_PSP\_ELE)

### 3.3.4 Additional Details

**Verified Status Codes** (confirmed from TJ02T on the live SAP system):

ISTAT

Short Text

Description

Used For

I0002

REL

Released

Revision eligibility check

I0045

TECO

Technically completed

Network and WBS completion target

I0046

CLSD

Closed

Order status check / Revision close target

I0072

NOCO

Notification completed

Notification status check

### 3.3.5 GIT Repository Details

Not applicable — backend ABAP executable deployed via transport request. The separate Fiori Tile development will have its own GIT repository documented in a corresponding TS.

### 3.4 Authorization Requirements

Authorization is managed at the batch job scheduling level as per Business Unit (BU) decision. The program does not implement explicit AUTHORITY-CHECK statements. Access control is enforced by:

1\. SM36/SM37 job scheduling authorization (S\_BTCH\_JOB, S\_BTCH\_ADM)  
2\. Plant-level PM authorization objects (I\_IWERK, I\_BEGRP) already assigned to the batch user profile  
3\. The batch job user must have authorization for the BAPIs: BAPI\_BUS2002\_SET\_STATUS, BAPI\_BUS2054\_SET\_STATUS, and /AXONEBX/GET\_REV\_CLOSE

### 3.4.1 Definition

Standard authorization objects S\_BTCH\_JOB and S\_BTCH\_ADM control batch job scheduling. Plant-level PM authorization objects (I\_IWERK for planning plant, I\_BEGRP for planner group) control access to maintenance revision data. No custom authorization object is created.

### 3.4.2 Defined Fields

Auth Object

Field

Value

S\_BTCH\_JOB

JOBGROUP

\* (all job groups)

S\_BTCH\_JOB

JOBACTION

RELE (release jobs)

I\_IWERK

IWERK

ECE2 and others per variant

B\_USERSTAT

ACTVT

02 (change) — for status changes

### 3.4.3 Procedure

The batch job user profile must include the above authorization objects. The security administrator assigns these via SU01/PFCG based on the agreed batch user role. The batch variant is configured with required selection parameters and scheduled via SM36 as a daily job during off-peak hours.

### 3.4.4 DCL Details

Not applicable — no CDS views or data control language objects are required.

### 3.4.5 BTP Details

**xs-security Configuration**

N/A — runs on S/4HANA on-premise, not on BTP

**IDP Setup**

N/A

**BTP Role Collections**

N/A

### 3.5 Technical Flow Diagram

#mermaid-1791908260783{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;fill:#000000;}@keyframes edge-animation-frame{from{stroke-dashoffset:0;}}@keyframes dash{to{stroke-dashoffset:0;}}#mermaid-1791908260783 .edge-animation-slow{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 50s linear infinite;stroke-linecap:round;}#mermaid-1791908260783 .edge-animation-fast{stroke-dasharray:9,5!important;stroke-dashoffset:900;animation:dash 20s linear infinite;stroke-linecap:round;}#mermaid-1791908260783 .error-icon{fill:#552222;}#mermaid-1791908260783 .error-text{fill:#552222;stroke:#552222;}#mermaid-1791908260783 .edge-thickness-normal{stroke-width:1px;}#mermaid-1791908260783 .edge-thickness-thick{stroke-width:3.5px;}#mermaid-1791908260783 .edge-pattern-solid{stroke-dasharray:0;}#mermaid-1791908260783 .edge-thickness-invisible{stroke-width:0;fill:none;}#mermaid-1791908260783 .edge-pattern-dashed{stroke-dasharray:3;}#mermaid-1791908260783 .edge-pattern-dotted{stroke-dasharray:2;}#mermaid-1791908260783 .marker{fill:#666;stroke:#666;}#mermaid-1791908260783 .marker.cross{stroke:#666;}#mermaid-1791908260783 svg{font-family:"trebuchet ms",verdana,arial,sans-serif;font-size:16px;}#mermaid-1791908260783 p{margin:0;}#mermaid-1791908260783 :root{--mermaid-font-family:"trebuchet ms",verdana,arial,sans-serif;}Syntax error in textmermaid version 11.13.0

### 3.6 UI Details

Not applicable — this program runs as a background batch job with no interactive UI. A separate Fiori Tile is planned as a separate deliverable per SIA Code Quality Strategy.

### 3.6.1 UI Mock Screens

**Application Name**

N/A — background batch program

**Site**

N/A

**URL**

N/A

**Mockup**

N/A — no interactive screens

### 3.6.2 Navigations

Not applicable.

### 3.6.3 Actions

Not applicable.

### 3.6.4 Validations

Server-side only — see sections 3.2 (Validation of Selection Criteria) and 3.7 (Processing Logic).

### 3.6.5 Other Details

Not applicable.

### 3.7 Processing Logic

**Commit/Rollback Strategy:** Each BAPI call is followed by BAPI\_TRANSACTION\_COMMIT(WAIT='X') on success or BAPI\_TRANSACTION\_ROLLBACK on error. Each revision + network + WBS chain is committed independently — a failure on one revision does not roll back or affect processing of others.

**STEP 1 — Fetch Eligible Revisions:**

`SELECT REVNR REVTY REVBD REVED IWERK VAPLZ VAWRK AUFNR OBJNR PSPEL FROM T352R INTO TABLE lt_revisions WHERE REVNR IN s_revnr AND REVTY IN s_revty AND REVBD IN s_revbd AND REVED IN s_reved AND IWERK IN s_iwerk AND VAPLZ IN s_vaplz AND VAWRK IN s_vawrk AND ZZ_ESLOT_START IN s_eslots AND ZZ_ESLOT_END IN s_eslote.`

If lt\_revisions is empty → message ZPM\_REVCOMP 009, EXIT.

**STEP 2 — Filter by Status (REL) and Age:**

For each revision: read JEST WHERE OBJNR = T352R-OBJNR AND INACT <> 'X' AND STAT = 'I0002' (REL — confirmed from TJ02T). Also check: REVED <= SY-DATUM – P\_DAYS (default 60). Remove revisions not meeting both conditions.

**STEP 3 — Check Linked Notifications and Orders:**

For each remaining revision:

• Read DIWPS\_RV\_CR WHERE WPID = REVNR → collect NOTIFID (TYPE QMNUM, CHAR 12) and ORDER\_NO (TYPE AUFNR, CHAR 12).  
• For each NOTIFID: Read QMEL-OBJNR (TYPE QMOBJNR, CHAR 22) WHERE QMNUM = NOTIFID. Read JEST WHERE OBJNR = QMEL-OBJNR AND INACT <> 'X'. Check STAT = 'I0072' (NOCO).  
• For each ORDER\_NO: Read AUFK-OBJNR (TYPE J\_OBJNR, CHAR 22) WHERE AUFNR = ORDER\_NO. Read JEST WHERE OBJNR = AUFK-OBJNR AND INACT <> 'X'. Check STAT = 'I0046' (CLSD).  
• If ANY notification is NOT NOCO or ANY order is NOT CLSD → skip revision, log ZPM\_REVCOMP 002.

**STEP 4 — Close Revision:**

Call `/AXONEBX/GET_REV_CLOSE` with I\_REVNR = revision REVNR (TYPE REVNI, CHAR 8), I\_WERKS = revision IWERK (TYPE IWERK, CHAR 4). Check return for errors. Success → log ZPM\_REVCOMP 001. Error → log ZPM\_REVCOMP 010 with BAPI message text.

**STEP 5 — Process Networks:**

Read T325R WHERE REVNR = closed revision REVNR → get network AUFNR. For each network:

• Read T325R WHERE AUFNR = network AUFNR AND REVNR <> current revision → get other linked revisions.  
• For each other revision: check CLSD via JEST (STAT = 'I0046').  
• If ALL other revisions CLSD → Call `BAPI_BUS2002_SET_STATUS`:

Parameter

Direction

Type

Value

NUMBER

IMPORTING

BAPI\_NETWORK\_LIST-NETWORK (NW\_AUFNR, CHAR 12)

Network AUFNR

SET\_SYSTEM\_STATUS

IMPORTING

BAPI\_SYSTEM\_STATUS-SYSTEM\_STATUS (CHAR 4)

'TECO'

RETURN

EXPORTING

BAPIRETURN1

Check TYPE for E/A

Then call BAPI\_TRANSACTION\_COMMIT(WAIT='X'). Log ZPM\_REVCOMP 003.  
• If ANY revision NOT CLSD → skip, log ZPM\_REVCOMP 004.  
• If revision has no linked network → log ZPM\_REVCOMP 005.

**STEP 6 — Process WBS Elements:**

For each TECO'd network: Read AUFK WHERE AUFNR = network AUFNR → get PSPEL (TYPE PS\_PSP\_ELE, NUMC 8). Read AUFK WHERE PSPEL = same PSPEL AND AUFNR <> current network → get other linked networks. Check each TECO via JEST (STAT = 'I0045').

If ALL TECO → Call `BAPI_BUS2054_SET_STATUS`:

Parameter

Direction

Type

Value

I\_WBS\_SYSTEM\_STATUS

TABLES

BAPI\_WBS\_MNT\_SYSTEM\_STATUS

WBS\_ELEMENT = PSPEL (PS\_POSID, CHAR 24), SET\_SYSTEM\_STATUS = 'TECO'

RETURN

EXPORTING

BAPIRETURN1

Check TYPE for E/A

Then call BAPI\_TRANSACTION\_COMMIT(WAIT='X'). Log ZPM\_REVCOMP 006.  
If ANY network NOT TECO → skip, log ZPM\_REVCOMP 007.

**STEP 7 — Email Notification (Plant ECE2 only):**

If revision IWERK = 'ECE2' AND WBS was TECO'd:

• Read SO15 distribution list for EC FI recipients.  
• Compose email per MO-0595 template.  
• Call `SO_NEW_DOCUMENT_ATT_SEND_API1`:

Parameter

Direction

Type

DOCUMENT\_DATA

IMPORTING

SODOCCHGI1 (subject, doc\_size, obj\_descr)

PACKING\_LIST

TABLES

SOPCKLSTI1

CONTENTS\_TXT

TABLES

SOLISTI1 (email body per MO-0595)

RECEIVERS

TABLES

SOMLRECI1 (from SO15 dist list)

Handle exceptions: TOO\_MANY\_RECEIVERS, DOCUMENT\_NOT\_SENT, DOCUMENT\_TYPE\_NOT\_EXIST, OPERATION\_NO\_AUTHORIZATION, PARAMETER\_ERROR, X\_ERROR, ENQUEUE\_ERROR — all caught and logged as warnings. Does not affect status changes.

**STEP 8 — Display Log:**

Collect all messages in lt\_log. Foreground: CL\_SALV\_TABLE ALV with color coding. Background: WRITE to spool for SM37 review.

### 3.8 Reusable Code

The following should be implemented as reusable local class methods:

Method

Description

Parameters

CHECK\_STATUS

Generic JEST status check for any object

IV\_OBJNR (TYPE J\_OBJNR), IV\_STAT (TYPE J\_STATUS) → RV\_ACTIVE (TYPE ABAP\_BOOL)

COLLECT\_MESSAGE

Append message to log table

IV\_TYPE, IV\_ID, IV\_NUMBER, IV\_V1–V4, IV\_REVNR, IV\_AUFNR, IV\_PSPEL, IV\_STEP

SEND\_EMAIL

SO\_NEW\_DOCUMENT\_ATT\_SEND\_API1 wrapper with SO15 lookup

IV\_WBS\_ELEMENT, IV\_PLANT, IV\_DIST\_LIST

BAPI\_COMMIT

BAPI\_TRANSACTION\_COMMIT(WAIT='X') with BAPIRET2 error logging

RV\_SUCCESS (TYPE ABAP\_BOOL)

### 3.9 Messages

Message Class

ID

Type

Message Text

ZPM\_REVCOMP

001

S

Revision &1 closed (CLSD) successfully

ZPM\_REVCOMP

002

E

Notification &1 / Order &2 still open — cannot close Revision &3

ZPM\_REVCOMP

003

S

Network &1 completed (TECO) successfully

ZPM\_REVCOMP

004

I

Revision &1 still open — cannot complete Network &2

ZPM\_REVCOMP

005

I

Revision &1 closed without linked network

ZPM\_REVCOMP

006

S

WBS &1 completed (TECO) successfully

ZPM\_REVCOMP

007

I

Network &1 not yet completed — cannot complete WBS &2

ZPM\_REVCOMP

008

S

Email sent to EC FI distribution list for WBS &1 TECO (Plant ECE2)

ZPM\_REVCOMP

009

I

No revisions found matching selection criteria

ZPM\_REVCOMP

010

E

Error closing Revision &1: &2

ZPM\_REVCOMP

011

E

Error completing Network &1: &2

ZPM\_REVCOMP

012

E

Error completing WBS &1: &2

### 3.10 Subroutines / Methods

Name

Description

GET\_REVISIONS

Reads T352R matching selection criteria; filters by REL status (I0002) and age (REVED <= SY-DATUM – P\_DAYS)

CHECK\_STATUS

Generic: reads JEST for OBJNR, checks STAT value and INACT <> 'X'. Used for REL/NOCO/CLSD/TECO

GET\_LINKED\_ITEMS

Reads DIWPS\_RV\_CR (WPID = REVNR); returns NOTIFID and ORDER\_NO lists

CLOSE\_REVISION

Calls /AXONEBX/GET\_REV\_CLOSE (I\_REVNR, I\_WERKS); logs BAPIRETURN1 messages

GET\_NETWORKS

Reads T325R for REVNR→AUFNR; checks multi-revision linkage

COMPLETE\_NETWORK

BAPI\_BUS2002\_SET\_STATUS (NUMBER=AUFNR, SET\_SYSTEM\_STATUS='TECO') + BAPI\_TRANSACTION\_COMMIT(WAIT='X')

GET\_WBS\_ELEMENTS

Reads AUFK (AUFNR→PSPEL); checks multi-network linkage

COMPLETE\_WBS

BAPI\_BUS2054\_SET\_STATUS (I\_WBS\_SYSTEM\_STATUS: WBS\_ELEMENT=PSPEL, SET\_SYSTEM\_STATUS='TECO') + BAPI\_TRANSACTION\_COMMIT(WAIT='X')

SEND\_EMAIL

Plant ECE2 only: SO\_NEW\_DOCUMENT\_ATT\_SEND\_API1 with SO15 dist list and MO-0595 template

DISPLAY\_LOG

CL\_SALV\_TABLE (foreground) or WRITE to spool (background)

## 4 Report Output

### 4.1 Output Method

**Background mode:** Output written to spool for review via SM37 / SP02.  
**Foreground mode (testing):** ALV grid display using CL\_SALV\_TABLE.

### 4.2 Main Heading

Auto Complete Revision, Network and WBS — Processing Log

### 4.3 Sub Heading

Execution Date: SY-DATUM | Time: SY-UZEIT | User: SY-UNAME | Days Parameter: P\_DAYS

### 4.4 Layout / UI Design

Col #

Field

Type

Description

1

REVNR

CHAR 8

Revision Number

2

AUFNR

CHAR 12

Network Number

3

PSPEL

NUMC 8

WBS Element

4

STEP

CHAR 20

Processing Step (Revision / Network / WBS / Email)

5

MSGTY

CHAR 1

Message Type (S=Success, E=Error, I=Info, W=Warning)

6

MSGTX

CHAR 220

Message Text (full BAPI return message)

7

TIMESTAMP

CHAR 14

Date/Time of Processing

Color coding: COL\_POSITIVE (green) = success, COL\_NEGATIVE (red) = error, COL\_TOTAL (yellow) = info/warning.

### 4.5 Totaling

Summary row: Total Revisions Processed | Total Revisions Closed | Total Networks TECO'd | Total WBS TECO'd | Total Errors | Total Emails Sent.

### 4.6 Sorting

Default: REVNR ascending, then STEP order (Revision → Network → WBS → Email).

### 4.7 Page Break

Not applicable — ALV grid handles pagination automatically.

### 4.8 Error Handling

1\. **BAPI errors** (RETURN-TYPE = 'E' or 'A'): Logged with full BAPIRETURN1-MESSAGE text (CHAR 220). BAPI\_TRANSACTION\_ROLLBACK called. Processing continues to next item.  
2\. **Unexpected exceptions:** TRY/CATCH cx\_root. Exception text logged. Processing continues.  
3\. **Email exceptions:** All 7 exceptions from SO\_NEW\_DOCUMENT\_ATT\_SEND\_API1 caught and logged as warnings. Does not affect status changes.  
4\. **No data:** ZPM\_REVCOMP 009 + EXIT.  
5\. **Independent chains:** Error on one revision does not roll back or affect others.

### 4.9 Report Header & Footer

Standard Project Polaris header and footer. No deviation required.

## 5 Assumptions in Technical Design

1\. The custom BAPI /AXONEBX/GET\_REV\_CLOSE is deployed and active on the target S/4HANA system with parameters I\_REVNR (TYPE REVNI, CHAR 8) and I\_WERKS (TYPE IWERK, CHAR 4).  
2\. T325R contains the revision-to-network assignment (REVNR → AUFNR mapping). Table returned empty fields in the connected ECC system — to be verified on the target S/4HANA system.  
3\. DIWPS\_RV\_CR verified: contains WPID (TYPE REVNI, CHAR 8), NOTIFID (TYPE QMNUM, CHAR 12), ORDER\_NO (TYPE AUFNR, CHAR 12).  
4\. JEST status values confirmed via TJ02T: I0002=REL, I0045=TECO, I0046=CLSD, I0072=NOCO.  
5\. SO15 distribution list for EC FI is maintained and current.  
6\. MO-0595 email template is available and defines subject/body format.  
7\. All service orders are closed within P\_DAYS (default 60) from revision end date.  
8\. Batch job user has sufficient authorization for all BAPI calls and table reads.  
9\. BAPI\_BUS2002\_SET\_STATUS: NUMBER typed NW\_AUFNR (CHAR 12), SET\_SYSTEM\_STATUS (CHAR 4). Verified.  
10\. BAPI\_BUS2054\_SET\_STATUS: I\_WBS\_SYSTEM\_STATUS table with WBS\_ELEMENT (TYPE PS\_POSID, CHAR 24) and SET\_SYSTEM\_STATUS (CHAR 4). Verified.

## 6 Open Issues in Technical Design

#

Issue

Status

Owner

1

Confirm /AXONEBX/GET\_REV\_CLOSE exact interface and return structure — custom/partner BAPI not available in connected ECC system for live verification

OPEN

Functional / Vendor

2

Confirm T325R table structure on target S/4HANA — returned empty fields in ECC test system (may be S/4HANA PM-specific)

OPEN

Technical

3

Clarify FS reference to DIWPA\_RV\_CR vs DIWPS\_RV\_CR — DIWPS\_RV\_CR verified (WPID, NOTIFID, ORDER\_NO); DIWPA\_RV\_CR returned no fields in DD03L

OPEN

Functional

4

Confirm Fiori Tile development is a separate TS deliverable

OPEN

Project Lead

5

Confirm the SO15 distribution list name for EC FI email recipients

OPEN

Business

## 7 Unit Test Results

Scenario #

Input / Selection Criteria

Expected Result

Pass/Fail

1

Revision with linked Notifications and Service Orders not yet completed

System ignores revision for auto-close; logs info message per open item

Pending

2

Revision with all Notifications NOCO and all Orders CLSD

System closes revision (CLSD) with success message

Pending

3

Revision with network linked to multiple revisions — all other revisions CLSD

System TECOs the network with success message

Pending

4

Network linked to multiple revisions — one revision NOT CLSD

System skips network TECO; logs info about open revision

Pending

5

WBS linked to multiple networks — all networks TECO

System TECOs the WBS with success message

Pending

6

WBS linked to multiple networks — one network NOT TECO

System skips WBS TECO; logs info about open network

Pending

7

Revision without any linked network

System closes revision and logs "Revision XXXXX closed without network"

Pending

8

WBS TECO for planning plant ECE2

Email sent to EC FI distribution list (SO15) using MO-0595 template

Pending

9

WBS TECO for plant other than ECE2

No email sent; only log message for WBS TECO

Pending

10

BAPI returns error during revision close

Error message logged; revision remains unchanged; processing continues to next revision

Pending

11

No revisions match selection criteria

Program ends with info message ZPM\_REVCOMP 009

Pending

12

Background execution (SM36/SM37)

All messages stored in spool; log available for review via SM37

Pending

## 8 Related Documentation

1\. **Functional Specification:** FSD\_EN-MO-0613 Auto Complete Revision, Network and WBS (v0.1, Muralikrishna K, 10 Sep 2026)  
2\. **Email Template:** MO-0595 (WBS TECO email notification to EC FI)  
3\. **Project:** Polaris Lodestar Phase 2A  
4\. **Verified BAPIs:** BAPI\_BUS2002\_SET\_STATUS (FG: CNIF\_STATUS\_2002), BAPI\_BUS2054\_SET\_STATUS (FG: CNIF\_STATUS\_2054), BAPI\_TRANSACTION\_COMMIT (FG: BAPT), SO\_NEW\_DOCUMENT\_ATT\_SEND\_API1 (FG: SOI1)  
5\. **Verified Status Codes** (TJ02T): I0002=REL (Released), I0045=TECO (Technically completed), I0046=CLSD (Closed), I0072=NOCO (Notification completed)

**C16 — AI for SAP operational efficiency**  |  Document version 1.0  |  13 October 2026

C16.ai

**Disclaimer & Important Notices**

**1.  AI-Generated Content.** This document was generated by **C16**, an automated AI-powered SAP analysis platform operated by **PEOL Technologies Private Limited**, based on data sourced from the connected SAP system at the time of generation. The contents have not been individually reviewed by a human consultant prior to publication.

**2.  Validation Required; Customer Responsibility.** All findings, scores, classifications, recommendations, timelines, and roadmap items are **advisory in nature** and must be reviewed and validated by qualified SAP functional and technical subject-matter experts before any action is taken. Migration, remediation, configuration, and implementation decisions remain the **sole responsibility of the customer**.

**3.  Demonstration System Notice.** Where this document was produced from an **IDES, sandbox, training, or demonstration** SAP system, the configurations, data volumes, transactions, and custom objects analysed do not represent any real production customer environment. Such content is provided for **illustration and template purposes only**; actual findings, scores, and recommendations in a customer engagement will vary materially.

**4.  No Warranty; No Liability.** This document is provided **“as is.”** PEOL Technologies Private Limited makes no representation or warranty of any kind, express or implied, including (without limitation) any warranty as to accuracy, completeness, merchantability, non-infringement, or fitness for a particular purpose. In no event shall PEOL Technologies Private Limited be liable for any direct, indirect, incidental, consequential, or special damages arising from the use of, or reliance upon, this document.

**5.  SAP Trademarks & Partnership.** _SAP_, _SAP S/4HANA_, _SAP ECC_, _SAP ERP_, _ABAP_, _SAP HANA_, _SAP Fiori_, _BAPI_, _BAdI_, _Business Partner_, and other SAP product names referenced in this document are trademarks or registered trademarks of **SAP SE** in Germany and other countries. **PEOL Technologies Private Limited is an SAP Partner; C16 is PEOL’s own product, not an SAP product.** References to SAP products, transactions, tables, notes, and methodologies are made solely for analytical and educational purposes.

**6.  Confidentiality.** Where this document contains customer-specific information, it is **confidential** and intended solely for the named recipient. It may not be reproduced, distributed, or disclosed to any third party without the prior written consent of PEOL Technologies Private Limited.

**7.  Copyright.** © 2026 PEOL Technologies Private Limited. All rights reserved. “C16”, “C16.ai”, and the C16 logo are trademarks of PEOL Technologies Private Limited.