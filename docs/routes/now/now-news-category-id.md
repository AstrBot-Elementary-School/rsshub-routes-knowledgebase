# Now 新聞 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `now`
- Namespace Name: `Now 新聞`
- Route Path: `/now/news/:category?/:id?`
- Route Name: `新聞`
- Example: `/now/news`
- URL: `news.now.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: tip
**编号** 仅对事件追蹤、評論節目、新聞專題三个分类起作用，例子如下：

对于 [事件追蹤](https://news.now.com/home/tracker) 中的 [塔利班奪權](https://news.now.com/home/tracker/detail?catCode=123\&topicId=1056) 话题，其网址为 `https://news.now.com/home/tracker/detail?catCode=123&topicId=1056`，其中 `topicId` 为 1056，则对应路由为 [`/now/news/tracker/1056`](https://rsshub.app/now/news/tracker/1056)
:::

| 首頁 | 港聞  | 兩岸國際      | 娛樂          |
| ---- | ----- | ------------- | ------------- |
|      | local | international | entertainment |

| 生活 | 科技       | 財經    | 體育   |
| ---- | ---------- | ------- | ------ |
| life | technology | finance | sports |

| 事件追蹤 | 評論節目 | 新聞專題 |
| -------- | -------- | -------- |
| tracker  | feature  | opinion  |

## Parameters
- `category`: 分类，见下表，默认为首页
- `id`: 编号，可在对应专题/节目页 URL 中找到 topicId


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
  - `news.now.com/home/:category?`
  - `news.now.com/`
- `target`: `/news/:category?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n**编号** 仅对事件追蹤、評論節目、新聞專題三个分类起作用，例子如下：\n\n对于 [事件追蹤](https://news.now.com/home/tracker) 中的 [塔利班奪權](https://news.now.com/home/tracker/detail?catCode=123\\&topicId=1056) 话题，其网址为 `https://news.now.com/home/tracker/detail?catCode=123&topicId=1056`，其中 `topicId` 为 1056，则对应路由为 [`/now/news/tracker/1056`](https://rsshub.app/now/news/tracker/1056)\n:::\n\n| 首頁 | 港聞  | 兩岸國際      | 娛樂          |\n| ---- | ----- | ------------- | ------------- |\n|      | local | international | entertainment |\n\n| 生活 | 科技       | 財經    | 體育   |\n| ---- | ---------- | ------- | ------ |\n| life | technology | finance | sports |\n\n| 事件追蹤 | 評論節目 | 新聞專題 |\n| -------- | -------- | -------- |\n| tracker  | feature  | opinion  |",
  "example": "/now/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 187,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新聞",
  "parameters": {
    "category": "分类，见下表，默认为首页",
    "id": "编号，可在对应专题/节目页 URL 中找到 topicId"
  },
  "path": "/news/:category?/:id?",
  "radar": [
    {
      "source": [
        "news.now.com/home/:category?",
        "news.now.com/"
      ],
      "target": "/news/:category?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "首頁 | Now 新聞 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60960343462107136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.now.com/home",
      "title": "首頁 | Now 新聞",
      "type": "feed",
      "url": "rsshub://now/news"
    },
    {
      "description": "首頁 | Now 新聞 - Powered by RSSHub",
      "errorAt": "2026-01-08T10:08:35.267Z",
      "errorMessage": "[GET] \"https://d3sli7vh0lsda4.cloudfront.net/api/getNewsList?category=119&pageNo=1&pageSize=20\": <no response> fetch failed (getaddrinfo ENOTFOUND d3sli7vh0lsda4.cloudfront.net)\n",
      "id": "61348755817519104",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.now.com/home/local",
      "title": "首頁 | Now 新聞",
      "type": "feed",
      "url": "rsshub://now/news/local"
    }
  ],
  "url": "news.now.com/"
}
```
