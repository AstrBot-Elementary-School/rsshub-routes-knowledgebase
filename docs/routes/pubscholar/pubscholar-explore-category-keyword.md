# PubScholar 公益学术平台 - Explore

## Coverage
`index-only`

## Route
- Namespace: `pubscholar`
- Namespace Name: `PubScholar 公益学术平台`
- Route Path: `/pubscholar/explore/:category?/:keyword?`
- Route Name: `Explore`
- Example: `/pubscholar/explore`
- URL: `pubscholar.cn`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `explore.ts`
- Source Module: `_None_`

## Description
| Articles / 论文 | Patents / 专利 | Reports / 领域快报 | Information / 动态快讯 | Datasets / 科学数据 | Books / 图书 |
| --------------- | -------------- | ------------------ | ---------------------- | ------------------- | ------------ |
| articles        | patents        | bulletins          | reports                | sciencedata         | books        |

## Parameters
- `category`: Category, see the table below, `articles` by default
- `keyword`: Search Keyword


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "| Articles / 论文 | Patents / 专利 | Reports / 领域快报 | Information / 动态快讯 | Datasets / 科学数据 | Books / 图书 |\n| --------------- | -------------- | ------------------ | ---------------------- | ------------------- | ------------ |\n| articles        | patents        | bulletins          | reports                | sciencedata         | books        |",
  "example": "/pubscholar/explore",
  "heat": 0,
  "location": "explore.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Explore",
  "parameters": {
    "category": "Category, see the table below, `articles` by default",
    "keyword": "Search Keyword"
  },
  "path": "/explore/:category?/:keyword?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
