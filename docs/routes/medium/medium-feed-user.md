# Medium - Medium Feed

## Coverage
`index-only`

## Route
- Namespace: `medium`
- Namespace Name: `Medium`
- Route Path: `/medium/feed/:user`
- Route Name: `Medium Feed`
- Example: `/medium/feed/zhgchgli`
- URL: `medium.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `pseudoyu`
- Source Location: `feed.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: Username of the Medium


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
  - `medium.com/@:user`
- `target`: `/feed/:user`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/medium/feed/zhgchgli",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 33,
  "location": "feed.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "Medium Feed",
  "parameters": {
    "user": "Username of the Medium"
  },
  "path": "/feed/:user",
  "radar": [
    {
      "source": [
        "medium.com/@:user"
      ],
      "target": "/feed/:user"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Stories by Gate Ventures on Medium - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "101277342798840832",
      "image": "https://cdn-images-1.medium.com/fit/c/150/150/1*39spPNH5p_Q21l-sdv0-dg.png",
      "ownerUserId": null,
      "siteUrl": "https://medium.com/@gate_ventures?source=rss-a030b95b6ffb------2",
      "title": "Stories by Gate Ventures on Medium",
      "type": "feed",
      "url": "rsshub://medium/feed/@gate_ventures"
    },
    {
      "description": "Stories by Ximya on Medium - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "125976551457979392",
      "image": "https://cdn-images-1.medium.com/fit/c/150/150/1*Iq4-bb159lSKVrb_exoOPw.png",
      "ownerUserId": null,
      "siteUrl": "https://medium.com/@ximya?source=rss-b042ce66d922------2",
      "title": "Stories by Ximya on Medium",
      "type": "feed",
      "url": "rsshub://medium/feed/ximya"
    }
  ],
  "view": 1
}
```
