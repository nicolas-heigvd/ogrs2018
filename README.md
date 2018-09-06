# ogrs2018
1. Create a `command.sh` file with this content and execute it:    

`#!/bin/bash`  
`mkdir qgis-python-plugin`  
`cd qgis-python-plugin`  
`git init`  
`git pull https://github.com/nicolas-heigvd/ogrs2018.git`  
`pdflatex smapshot_nbc_ogrs2018.tex`  
`bibtex smapshot_nbc_ogrs2018.aux`  
`pdflatex smapshot_nbc_ogrs2018.tex`  
`pdflatex smapshot_nbc_ogrs2018.tex`  
`evince smapshot_nbc_ogrs2018.pdf`  
