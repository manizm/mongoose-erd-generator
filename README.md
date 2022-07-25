Mongoose-erd-generator
===============================

A tool that extracts  information from mongoose schemas and turns them into a ERD diagram.
Forked from: https://github.com/jodevsa/mongoose-erd-generator

**TODO** update readme according to changes

**Main difference is that it relies upon mongoose connected instance to get schema**


[![Build Status](https://travis-ci.org/jodevsa/node-bitview.svg?branch=master)](https://travis-ci.org/jodevsa/node-bitview)
[![bitHound Dependencies](https://www.bithound.io/github/jodevsa/node-bitview/badges/dependencies.svg)](https://www.bithound.io/github/jodevsa/node-bitview/master/dependencies/npm)
![bitHound Overall Score](https://www.bithound.io/github/jodevsa/node-bitview/badges/score.svg)
![issues](https://img.shields.io/github/issues/jodevsa/node-bitview.svg)
![stars](https://img.shields.io/github/stars/jodevsa/node-bitview.svg)
![license](https://img.shields.io/github/license/jodevsa/node-bitview.svg)

![ERD Diagram generated from this tool](https://i.imgur.com/NFE4HMz.png)
Installation
-----

`npm install mongoose-erd-generator -g`

Running the script
-----
Usage: mongoose-erd-generator [options]

##### Options:

    -V, --version                                                 output the version number
    -p, --path <path>                                             set models path wanted to generate an ERD from.
    -o, --output <path>                                           set output path
    -i, --ignore-index                                            ignore any files called index.js
    -f, --format [svg,dot,xdot,plain,plan-ext,ps,ps2,json,json0]  
    -c, --color <color>                                           
    -h, --help                                 

example
-------        
##### Global install:
`npm install mongoose-erd-generator -g`

##### Run CMD:
###### MAC / LINUX
`mongoose-erd-generator -p ./path_to_models_folder/ -f svg -o ./erd.svg`

###### WINDOWS
`mongoose-erd-generator -p .\path_to_models_folder\ -f svg -o .\erd.svg`
