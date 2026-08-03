# 直播吧 - 录像

## Coverage
`index-only`

## Route
- Namespace: `zhibo8`
- Namespace Name: `直播吧`
- Route Path: `/zhibo8/luxiang/:category?`
- Route Name: `录像`
- Example: `/zhibo8/luxiang/nba`
- URL: `zhibo8.cc`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `luxiang.ts`
- Source Module: `_None_`

## Description
| NBA | 足球  |
| --- | ----- |
| nba | zuqiu |

## Parameters
- `category`: 分类，见下表，默认为 `nba`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `zhibo8.cc/:category/luxiang.htm`
- `target`: `/luxiang/:category`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| NBA | 足球  |\n| --- | ----- |\n| nba | zuqiu |",
  "example": "/zhibo8/luxiang/nba",
  "heat": 4,
  "location": "luxiang.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "录像",
  "parameters": {
    "category": "分类，见下表，默认为 `nba`"
  },
  "path": "/luxiang/:category?",
  "radar": [
    {
      "source": [
        "zhibo8.cc/:category/luxiang.htm"
      ],
      "target": "/luxiang/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "NBA篮球录像-直播吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68973917074888704",
      "image": "https://www.zhibo8.cc/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.zhibo8.cc/nba/luxiang.htm",
      "title": "NBA篮球录像-直播吧",
      "type": "feed",
      "url": "rsshub://zhibo8/luxiang/nba"
    }
  ]
}
```
