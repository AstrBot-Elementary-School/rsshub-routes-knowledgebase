# 微信小程序 - 公众号（CareerEngine 来源）

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/wechat/ce/:id`
- Route Name: `公众号（CareerEngine 来源）`
- Example: `/wechat/ce/595a5b14d7164e53908f1606`
- URL: `posts.careerengine.us`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `HenryQW`
- Source Location: `ce.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 公众号 id，在 [CareerEngine](https://search.careerengine.us/) 搜索公众号，通过 URL 中找到对应的公众号 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cimidata.com/a/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/wechat/ce/595a5b14d7164e53908f1606",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 225,
  "location": "ce.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "公众号（CareerEngine 来源）",
  "parameters": {
    "id": "公众号 id，在 [CareerEngine](https://search.careerengine.us/) 搜索公众号，通过 URL 中找到对应的公众号 id"
  },
  "path": "/ce/:id",
  "radar": [
    {
      "source": [
        "cimidata.com/a/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "专注于大数据、人工智能技术应用的分享与交流。致力于成就百万数据科学家。定期组织技术分享直播，并整理大数据、推荐/搜索算法、广告算法、NLP 自然语言处理算法、智能风控、自动驾驶、机器学习/深度学习等技术应用文章。 - Powered by RSSHub",
      "errorAt": "2025-08-01T18:51:41.921Z",
      "errorMessage": "[GET] \"https://posts.careerengine.us/author/5c84fb2104a9c94955fe9e73/rss\": 404 Not Found\n",
      "id": "69399076414973952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://posts.careerengine.us/author/5c84fb2104a9c94955fe9e73/posts",
      "title": "微信公众号 - DataFunTalk",
      "type": "feed",
      "url": "rsshub://wechat/ce/5c84fb2104a9c94955fe9e73"
    },
    {
      "description": "在这里，读懂真实的市场。 - Powered by RSSHub",
      "errorAt": "2025-08-01T19:11:21.887Z",
      "errorMessage": "502 \n[GET] \"https://posts.careerengine.us/author/5c68a639279f245e524d860f/rss\": 404 Not Found\n",
      "id": "57479832114244608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://posts.careerengine.us/author/5c68a639279f245e524d860f/posts",
      "title": "微信公众号 - 奥派经济学",
      "type": "feed",
      "url": "rsshub://wechat/ce/5c68a639279f245e524d860f"
    }
  ]
}
```
