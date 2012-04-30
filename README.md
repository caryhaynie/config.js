# config.js -- node.js configuration for busy people

## install

`$ git clone https://github.com/caryhaynie/config.js.git`

`$ cd config.js; sudo npm link`

## usage

`$ npm link config.js`


## info
config.js is a simple library that allows node.js developers to store
configuration data in a JSON file that sits next to the script where they
need it. To load your config, simply call ` require("config.js").getConfig() `
and read the resulting object. If config.js can't find a config file, it will
simply return an empty object. If it can't parse the JSON data, it will throw
a Syntax Error.
