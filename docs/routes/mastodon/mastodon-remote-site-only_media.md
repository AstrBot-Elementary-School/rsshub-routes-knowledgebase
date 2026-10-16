# Mastodon - Instance timeline (federated)

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/mastodon/remote/:site/:only_media?`
- Route Name: `Instance timeline (federated)`
- Example: `/mastodon/remote/pawoo.net/true`
- URL: `mastodon.social`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `timeline-remote.ts`
- Source Module: `_None_`

## Description
If the instance address is not `mastodon.social` or `pawoo.net`, then the route requires `ALLOW_USER_SUPPLY_UNSAFE_DOMAIN` to be `true`.

## Parameters
- `site`: instance address, only domain, no `http://` or `https://` protocol header
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
  "description": "If the instance address is not `mastodon.social` or `pawoo.net`, then the route requires `ALLOW_USER_SUPPLY_UNSAFE_DOMAIN` to be `true`.",
  "example": "/mastodon/remote/pawoo.net/true",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "timeline-remote.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "Instance timeline (federated)",
  "parameters": {
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
    },
    "site": "instance address, only domain, no `http://` or `https://` protocol header"
  },
  "path": "/remote/:site/:only_media?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Federated Public Media Timeline on pawoo.net - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67190720346044416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pawoo.net/",
      "title": "Federated Public Media Timeline on pawoo.net",
      "type": "feed",
      "url": "rsshub://mastodon/remote/pawoo.net/true"
    },
    {
      "description": "Federated Public Timeline on pawoo.net - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83530831395657728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pawoo.net/",
      "title": "Federated Public Timeline on pawoo.net",
      "type": "feed",
      "url": "rsshub://mastodon/remote/pawoo.net/false"
    }
  ],
  "view": 1
}
```
