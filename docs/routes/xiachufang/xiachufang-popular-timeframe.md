# 下厨房 - 作品动态

## Coverage
`index-only`

## Route
- Namespace: `xiachufang`
- Namespace Name: `下厨房`
- Route Path: `/xiachufang/popular/:timeframe?`
- Route Name: `作品动态`
- Example: `/xiachufang/popular/hot`
- URL: `xiachufang.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `xyqfer`
- Source Location: `popular.ts`
- Source Module: `_None_`

## Description
| 正在流行 | 24 小时最佳 | 本周最受欢迎 | 新秀菜谱 | 月度最佳   |
| -------- | ----------- | ------------ | -------- | ---------- |
| hot      | pop         | week         | rising   | monthhonor |

## Parameters
- `timeframe`: 默认最新上传


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
  "description": "| 正在流行 | 24 小时最佳 | 本周最受欢迎 | 新秀菜谱 | 月度最佳   |\n| -------- | ----------- | ------------ | -------- | ---------- |\n| hot      | pop         | week         | rising   | monthhonor |",
  "example": "/xiachufang/popular/hot",
  "heat": 1,
  "location": "popular.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "作品动态",
  "parameters": {
    "timeframe": "默认最新上传"
  },
  "path": "/popular/:timeframe?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "下厨房-正在流行 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1259647273659138048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.xiachufang.com/activity/site/?order=hot",
      "title": "下厨房-正在流行",
      "type": "feed",
      "url": "rsshub://xiachufang/popular/hot"
    }
  ]
}
```
