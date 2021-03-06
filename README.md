
<img src='preview.gif' />

<img src='icon.png' width='150' height='150' align='right' />

# Code Analyser &nbsp; &nbsp; &nbsp; [![Build status](https://travis-ci.org/william-taylor/code-analyser.svg?branch=master)](https://travis-ci.org/william-taylor/analyser) [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

I'm a prolific coder and one thing I like to know is how large my projects are. What I wanted was a simple web application that allows me to upload my source code and for it to tell me how many lines of code are part of that project and other additional information. This is what Coder Analyser is, it is a simple web app that gives me stats on any web project anywhere from any device.

## Overview

Code Analyser is a React based application which uses Webpack for module bundling. I use the HTML5 File API and Fetch API to take files and upload them onto a Node.js server. Once there, the node server does a quick analysis of the given files and returns the results as JSON. Once there this information is then dropped into a styled HTML table. Additionally, the project uses Electron so a desktop version application is available and can be downloaded from the website itself.

## Features

* Drag and drop feature
* Basic file stats
* Language agnostic
* Desktop version via Electron

## Development

* More detailed analysis
* Export table to CSV
* Language Selection
* Make clearing files easier.

## License

Apache 2.0
