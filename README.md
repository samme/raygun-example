Raygun Example
==============

This is documentation generated from [Lodash](https://github.com/lodash/lodash) using the [Raygun](https://github.com/samme/raygun) theme:

```bash
jsdoc node_modules/lodash/lodash.js -c ./jsdoc-conf.json
```

jsdoc-conf.json
---------------

```json
{
  "tags": {
    "allowUnknownTags": true
  },
  "plugins": [
    "plugins/markdown"
  ],
  "templates": {
    "cleverLinks": false,
    "monospaceLinks": false,
    "default": {
      "outputSourceFiles": false
    }
  },
  "opts": {
    "destination": "docs",
    "readme": "./README.md",
    "template": "../raygun"
  }
}
```