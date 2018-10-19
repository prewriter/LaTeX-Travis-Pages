[![Build Status](https://travis-ci.org/prewriter/LaTeX2Website.svg?branch=master)](https://travis-ci.org/prewriter/LaTeX-Travis-Pages)

You have a bunch of .tex files that you want to publish quickly and easily update website to keep up with changes in them. 

Use this project. Using Travis CI it will:
- compile them to PDF
- convert them to HTML, using pdf2htmlEX
- make website with links to PDF and HTML, and titles from `\title{}`

See example output at https://prewriter.github.io/LaTeX-Travis-Pages/

You need to set `GITHUB_TOKEN` to your [personal access token](https://github.com/settings/tokens) in Travis settings in order for deployment to work.
