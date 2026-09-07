# Saraba1st - 帖子

## Coverage
`index-only`

## Route
- Namespace: `saraba1st`
- Namespace Name: `Saraba1st`
- Route Path: `/saraba1st/thread/:tid`
- Route Name: `帖子`
- Example: `/saraba1st/thread/751272`
- URL: `stage1st.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `zengxs`
- Source Location: `thread.ts`
- Source Module: `_None_`

## Description
帖子网址如果为 `https://stage1st.com/2b/thread-751272-1-1.html` 那么帖子 id 就是 `751272`。

## Parameters
- `tid`: 帖子 id


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
  "description": "帖子网址如果为 `https://stage1st.com/2b/thread-751272-1-1.html` 那么帖子 id 就是 `751272`。",
  "example": "/saraba1st/thread/751272",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "thread.ts",
  "maintainers": [
    "zengxs"
  ],
  "name": "帖子",
  "parameters": {
    "tid": "帖子 id"
  },
  "path": "/thread/:tid",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
