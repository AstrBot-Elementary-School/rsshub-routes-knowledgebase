# 集思录 - 用户

## Coverage
`index-only`

## Route
- Namespace: `jisilu`
- Namespace Name: `集思录`
- Route Path: `/jisilu/people/:id/:type?`
- Route Name: `用户`
- Example: `/jisilu/people/天书`
- URL: `www.jisilu.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `people.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [天书的主题](https://www.jisilu.cn/people/天书)，网址为 `https://www.jisilu.cn/people/天书`，请截取 `https://www.jisilu.cn/people/` 到末尾的部分 `天书` 作为 `id` 参数填入，此时目标路由为 [`/jisilu/people/天书`](https://rsshub.app/jisilu/people/天书)。
:::

::: tip
前往 [用户排名](https://www.jisilu.cn/users/) 查看更多用户。
:::

## Parameters
- `id`: 用户 id，可在对应用户页 URL 中找到
- `type`: 类型，可选值为 `questions` 即 `主题` 或 `answer` 即 `回复`，默认为 `questions` 即 `主题`


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
  - `www.jisilu.cn/people/:id`
- `target`: `/people/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [天书的主题](https://www.jisilu.cn/people/天书)，网址为 `https://www.jisilu.cn/people/天书`，请截取 `https://www.jisilu.cn/people/` 到末尾的部分 `天书` 作为 `id` 参数填入，此时目标路由为 [`/jisilu/people/天书`](https://rsshub.app/jisilu/people/天书)。\n:::\n\n::: tip\n前往 [用户排名](https://www.jisilu.cn/users/) 查看更多用户。\n:::",
  "example": "/jisilu/people/天书",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 12,
  "location": "people.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "用户",
  "parameters": {
    "id": "用户 id，可在对应用户页 URL 中找到",
    "type": "类型，可选值为 `questions` 即 `主题` 或 `answer` 即 `回复`，默认为 `questions` 即 `主题`"
  },
  "path": "/people/:id/:type?",
  "radar": [
    {
      "source": [
        "www.jisilu.cn/people/:id"
      ],
      "target": "/people/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "集思录，一个以数据为本的投资社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "97454904768301056",
      "image": "https://www.jisilu.cn/static/css/jisilu/img/logo_jisilu.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jisilu.cn/people/%E5%A4%A9%E4%B9%A6",
      "title": "天书 的个人主页 - 集思录 - 主题",
      "type": "feed",
      "url": "rsshub://jisilu/people/%E5%A4%A9%E4%B9%A6"
    },
    {
      "description": "集思录，一个以数据为本的投资社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "148336659220684800",
      "image": "https://www.jisilu.cn/static/css/jisilu/img/logo_jisilu.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jisilu.cn/people/%E5%AD%94%E6%9B%BC%E5%AD%90",
      "title": "孔曼子 的个人主页 - 集思录 - 主题",
      "type": "feed",
      "url": "rsshub://jisilu/people/%E5%AD%94%E6%9B%BC%E5%AD%90"
    }
  ],
  "url": "www.jisilu.cn",
  "view": 0
}
```
