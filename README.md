# R
![Marketplace Version](http://vsmarketplacebadge.apphb.com/version/ikuyadeu.r.svg "Current Version")
![Market Place Installs](http://vsmarketplacebadge.apphb.com/installs/ikuyadeu.r.svg "Number of Installs")

R languagesupport for VS Code.
Require [R](https://www.r-project.org/)

## Features
Use `F1` key and `R:` command
* Run Source and Run Selected
![use Run .R](images/feature.png)

* R Integrated Terminal
![Create R terminal](images/terminal.png)

* Support [lintr](https://github.com/jimhester/lintr)
![lintr](images/lintr.png)
* Create .gitignore based [R.gitignore](https://github.com/github/gitignore/raw/master/R.gitignore)
* Support R Documentation and R Markdown
* Snippets

## Requirements
* R base in https://www.r-project.org/
* lintr package

## Extension Settings
This extension contributes the following settings:

* `r.rterm.windows`: set to R term's path for Windows
* `r.rterm.mac`: set to R term's path for Mac OS X
* `r.rterm.linux`: set to R term's path for Linux
* `r.lintr.linters`: list of [linter functions](https://github.com/jimhester/lintr#available-linters)
* `r.lintr.cach`: toggle caching of lint results

## TODO
* Intellisense
* Output Plot
* Debug
* Language Server

This extension based on the 
* [r.tmbundle](https://github.com/textmate/r.tmbundle)
* [markdown-redcarpet.tmbandle](https://github.com/streeter/markdown-redcarpet.tmbundle)
* [Markdown extension in VS Code](https://github.com/Microsoft/vscode/blob/master/extensions/markdown/snippets/markdown.json)
* [R.gitignore](https://github.com/github/gitignore/raw/master/R.gitignore)


The R logo is © 2016 The R Foundation