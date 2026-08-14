# Liquipedia - Counter-Strike Team Match Results

## Coverage
`index-only`

## Route
- Namespace: `liquipedia`
- Namespace Name: `Liquipedia`
- Route Path: `/liquipedia/counterstrike/matches/:team`
- Route Name: `Counter-Strike Team Match Results`
- Example: `/liquipedia/counterstrike/matches/Team_Falcons`
- URL: `liquipedia.net`
- Language: `_None_`
- Categories: `game`
- Maintainers: `CookiePieWw`
- Source Location: `cs-matches.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `liquipedia.net/counterstrike/:id/Matches`
  - `liquipedia.net/dota2/:id`
- `target`: `/counterstrike/matches/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/liquipedia/counterstrike/matches/Team_Falcons",
  "heat": 2,
  "location": "cs-matches.ts",
  "maintainers": [
    "CookiePieWw"
  ],
  "name": "Counter-Strike Team Match Results",
  "path": "/counterstrike/matches/:team",
  "radar": [
    {
      "source": [
        "liquipedia.net/counterstrike/:id/Matches",
        "liquipedia.net/dota2/:id"
      ],
      "target": "/counterstrike/matches/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "[Counter-Strike] Team_Falcons Match Results From Liquipedia - Powered by RSSHub",
      "errorAt": "2026-03-16T14:57:14.264Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "137121125120034816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://liquipedia.net/counterstrike/Team_Falcons/Matches",
      "title": "[Counter-Strike] Team_Falcons Match Results From Liquipedia",
      "type": "feed",
      "url": "rsshub://liquipedia/counterstrike/matches/Team_Falcons"
    },
    {
      "description": "[Counter-Strike] G2_Esports Match Results From Liquipedia - Powered by RSSHub",
      "errorAt": "2026-03-16T15:57:33.489Z",
      "errorMessage": "Failed to fetch\n",
      "id": "58124618911394816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://liquipedia.net/counterstrike/G2_Esports/Matches",
      "title": "[Counter-Strike] G2_Esports Match Results From Liquipedia",
      "type": "feed",
      "url": "rsshub://liquipedia/counterstrike/matches/G2_Esports"
    }
  ]
}
```
