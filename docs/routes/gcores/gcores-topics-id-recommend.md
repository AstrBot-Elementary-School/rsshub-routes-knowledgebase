# 机核网 - 机组推荐

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/topics/:id/recommend`
- Route Name: `机组推荐`
- Example: `/gcores/topics/581/recommend`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [我的年度总结](https://www.gcores.com/topics/581)，网址为 `https://www.gcores.com/topics/581`，请截取 `https://www.gcores.com/topics/` 到末尾的部分 `581` 作为 `id` 参数填入，此时目标路由为 [`/gcores/topics/581/recommend`](https://rsshub.app/gcores/topics/581/recommend)。
:::

## Parameters
- `id`: {"description": "小组 ID，可在对应小组页 URL 中找到"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.gcores.com/topics/:id`
- `target`: `/topics/:id/recommend`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [我的年度总结](https://www.gcores.com/topics/581)，网址为 `https://www.gcores.com/topics/581`，请截取 `https://www.gcores.com/topics/` 到末尾的部分 `581` 作为 `id` 参数填入，此时目标路由为 [`/gcores/topics/581/recommend`](https://rsshub.app/gcores/topics/581/recommend)。\n:::",
  "example": "/gcores/topics/581/recommend",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "topics.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "机组推荐",
  "parameters": {
    "id": {
      "description": "小组 ID，可在对应小组页 URL 中找到"
    }
  },
  "path": "/topics/:id/recommend",
  "radar": [
    {
      "source": [
        "www.gcores.com/topics/:id"
      ],
      "target": "/topics/:id/recommend"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "www.gcores.com",
  "view": 1
}
```
