# 湖南农业大学 - 国际交流与合作处、国际教育学院、港澳台事务办公室

## Coverage
`index-only`

## Route
- Namespace: `hunau`
- Namespace Name: `湖南农业大学`
- Route Path: `/hunau/ied/:type?/:category?`
- Route Name: `国际交流与合作处、国际教育学院、港澳台事务办公室`
- Example: `/hunau/ied`
- URL: `ied.hunau.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `lcandy2`
- Source Location: `ied.ts`
- Source Module: `_None_`

## Description
| 分类     | 公告通知 | 新闻快讯 | 其他分类... |
| -------- | -------- | -------- | ----------- |
| type     | xwzx     | xwzx     | 对应 URL    |
| category | ggtz     | xwkx     | 对应 URL    |

## Parameters
- `type`: 页面归属，默认为 `xwzx`
- `category`: 页面分类，默认为 `ggtz`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ied.hunau.edu.cn/`
- `target`: `/ied`
### Rule 2
- `source`:
  - `ied.hunau.edu.cn/xwzx/ggtz`
  - `ied.hunau.edu.cn/xwzx/ggtz/index.html`
- `target`: `/ied/xwzx/ggtz`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分类     | 公告通知 | 新闻快讯 | 其他分类... |\n| -------- | -------- | -------- | ----------- |\n| type     | xwzx     | xwzx     | 对应 URL    |\n| category | ggtz     | xwkx     | 对应 URL    |",
  "example": "/hunau/ied",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "ied.ts",
  "maintainers": [
    "lcandy2"
  ],
  "name": "国际交流与合作处、国际教育学院、港澳台事务办公室",
  "parameters": {
    "category": "页面分类，默认为 `ggtz`",
    "type": "页面归属，默认为 `xwzx`"
  },
  "path": "/ied/:type?/:category?",
  "radar": [
    {
      "source": [
        "ied.hunau.edu.cn/"
      ],
      "target": "/ied"
    },
    {
      "source": [
        "ied.hunau.edu.cn/xwzx/ggtz",
        "ied.hunau.edu.cn/xwzx/ggtz/index.html"
      ],
      "target": "/ied/xwzx/ggtz"
    }
  ],
  "topFeeds": [],
  "url": "ied.hunau.edu.cn/"
}
```
