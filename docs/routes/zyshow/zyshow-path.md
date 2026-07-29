# 综艺秀 - 综艺

## Coverage
`index-only`

## Route
- Namespace: `zyshow`
- Namespace Name: `综艺秀`
- Route Path: `/zyshow/:path{.+}?`
- Route Name: `综艺`
- Example: `/zyshow/chongchongchong`
- URL: `zyshow.net`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `pharaoh2012, nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
地区，见下表，默认为空，即台湾

| 台湾 | 韩国 | 大陆 |
| ---- | ---- | ---- |
|      | kr   | dl   |

## Parameters
- `path`: 综艺 id，综艺详情对应页 URL 中找到


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "地区，见下表，默认为空，即台湾\n\n| 台湾 | 韩国 | 大陆 |\n| ---- | ---- | ---- |\n|      | kr   | dl   |",
  "example": "/zyshow/chongchongchong",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "pharaoh2012",
    "nczitzk"
  ],
  "name": "综艺",
  "parameters": {
    "path": "综艺 id，综艺详情对应页 URL 中找到"
  },
  "path": "/:path{.+}?",
  "topFeeds": []
}
```
