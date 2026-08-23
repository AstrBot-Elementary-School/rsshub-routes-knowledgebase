# 扬州大学 - 官网消息

## Coverage
`index-only`

## Route
- Namespace: `yzu`
- Namespace Name: `扬州大学`
- Route Path: `/yzu/home/:type`
- Route Name: `官网消息`
- Example: `/yzu/home/xxyw`
- URL: `www.yzu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LogicJake`
- Source Location: `home.ts`
- Source Module: `_None_`

## Description
| 学校要闻 | 校园新闻 | 信息公告 | 学术活动 | 媒体扬大 |
| -------- | -------- | -------- | -------- | -------- |
| xxyw     | xyxw     | xxgg     | xshd     | mtyd     |

## Parameters
- `type`: 分类名


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.yzu.edu.cn/dtxx/:type.htm`
- `target`: `/home/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学校要闻 | 校园新闻 | 信息公告 | 学术活动 | 媒体扬大 |\n| -------- | -------- | -------- | -------- | -------- |\n| xxyw     | xyxw     | xxgg     | xshd     | mtyd     |",
  "example": "/yzu/home/xxyw",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "home.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "官网消息",
  "parameters": {
    "type": "分类名"
  },
  "path": "/home/:type",
  "radar": [
    {
      "source": [
        "www.yzu.edu.cn/dtxx/:type.htm"
      ],
      "target": "/home/:type"
    }
  ],
  "topFeeds": []
}
```
