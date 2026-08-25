# Fermilab - News

## Coverage
`index-only`

## Route
- Namespace: `fnal`
- Namespace Name: `Fermilab`
- Route Path: `/fnal/news/:category?`
- Route Name: `News`
- Example: `/fnal/news`
- URL: `news.fnal.gov`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| All News | Fermilab features | Press releases | Symmetry features |
| -------- | ----------------- | -------------- | ----------------- |
| allnews  | 269               | 55             | 12580             |

## Parameters
- `category`: Category, see below, All News by default


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| All News | Fermilab features | Press releases | Symmetry features |\n| -------- | ----------------- | -------------- | ----------------- |\n| allnews  | 269               | 55             | 12580             |",
  "example": "/fnal/news",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, see below, All News by default"
  },
  "path": "/news/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
