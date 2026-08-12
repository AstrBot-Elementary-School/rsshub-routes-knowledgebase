# AtCoder - Posts

## Coverage
`index-only`

## Route
- Namespace: `atcoder`
- Namespace Name: `AtCoder`
- Route Path: `/atcoder/post/:language?/:keyword?`
- Route Name: `Posts`
- Example: `/atcoder/post`
- URL: `atcoder.jp`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: Language, `jp` as Japanese or `en` as English, English by default
- `keyword`: Keyword


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
    "programming"
  ],
  "example": "/atcoder/post",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "post.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Posts",
  "parameters": {
    "keyword": "Keyword",
    "language": "Language, `jp` as Japanese or `en` as English, English by default"
  },
  "path": "/post/:language?/:keyword?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Post Archive - AtCoder - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66281194474129408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://atcoder.jp/posts?lang=en",
      "title": "Post Archive - AtCoder",
      "type": "feed",
      "url": "rsshub://atcoder/post"
    },
    {
      "description": "Post Archive - AtCoder - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75678570335625216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://atcoder.jp/posts?lang=java",
      "title": "Post Archive - AtCoder",
      "type": "feed",
      "url": "rsshub://atcoder/post/java"
    }
  ]
}
```
