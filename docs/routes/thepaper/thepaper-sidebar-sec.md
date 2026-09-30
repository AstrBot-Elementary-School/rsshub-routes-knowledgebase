# 澎湃新闻 - 侧边栏

## Coverage
`index-only`

## Route
- Namespace: `thepaper`
- Namespace Name: `澎湃新闻`
- Route Path: `/thepaper/sidebar/:sec?`
- Route Name: `侧边栏`
- Example: `/thepaper/sidebar`
- URL: `thepaper.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `bigfei`
- Source Location: `sidebar.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sec`: {"description": "侧边栏 id", "options": [{"label": "澎湃热榜", "value": "hotNews"}, {"label": "澎湃快讯", "value": "financialInformationNews"}, {"label": "早晚报", "value": "morningEveningNews"}, {"label": "要闻精选", "value": "editorHandpicked"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `thepaper.cn/`
- `target`: `/sidebar`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thepaper/sidebar",
  "heat": 115,
  "location": "sidebar.ts",
  "maintainers": [
    "bigfei"
  ],
  "name": "侧边栏",
  "parameters": {
    "sec": {
      "description": "侧边栏 id",
      "options": [
        {
          "label": "澎湃热榜",
          "value": "hotNews"
        },
        {
          "label": "澎湃快讯",
          "value": "financialInformationNews"
        },
        {
          "label": "早晚报",
          "value": "morningEveningNews"
        },
        {
          "label": "要闻精选",
          "value": "editorHandpicked"
        }
      ]
    }
  },
  "path": "/sidebar/:sec?",
  "radar": [
    {
      "source": [
        "thepaper.cn/"
      ],
      "target": "/sidebar"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "澎湃新闻 - 澎湃热榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61246261602249728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.thepaper.cn/",
      "title": "澎湃新闻 - 澎湃热榜",
      "type": "feed",
      "url": "rsshub://thepaper/sidebar"
    },
    {
      "description": "澎湃新闻 - 澎湃热榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56001539986599972",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.thepaper.cn/",
      "title": "澎湃新闻 - 澎湃热榜",
      "type": "feed",
      "url": "rsshub://thepaper/sidebar/hotNews"
    }
  ],
  "url": "thepaper.cn/"
}
```
