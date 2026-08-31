# 国家留学网 - 通知

## Coverage
`index-only`

## Route
- Namespace: `csc`
- Namespace Name: `国家留学网`
- Route Path: `/csc/notice/:type?`
- Route Name: `通知`
- Example: `/csc/notice/lxtz`
- URL: `www.csc.edu.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `Derekmini, markmingjie`
- Source Location: `notice.ts`
- Source Module: `_None_`

## Description
| 遴选通知 | 综合项目专栏 | 常见问题解答 | 录取公告 | 新闻资讯 | 新闻公告 |
| -------- | ------------ | ------------ | -------- | -------- | -------- |
| lxtz     | xmzl         | wtjd         | lqgg     | xwzx     | xwgg     |

## Parameters
- `type`: {"default": "lxtz", "description": "分类", "options": [{"label": "遴选通知", "value": "lxtz"}, {"label": "综合项目专栏", "value": "xmzl"}, {"label": "常见问题解答", "value": "wtjd"}, {"label": "录取公告", "value": "lqgg"}, {"label": "新闻资讯", "value": "xwzx"}, {"label": "新闻公告", "value": "xwgg"}]}


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| 遴选通知 | 综合项目专栏 | 常见问题解答 | 录取公告 | 新闻资讯 | 新闻公告 |\n| -------- | ------------ | ------------ | -------- | -------- | -------- |\n| lxtz     | xmzl         | wtjd         | lqgg     | xwzx     | xwgg     |",
  "example": "/csc/notice/lxtz",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "notice.ts",
  "maintainers": [
    "Derekmini",
    "markmingjie"
  ],
  "name": "通知",
  "parameters": {
    "type": {
      "default": "lxtz",
      "description": "分类",
      "options": [
        {
          "label": "遴选通知",
          "value": "lxtz"
        },
        {
          "label": "综合项目专栏",
          "value": "xmzl"
        },
        {
          "label": "常见问题解答",
          "value": "wtjd"
        },
        {
          "label": "录取公告",
          "value": "lqgg"
        },
        {
          "label": "新闻资讯",
          "value": "xwzx"
        },
        {
          "label": "新闻公告",
          "value": "xwgg"
        }
      ]
    }
  },
  "path": "/notice/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.csc.edu.cn"
}
```
