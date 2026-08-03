# 人民网 - 领导留言板

## Coverage
`index-only`

## Route
- Namespace: `people`
- Namespace Name: `人民网`
- Route Path: `/people/liuyan/:id?/:state?`
- Route Name: `领导留言板`
- Example: `/people/liuyan/539`
- URL: `liuyan.people.com.cn/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `liuyan.ts`
- Source Module: `_None_`

## Description
| 全部 | 待回复 | 办理中 | 已办理 |
| ---- | ------ | ------ | ------ |
| 1    | 2      | 3      | 4      |

## Parameters
- `id`: 编号，可在对应人物页 URL 中找到
- `state`: 状态，见下表，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 全部 | 待回复 | 办理中 | 已办理 |\n| ---- | ------ | ------ | ------ |\n| 1    | 2      | 3      | 4      |",
  "example": "/people/liuyan/539",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "liuyan.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "领导留言板",
  "parameters": {
    "id": "编号，可在对应人物页 URL 中找到",
    "state": "状态，见下表，默认为全部"
  },
  "path": "/liuyan/:id?/:state?",
  "topFeeds": [],
  "url": "liuyan.people.com.cn/"
}
```
