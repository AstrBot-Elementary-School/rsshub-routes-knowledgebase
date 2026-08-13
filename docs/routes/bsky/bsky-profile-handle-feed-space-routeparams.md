# Bluesky (bsky) - Feeds

## Coverage
`index-only`

## Route
- Namespace: `bsky`
- Namespace Name: `Bluesky (bsky)`
- Route Path: `/bsky/profile/:handle/feed/:space/:routeParams?`
- Route Name: `Feeds`
- Example: `/bsky/profile/jaz.bsky.social/feed/cv:cat`
- URL: `bsky.app`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `FerrisChi`
- Source Location: `feeds.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `handle`: User handle, can be found in URL
- `space`: Space ID, can be found in URL


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
  "example": "/bsky/profile/jaz.bsky.social/feed/cv:cat",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 59,
  "location": "feeds.ts",
  "maintainers": [
    "FerrisChi"
  ],
  "name": "Feeds",
  "parameters": {
    "handle": "User handle, can be found in URL",
    "space": "Space ID, can be found in URL"
  },
  "path": "/profile/:handle/feed/:space/:routeParams?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "HQ for Onlyfans, Fansly, FMTY babes, strippers, & SWers of all kinds💙🤍 Real NSFW content from real people. Focus on Hot Girls & NB Porn, Lewds, & Nudes Verified creators only! Get approved: babesky.com/request Includes media tagged with #realNSFW - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "137363658073858048",
      "image": "https://cdn.bsky.app/img/avatar/plain/did:plc:db645kt5coo7teuoxdjhq34x/bafkreieypzlx2zarzgopqfof3w5usn6qu3o7pdovbuofiptymmwn6hdgcy",
      "ownerUserId": null,
      "siteUrl": "https://bsky.app/profile/realnsfw.social/feed/aaamkr6xjlwb2",
      "title": "Real NSFW ✅ — Bluesky",
      "type": "feed",
      "url": "rsshub://bsky/profile/realnsfw.social/feed/aaamkr6xjlwb2"
    },
    {
      "description": "Are you looking for new NSFW Art/Artists? Are you a NSFW Artist looking to grow your following? If so, this is the feed for you. Discover NSFW Artists is an opt-in, curated feed of hundreds of BlueSky artists under 5000 followers. Very inclusive, DM me to be added/removed! Updates take ~ 10m - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "137351369333348352",
      "image": "https://cdn.bsky.app/img/avatar/plain/did:plc:btrhhrtkx7oabgkamwgbgowt/bafkreid5jlugjhej36eotejzvdmaalsur6fr3xiwnhcmexwidnfueonezm",
      "ownerUserId": null,
      "siteUrl": "https://bsky.app/profile/prurientpeddler.bsky.social/feed/aaaakm6qk7cfe",
      "title": "Discover NSFW Artists — Bluesky",
      "type": "feed",
      "url": "rsshub://bsky/profile/prurientpeddler.bsky.social/feed/aaaakm6qk7cfe"
    }
  ],
  "view": 1
}
```
