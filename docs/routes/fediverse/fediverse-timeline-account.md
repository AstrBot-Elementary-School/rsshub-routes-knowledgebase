# Fediverse - Timeline

## Coverage
`index-only`

## Route
- Namespace: `fediverse`
- Namespace Name: `Fediverse`
- Route Path: `/fediverse/timeline/:account`
- Route Name: `Timeline`
- Example: `/fediverse/timeline/Mastodon@mastodon.social`
- URL: `fediverse.observer`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod, pseudoyu`
- Source Location: `timeline.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `account`: username@domain


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
  "example": "/fediverse/timeline/Mastodon@mastodon.social",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 59,
  "location": "timeline.ts",
  "maintainers": [
    "DIYgod",
    "pseudoyu"
  ],
  "name": "Timeline",
  "parameters": {
    "account": "username@domain"
  },
  "path": "/timeline/:account",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Public posts from @pseudoyu@mas.to - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56548464220512256",
      "image": "https://media.mas.to/accounts/avatars/109/300/507/275/095/341/original/9a0abd8b35530714.jpeg",
      "ownerUserId": "41229460898486272",
      "siteUrl": "https://mas.to/@pseudoyu",
      "title": "pseudoyu (Fediverse@pseudoyu@mas.to)",
      "type": "feed",
      "url": "rsshub://fediverse/timeline/pseudoyu%40mas.to"
    },
    {
      "description": "Public posts from @Mastodon@mastodon.social - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56934811567432704",
      "image": "https://files.mastodon.social/accounts/avatars/000/013/179/original/b4ceb19c9c54ec7e.png",
      "ownerUserId": null,
      "siteUrl": "https://mastodon.social/@Mastodon",
      "title": "Mastodon (Fediverse@Mastodon@mastodon.social)",
      "type": "feed",
      "url": "rsshub://fediverse/timeline/Mastodon@mastodon.social"
    }
  ],
  "view": 1
}
```
