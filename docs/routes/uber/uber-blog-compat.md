# Uber - Engineering

## Coverage
`index-only`

## Route
- Namespace: `uber`
- Namespace Name: `Uber`
- Route Path: `/uber/blog/:compat?`
- Route Name: `Engineering`
- Example: `/uber/blog`
- URL: `www.uber.com/en-HK/blog/engineering`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `hulb`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
The English blog on any of Uber's regional sites (e.g., [www.uber.com/en-JP/blog](http://www.uber.com/en-JP/blog)) is the same engineering blog provided by this route, so language selection is not supported. This route is not for the public news blog on specific regional sites (e.g., [www.uber.com/ja-JP/blog](http://www.uber.com/ja-JP/blog)).

## Parameters
_None_


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
  - `www.uber.com/:language/blog/engineering`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "The English blog on any of Uber's regional sites (e.g., [www.uber.com/en-JP/blog](http://www.uber.com/en-JP/blog)) is the same engineering blog provided by this route, so language selection is not supported. This route is not for the public news blog on specific regional sites (e.g., [www.uber.com/ja-JP/blog](http://www.uber.com/ja-JP/blog)).",
  "example": "/uber/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 98,
  "location": "blog.ts",
  "maintainers": [
    "hulb"
  ],
  "name": "Engineering",
  "path": "/blog/:compat?",
  "radar": [
    {
      "source": [
        "www.uber.com/:language/blog/engineering"
      ],
      "target": "/blog"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "The technology behind Uber Engineering - Powered by RSSHub",
      "errorAt": "2026-04-01T00:07:14.390Z",
      "errorMessage": "[GET] \"https://www.uber.com/en-HK/blog/engineering/rss/\": 404 Not Found\n[GET] \"https://www.uber.com/en-HK/blog/engineering/rss/\": 404 Not Found\n",
      "id": "56764323854292992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.uber.com/blog/engineering",
      "title": "Uber Engineering Blog",
      "type": "feed",
      "url": "rsshub://uber/blog"
    }
  ],
  "url": "www.uber.com/en-HK/blog/engineering",
  "zh": {
    "description": "uber 的任何区域站点的英文 blog（例如 [www.uber.com/en-JP/blog](http://www.uber.com/en-JP/blog)）都是相同的内容，正是本路由提供的 engineering blog，因此本路由不提供语言选择；本路由不是 uber 在特定区域站点的公开新闻 blog（例如 [www.uber.com/ja-JP/blog](http://www.uber.com/ja-JP/blog)）"
  }
}
```
