# Flexdashboard test

## Project description

Use RStudio and RMarkdown to create a flexdashboard `.html` document and deploy it as a website using GitHub pages. 

This is a basic flexdashboard developed to test a few formatting features such as:
    + flexdashboard themes
    + multiple pages
    + drop-down menus
    + interactive plots using Plotly
    + page sectioning 
    + LaTex style formulas

## Link to project output

https://gconway012.github.io/Flexdashboard_test/

## References 

1. Article/web post - *Deploying flexdashboard on GitHub Pages*, by Rami Krispin, dated Sep 4, 2020 at https://ramikrispin.github.io/2020/09/deploying-flexdashboard-on-github-pages/. Provided concise steps to follow to enable repository to host an .html file on GitHub Pages.

2. Stackoverflow post - *RMarkdown directing output file into a directory*, NicE's answer, dated Mar 9, 2015 at https://stackoverflow.com/questions/28894515/rmarkdown-directing-output-file-into-a-directory. Provided necessary code used to knit document/file to a different directory.

## Software utilized

* Mac OSx Catalina v10.15.7
* R v4.0.2 "Taking Off Again"
* RStudio v1.3.1073

## R Packages utilized

* rmarkdown v2.3
* tidyverse v1.3.0
* plotly v4.9.2.1

## Included files

* `flexdashboard_test.Rmd` - source code
* `/docs/index.html` - resulting .html file after knitting RMarkdown (.Rmd) file