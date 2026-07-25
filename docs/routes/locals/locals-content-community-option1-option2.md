# Locals - Content Feed

## Coverage
`index-only`

## Route
- Namespace: `locals`
- Namespace Name: `Locals`
- Route Path: `/locals/content/:community/:option1?/:option2?`
- Route Name: `Content Feed`
- Example: `/locals/content/mattfradd/video`
- URL: `locals.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `luckycold`
- Source Location: `feed.ts`
- Source Module: `_None_`

## Description
Fetches the Locals content library with an authenticated session cookie. By default it merges regular content and content+ posts, and it can be filtered by access tier and media type.

## Parameters
- `community`: Community slug from `locals.com/:community/feed?mode=content`
- `option1`: Filter or content type. Filters: `plus`, `nonplus`. Content types: `video`, `live`, `audio`, `podcast`, `article`, `document`, `pdf`
- `option2`: Content type when `option1` is a filter


## Features
- `requireConfig`: [{"description": "The value of the `locals2.v3.session` cookie after logging in to Locals", "name": "LOCALS_SESSION"}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `locals.com/:community/feed`
- `target`: `/content/:community`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Fetches the Locals content library with an authenticated session cookie. By default it merges regular content and content+ posts, and it can be filtered by access tier and media type.",
  "example": "/locals/content/mattfradd/video",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "The value of the `locals2.v3.session` cookie after logging in to Locals",
        "name": "LOCALS_SESSION"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "feed.ts",
  "maintainers": [
    "luckycold"
  ],
  "name": "Content Feed",
  "parameters": {
    "community": "Community slug from `locals.com/:community/feed?mode=content`",
    "option1": "Filter or content type. Filters: `plus`, `nonplus`. Content types: `video`, `live`, `audio`, `podcast`, `article`, `document`, `pdf`",
    "option2": "Content type when `option1` is a filter"
  },
  "path": "/content/:community/:option1?/:option2?",
  "radar": [
    {
      "source": [
        "locals.com/:community/feed"
      ],
      "target": "/content/:community"
    }
  ],
  "topFeeds": [
    {
      "description": "Locals content feed for Matt Fradd (video) - Powered by RSSHub",
      "errorAt": "2026-05-28T09:11:34.821Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nLocals RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n",
      "id": "261276499558545408",
      "image": "https://media3.locals.com/images/groups/52374/52374_ceunm7ccudql7dr_big.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://locals.com/mattfradd/feed?mode=content&content=video",
      "title": "Locals - Matt Fradd",
      "type": "feed",
      "url": "rsshub://locals/content/mattfradd/video"
    }
  ]
}
```
