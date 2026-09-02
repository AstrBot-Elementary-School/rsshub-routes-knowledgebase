# 网易公开课 - 今日关注

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/today/:need_content?`
- Route Name: `今日关注`
- Example: `/163/today`
- URL: `wp.m.163.com/163/html/newsapp/todayFocus/index.html`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `today.ts`
- Source Module: `_None_`

## Description
::: tip
参数 **需要获取全文** 设置为 `true` `yes` `t` `y` 等值后，RSS 会携带该新闻条目的对应全文。
:::

## Parameters
- `need_content`: 需要获取全文，填写 true/yes 表示需要，默认需要


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
  - `wp.m.163.com/163/html/newsapp/todayFocus/index.html`
  - `wp.m.163.com/`
- `target`: `/today`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n参数 **需要获取全文** 设置为 `true` `yes` `t` `y` 等值后，RSS 会携带该新闻条目的对应全文。\n:::",
  "example": "/163/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 202,
  "location": "today.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "今日关注",
  "parameters": {
    "need_content": "需要获取全文，填写 true/yes 表示需要，默认需要"
  },
  "path": "/today/:need_content?",
  "radar": [
    {
      "source": [
        "wp.m.163.com/163/html/newsapp/todayFocus/index.html",
        "wp.m.163.com/"
      ],
      "target": "/today"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "今日关注 - 网易新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56209316185473024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://wp.m.163.com/163/html/newsapp/todayFocus/index.html",
      "title": "今日关注 - 网易新闻",
      "type": "feed",
      "url": "rsshub://163/today"
    }
  ],
  "url": "wp.m.163.com/163/html/newsapp/todayFocus/index.html"
}
```
