# 太平洋科技 - 科技新闻

## Coverage
`index-only`

## Route
- Namespace: `pconline`
- Namespace Name: `太平洋科技`
- Route Path: `/pconline/focus/:category?`
- Route Name: `科技新闻`
- Example: `/pconline/focus`
- URL: `pconline.com.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `CH563`
- Source Location: `focus.ts`
- Source Module: `_None_`

## Description
::: tip

| 全部 | 科技 | 财经    | 生活 | 公司    | 人物      |
| ---- | ---- | ------- | ---- | ------- | --------- |
| all  | tech | finance | life | company | character |

:::

## Parameters
- `category`: {"default": "all", "description": "科技新闻的类别，获取最新的一页，分别：all, tech, finance, life, company, character"}


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
  - `pconline.com.cn/focus/`
  - `pconline.com.cn/`
- `target`: `/focus`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n\n| 全部 | 科技 | 财经    | 生活 | 公司    | 人物      |\n| ---- | ---- | ------- | ---- | ------- | --------- |\n| all  | tech | finance | life | company | character |\n\n:::",
  "example": "/pconline/focus",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 313,
  "location": "focus.ts",
  "maintainers": [
    "CH563"
  ],
  "name": "科技新闻",
  "parameters": {
    "category": {
      "default": "all",
      "description": "科技新闻的类别，获取最新的一页，分别：all, tech, finance, life, company, character"
    }
  },
  "path": "/focus/:category?",
  "radar": [
    {
      "source": [
        "pconline.com.cn/focus/",
        "pconline.com.cn/"
      ],
      "target": "/focus"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "太平洋科技-全部 - Powered by RSSHub",
      "errorAt": "2026-08-09T23:57:59.547Z",
      "errorMessage": "[GET] \"https:\": <no response> Failed to parse URL from https: (Invalid URL)\n[GET] \"https:\": <no response> Failed to parse URL from https:\nFailed to fetch\n",
      "id": "84175249418008576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pconline.com.cn/3g/other/focus/index.html",
      "title": "太平洋科技-全部",
      "type": "feed",
      "url": "rsshub://pconline/focus/all"
    },
    {
      "description": "太平洋科技-全部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59139256789618688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pconline.com.cn/3g/other/focus/index.html",
      "title": "太平洋科技-全部",
      "type": "feed",
      "url": "rsshub://pconline/focus"
    }
  ]
}
```
