# 微博 - 新鲜事

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/fresh/:id`
- Route Name: `新鲜事`
- Example: `/weibo/fresh/7574046780235777_1`
- URL: `weibo.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `fresh.ts`
- Source Module: `_None_`

## Description
订阅源页面首屏的精选内容或全部微博。保留新鲜事本身的栏目与顺序；正文为源页面提供的摘要及配图。

## Parameters
- `id`: 新鲜事页面 URL 中的标识，例如 7574046780235777_1 或 60e8c3bf5b9c0e70_0。保留末尾的栏目类型。


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true
- `requireConfig`: [{"description": "仅登录可见的新鲜事需要配置。", "name": "WEIBO_COOKIES", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `weibo.com/a/hot/:id.html`
- `target`: `/fresh/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "订阅源页面首屏的精选内容或全部微博。保留新鲜事本身的栏目与顺序；正文为源页面提供的摘要及配图。",
  "example": "/weibo/fresh/7574046780235777_1",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "仅登录可见的新鲜事需要配置。",
        "name": "WEIBO_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "fresh.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "新鲜事",
  "parameters": {
    "id": "新鲜事页面 URL 中的标识，例如 7574046780235777_1 或 60e8c3bf5b9c0e70_0。保留末尾的栏目类型。"
  },
  "path": "/fresh/:id",
  "radar": [
    {
      "source": [
        "weibo.com/a/hot/:id.html"
      ],
      "target": "/fresh/:id"
    }
  ],
  "topFeeds": []
}
```
