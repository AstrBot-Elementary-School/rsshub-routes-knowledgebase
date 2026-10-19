# 视觉联盟 - 发现

## Coverage
`index-only`

## Route
- Namespace: `cnu.cc`
- Namespace Name: `视觉联盟`
- Route Path: `/cnu.cc/discovery/:type?/:category?`
- Route Name: `发现`
- Example: `/cnu.cc/discovery/hot`
- URL: `cnu.cc`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `hoilc`
- Source Location: `discovery.ts`
- Source Module: `_None_`

## Description
| 热门 | 推荐      | 最新   |
| ---- | --------- | ------ |
| hot  | recommend | recent |

## Parameters
- `type`: 板块类型, 默认为`热门`, 具体参见下表
- `category`: 图片类别, 默认为`0`代表全部, 可参见[这里](http://www.cnu.cc/discoveryPage/hot-0)


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "| 热门 | 推荐      | 最新   |\n| ---- | --------- | ------ |\n| hot  | recommend | recent |",
  "example": "/cnu.cc/discovery/hot",
  "heat": 1,
  "location": "discovery.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "发现",
  "parameters": {
    "category": "图片类别, 默认为`0`代表全部, 可参见[这里](http://www.cnu.cc/discoveryPage/hot-0)",
    "type": "板块类型, 默认为`热门`, 具体参见下表"
  },
  "path": "/discovery/:type?/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "CNU视觉联盟 - 热门 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1259811719316635648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cnu.cc/discoveryPage/hot-0",
      "title": "CNU视觉联盟 - 热门",
      "type": "feed",
      "url": "rsshub://cnu.cc/discovery"
    }
  ]
}
```
