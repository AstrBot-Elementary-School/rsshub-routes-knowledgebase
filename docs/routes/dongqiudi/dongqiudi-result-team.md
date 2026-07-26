# 懂球帝 - 足球赛果

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/dongqiudi/result/:team`
- Route Name: `足球赛果`
- Example: `/dongqiudi/result/50001755`
- URL: `m.dongqiudi.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `HenryQW`
- Source Location: `result.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `team`: 球队 id, 可在[懂球帝数据](https://www.dongqiudi.com/data)中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dongqiudi.com/team/*team`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/dongqiudi/result/50001755",
  "heat": 54,
  "location": "result.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "足球赛果",
  "parameters": {
    "team": "球队 id, 可在[懂球帝数据](https://www.dongqiudi.com/data)中找到"
  },
  "path": "/result/:team",
  "radar": [
    {
      "source": [
        "www.dongqiudi.com/team/*team"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "皇家马德里 比赛结果 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63132054928183296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dongqiudi.com/team/50001755.html",
      "title": "皇家马德里 比赛结果",
      "type": "feed",
      "url": "rsshub://dongqiudi/result/50001755"
    },
    {
      "description": "曼联 比赛结果 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86597494578069504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dongqiudi.com/team/50000515.html",
      "title": "曼联 比赛结果",
      "type": "feed",
      "url": "rsshub://dongqiudi/result/50000515"
    }
  ]
}
```
