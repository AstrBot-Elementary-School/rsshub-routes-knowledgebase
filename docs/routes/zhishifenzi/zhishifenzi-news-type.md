# ZhiShiFenZi - News

## Coverage
`index-only`

## Route
- Namespace: `zhishifenzi`
- Namespace Name: `ZhiShiFenZi`
- Route Path: `/zhishifenzi/news/:type?`
- Route Name: `News`
- Example: `/zhishifenzi/news/ai`
- URL: `zhishifenzi.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `y9c`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| `:type`   | type name |
| --------- | --------- |
| biology   | Biology   |
| medicine  | Medicine  |
| ai        | AI        |
| physics   | physics   |
| chymistry | Chymistry |
| astronomy | Astronomy |
| others    | Others    |

> leave it blank（`/zhishifenzi/news`）to get all

## Parameters
- `type`: type，eg. ai


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
  "description": "| `:type`   | type name |\n| --------- | --------- |\n| biology   | Biology   |\n| medicine  | Medicine  |\n| ai        | AI        |\n| physics   | physics   |\n| chymistry | Chymistry |\n| astronomy | Astronomy |\n| others    | Others    |\n\n> leave it blank（`/zhishifenzi/news`）to get all",
  "example": "/zhishifenzi/news/ai",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "y9c"
  ],
  "name": "News",
  "parameters": {
    "type": "type，eg. ai"
  },
  "path": "/news/:type?",
  "topFeeds": []
}
```
