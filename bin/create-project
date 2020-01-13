#!/usr/bin/env node

// require esm module that is an ECMAScript module loader, allows us to import other files
require = require('esm')(module /*, options*/)

// require our cli.js file and call cli function exposed with process.argv (an array of all args passed to the script from the command line)
require('../src/cli').cli(process.argv)
