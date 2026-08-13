# Cursor - Changelog

## Coverage
`index-only`

## Route
- Namespace: `cursor`
- Namespace Name: `Cursor`
- Route Path: `/cursor/changelog/:locale?`
- Route Name: `Changelog`
- Example: `/cursor/changelog`
- URL: `cursor.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `p3psi-boo, nczitzk`
- Source Location: `changelog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `locale`: Locale appended to the route path, e.g. `ja`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cursor.com/changelog`
- `target`: `/changelog`
### Rule 2
- `source`:
  - `cursor.com/:locale/changelog`
- `target`: `/changelog/:locale`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/cursor/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 196,
  "location": "changelog.ts",
  "maintainers": [
    "p3psi-boo",
    "nczitzk"
  ],
  "name": "Changelog",
  "parameters": {
    "locale": "Locale appended to the route path, e.g. `ja`"
  },
  "path": "/changelog/:locale?",
  "radar": [
    {
      "source": [
        "cursor.com/changelog"
      ],
      "target": "/changelog"
    },
    {
      "source": [
        "cursor.com/:locale/changelog"
      ],
      "target": "/changelog/:locale"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "New updates and improvements. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "95136775344565248",
      "image": "https://ptht05hbb1ssoooe.public.blob.vercel-storage.com/assets/uploads/changelog-og.png",
      "ownerUserId": null,
      "siteUrl": "https://cursor.com/changelog",
      "title": "What's New in Cursor — Latest Updates & Release Notes",
      "type": "feed",
      "url": "rsshub://cursor/changelog"
    }
  ],
  "url": "cursor.com",
  "view": 0
}
```
