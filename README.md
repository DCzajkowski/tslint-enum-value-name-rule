# 🚧 This rule was abandoned due to [TSLint being discontinued](https://medium.com/palantir/tslint-in-2019-1a144c2317a9). It works and can be used, it's just not recommended. 🚧

# tslint-enum-value-name-rule

It is a TSLint rule to enforce PascalCasing in enum names.

## Installation

```bash
npm i -D tslint-enum-value-name-rule
```

In `tslint.json` config

```json
{
  "extends": [
    "tslint-enum-value-name-rule"
  ],
  "rules": {
    "enum-value-name": true
  }
}
```
