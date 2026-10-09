# 得到 - 首页

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/dedao/list/:category?`
- Route Name: `首页`
- Example: `/dedao/list/年度日更`
- URL: `igetget.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `list.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类名，默认为年度日更


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
  - `igetget.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/dedao/list/年度日更",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 116,
  "location": "list.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "首页",
  "parameters": {
    "category": "分类名，默认为年度日更"
  },
  "path": "/list/:category?",
  "radar": [
    {
      "source": [
        "igetget.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "得到 - 年度日更 - Powered by RSSHub",
      "errorAt": "2026-10-08T13:15:57.568Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "59505334359543853",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.igetget.com/list/%E5%B9%B4%E5%BA%A6%E6%97%A5%E6%9B%B4/Z01i89TzfXcv",
      "title": "得到 - 年度日更",
      "type": "feed",
      "url": "rsshub://dedao/list/%E5%B9%B4%E5%BA%A6%E6%97%A5%E6%9B%B4"
    },
    {
      "description": "得到 - 年度日更 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "115579636743659520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.igetget.com/list/%E5%B9%B4%E5%BA%A6%E6%97%A5%E6%9B%B4/Z01i89TzfXcv",
      "title": "得到 - 年度日更",
      "type": "feed",
      "url": "rsshub://dedao/list"
    }
  ],
  "url": "igetget.com/"
}
```
