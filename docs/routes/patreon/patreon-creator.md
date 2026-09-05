# Patreon - Home

## Coverage
`index-only`

## Route
- Namespace: `patreon`
- Namespace Name: `Patreon`
- Route Path: `/patreon/:creator`
- Route Name: `Home`
- Example: `/patreon/straightupsisters`
- URL: `www.patreon.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `feed.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `creator`: Patreon creator id, can be found in the url


## Features
- `requireConfig`: [{"description": "The value of the session_id cookie after logging in to Patreon, required to access paid posts", "name": "PATREON_SESSION_ID", "optional": true}]
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `patreon.com/:creator`
  - `www.patreon.com/cw/:creator`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/patreon/straightupsisters",
  "features": {
    "nsfw": true,
    "requireConfig": [
      {
        "description": "The value of the session_id cookie after logging in to Patreon, required to access paid posts",
        "name": "PATREON_SESSION_ID",
        "optional": true
      }
    ]
  },
  "heat": 15,
  "location": "feed.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Home",
  "parameters": {
    "creator": "Patreon creator id, can be found in the url"
  },
  "path": "/:creator",
  "radar": [
    {
      "source": [
        "patreon.com/:creator",
        "www.patreon.com/cw/:creator"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Creating Catholic videos, blog posts, and a podcast - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "210727018282671124",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/user/3447535/5bfb46da077a4253a77bb46e612a0178/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/3.jpg?token-hash=LXunSLeZIV4QHiraqd6nEAbEBMg8-G4CTdgQLAlMJwo%3D&token-time=1789776000",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/capturingchristianity",
      "title": "Cameron Bertuzzi",
      "type": "feed",
      "url": "rsshub://patreon/capturingchristianity"
    },
    {
      "description": "Yaoi/Gay AI artworks. (NSFW) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "107187512318883840",
      "image": "https://c10.patreonusercontent.com/4/patreon-media/p/campaign/12481247/88cace64bc5f4c1581085f33ed4e684d/eyJoIjoxMDgwLCJ3IjoxMDgwfQ%3D%3D/7.png?token-hash=g1fYK3L3XpxWHG7DVO05cnE_stfI2iAOozagHCzS6tw%3D&token-time=1789776000",
      "ownerUserId": null,
      "siteUrl": "https://www.patreon.com/Valarant",
      "title": "Valarant",
      "type": "feed",
      "url": "rsshub://patreon/Valarant"
    }
  ]
}
```
