# MissKON - Posts

## Coverage
`index-only`

## Route
- Namespace: `misskon`
- Namespace Name: `MissKON`
- Route Path: `/misskon/posts/:routeParams?`
- Route Name: `Posts`
- Example: `/misskon/posts/search=video&tags_exclude=353,3100&per_page=5`
- URL: `misskon.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `Urabartin`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `routeParams`: Additional parameters for filtering posts, refer to [WordPress API Reference](https://developer.wordpress.org/rest-api/reference/posts/#arguments) for details.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `misskon.com/`
- `target`: `/posts`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/misskon/posts/search=video&tags_exclude=353,3100&per_page=5",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 183,
  "location": "posts.ts",
  "maintainers": [
    "Urabartin"
  ],
  "name": "Posts",
  "parameters": {
    "routeParams": "Additional parameters for filtering posts, refer to [WordPress API Reference](https://developer.wordpress.org/rest-api/reference/posts/#arguments) for details."
  },
  "path": "/posts/:routeParams?",
  "radar": [
    {
      "source": [
        "misskon.com/"
      ],
      "target": "/posts"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "MissKON - Posts - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70149374631526400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://misskon.com/wp-json/wp/v2/posts",
      "title": "MissKON - Posts",
      "type": "feed",
      "url": "rsshub://misskon/posts"
    },
    {
      "description": "MissKON - search=video&tags_exclude=353,3100&per_page=5 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70321821822859264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://misskon.com/wp-json/wp/v2/posts?search=video&tags_exclude=353,3100&per_page=5",
      "title": "MissKON - search=video&tags_exclude=353,3100&per_page=5",
      "type": "feed",
      "url": "rsshub://misskon/posts/search=video&tags_exclude=353,3100&per_page=5"
    }
  ]
}
```
