# sparqljs-legacy-type
[![Build Status](https://travis-ci.com/Callidon/sparqljs-legacy-type.svg?branch=main)](https://travis-ci.com/Callidon/sparqljs-legacy-type) [![npm version](https://badge.fury.io/js/sparqljs-legacy-type.svg)](https://badge.fury.io/js/sparqljs-legacy-type)

This module contains TypeScript types definition for the [`SPARQL.js`](https://github.com/RubenVerborgh/SPARQL.js) package in version *2.0.x*.

## Installation

First install the package using npm or yarn
```
# with npm
npm install --save-dev sparqljs-legacy-type

# with yarn
yarn add -D sparqljs-legacy-type
```

Then, adds the following `typeRoots` configuration in your `tsconfig.json` configuration file.
```json
{
  "compilerOptions": {
      "typeRoots": [
        "./node_modules/sparqljs-legacy-type/"
      ]
    }
}
```
