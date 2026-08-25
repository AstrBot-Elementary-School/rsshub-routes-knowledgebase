# ZhiShiFenZi - innovation

## Coverage
`index-only`

## Route
- Namespace: `zhishifenzi`
- Namespace Name: `ZhiShiFenZi`
- Route Path: `/zhishifenzi/innovation/:type?`
- Route Name: `innovation`
- Example: `/zhishifenzi/innovation/company`
- URL: `zhishifenzi.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `y9c`
- Source Location: `innovation.ts`
- Source Module: `_None_`

## Description
| `:type`       | type name     |
| ------------- | ------------- |
| ~~multiple~~  | ~~Multiple~~  |
| company       | Company       |
| product       | Product       |
| technology    | Technology    |
| ~~character~~ | ~~Character~~ |
| policy        | Policy        |

> leave it blank（`/zhishifenzi/innovation`）to get all

## Parameters
- `type`: type，eg. company


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| `:type`       | type name     |\n| ------------- | ------------- |\n| ~~multiple~~  | ~~Multiple~~  |\n| company       | Company       |\n| product       | Product       |\n| technology    | Technology    |\n| ~~character~~ | ~~Character~~ |\n| policy        | Policy        |\n\n> leave it blank（`/zhishifenzi/innovation`）to get all",
  "example": "/zhishifenzi/innovation/company",
  "heat": 0,
  "location": "innovation.ts",
  "maintainers": [
    "y9c"
  ],
  "name": "innovation",
  "parameters": {
    "type": "type，eg. company"
  },
  "path": "/innovation/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
