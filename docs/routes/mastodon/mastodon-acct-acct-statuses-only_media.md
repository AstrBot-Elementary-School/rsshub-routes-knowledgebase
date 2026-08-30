# Mastodon - User timeline

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/mastodon/acct/:acct/statuses/:only_media?`
- Route Name: `User timeline`
- Example: `/mastodon/acct/Mastodon@mastodon.social/statuses`
- URL: `mastodon.social`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `notofoe`
- Source Location: `acct.ts`
- Source Module: `_None_`

## Description
Started from Mastodon v4.0.0, the use of the `search` API in the route no longer requires a user token.
If the domain of your Webfinger account URI is the same as the API host of the instance (i.e., no delegation called in some other protocols), then no configuration is required and the route is available out of the box.
However, you can still specify these route-specific configurations if you need to override them.

## Parameters
- `acct`: Webfinger account URI, like `user@host`
- `only_media`: {"default": "false", "description": "whether only display media content, default to false, any value to true", "options": [{"label": "true", "value": "true"}, {"label": "false", "value": "false"}]}


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
    "social-media"
  ],
  "description": "Started from Mastodon v4.0.0, the use of the `search` API in the route no longer requires a user token.\nIf the domain of your Webfinger account URI is the same as the API host of the instance (i.e., no delegation called in some other protocols), then no configuration is required and the route is available out of the box.\nHowever, you can still specify these route-specific configurations if you need to override them.",
  "example": "/mastodon/acct/Mastodon@mastodon.social/statuses",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 168,
  "location": "acct.ts",
  "maintainers": [
    "notofoe"
  ],
  "name": "User timeline",
  "parameters": {
    "acct": "Webfinger account URI, like `user@host`",
    "only_media": {
      "default": "false",
      "description": "whether only display media content, default to false, any value to true",
      "options": [
        {
          "label": "true",
          "value": "true"
        },
        {
          "label": "false",
          "value": "false"
        }
      ]
    }
  },
  "path": "/acct/:acct/statuses/:only_media?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "与我周旋一二 (@normanzxy) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57284621284168704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://alive.bar/@normanzxy",
      "title": "与我周旋一二 (@normanzxy)",
      "type": "feed",
      "url": "rsshub://mastodon/acct/@normanzxy@alive.bar/statuses/true"
    },
    {
      "description": "<p>写代码是热爱，写到世界充满爱！</p> - Powered by RSSHub",
      "errorAt": "2026-05-03T01:25:49.063Z",
      "errorMessage": "[GET] \"https://mastodon.social/api/v1/accounts/109772491671724800/statuses?only_media=false\": 404 Not Found\n",
      "id": "91124297603706880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mastodon.social/@DIYgod",
      "title": "DIYgod (@DIYgod)",
      "type": "feed",
      "url": "rsshub://mastodon/acct/DIYgod%40mastodon.social/statuses/false"
    }
  ],
  "view": 1
}
```
