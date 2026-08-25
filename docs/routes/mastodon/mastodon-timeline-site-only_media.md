# Mastodon - Instance timeline (local)

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/mastodon/timeline/:site/:only_media?`
- Route Name: `Instance timeline (local)`
- Example: `/mastodon/timeline/pawoo.net/true`
- URL: `mastodon.social`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `timeline-local.ts`
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
  "example": "/mastodon/timeline/pawoo.net/true",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "timeline-local.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "Instance timeline (local)",
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
  "path": "/timeline/:site/:only_media?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Local Public Media Timeline on pawoo.net - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67190628931188736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pawoo.net/",
      "title": "Local Public Media Timeline on pawoo.net",
      "type": "feed",
      "url": "rsshub://mastodon/timeline/pawoo.net/true"
    },
    {
      "description": "Local Public Timeline on fairy.id - Powered by RSSHub",
      "errorAt": "2026-01-22T04:17:25.246Z",
      "errorMessage": "This RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.\n",
      "id": "73036299014036480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fairy.id/",
      "title": "Local Public Timeline on fairy.id",
      "type": "feed",
      "url": "rsshub://mastodon/timeline/fairy.id/false"
    }
  ],
  "view": 1
}
```
