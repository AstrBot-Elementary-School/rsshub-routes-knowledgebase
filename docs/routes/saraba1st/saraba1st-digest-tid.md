# Saraba1st - 论坛摘要

## Coverage
`index-only`

## Route
- Namespace: `saraba1st`
- Namespace Name: `Saraba1st`
- Route Path: `/saraba1st/digest/:tid`
- Route Name: `论坛摘要`
- Example: `/saraba1st/digest/forum-6-1`
- URL: `stage1st.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `shinemoon`
- Source Location: `digest.tsx`
- Source Module: `_None_`

## Description
版面网址如果为 `https://stage1st.com/2b/forum-6-1.html` 那么论坛 id 就是 `forum-6-1`。

## Parameters
- `tid`: 论坛 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "版面网址如果为 `https://stage1st.com/2b/forum-6-1.html` 那么论坛 id 就是 `forum-6-1`。",
  "example": "/saraba1st/digest/forum-6-1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 41,
  "location": "digest.tsx",
  "maintainers": [
    "shinemoon"
  ],
  "name": "论坛摘要",
  "parameters": {
    "tid": "论坛 id"
  },
  "path": "/digest/:tid",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Stage1 论坛 - ＰＣ数码 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57334301287197696",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://stage1st.com/2b/forum-51-1.html",
      "title": "Stage1 论坛 - ＰＣ数码",
      "type": "feed",
      "url": "rsshub://saraba1st/digest/forum-51-1"
    },
    {
      "description": "Stage1 论坛 - 卓明谷 - Powered by RSSHub",
      "errorAt": "2025-03-25T11:54:12.181Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "57332597069544448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.saraba1st.com/2b/forum-75-1.html",
      "title": "Stage1 论坛 - 卓明谷",
      "type": "feed",
      "url": "rsshub://saraba1st/digest/forum-75-1"
    }
  ]
}
```
