# Steam - Sharefile Changelog

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/steam/sharefile-changelog/:sharefileID/:routeParams?`
- Route Name: `Sharefile Changelog`
- Example: `/steam/sharefile-changelog/2851063440/l=schinese`
- URL: `store.steampowered.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `NyaaaDoge`
- Source Location: `sharefile-changelog.ts`
- Source Module: `_None_`

## Description
Steam Community Sharefile's Changelog. Primary used for a workshop item.
Helpful route parameters:

- `l=` language parameter, change the language of description.
- `p=` page parameter, change the results page. p=1 by default.

## Parameters
- `sharefileID`: Steam community sharefile id. Usually refers to a workshop item.
- `routeParams`: Route parameters.


## Features
_None_

## Radar
### Rule 1
- `title`: `Sharefile Changelog`
- `source`:
  - `steamcommunity.com/sharedfiles/filedetails/changelog/:sharefileID`
- `target`: `/sharefile-changelog/:sharefileID`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Steam Community Sharefile's Changelog. Primary used for a workshop item.\nHelpful route parameters:\n\n- `l=` language parameter, change the language of description.\n- `p=` page parameter, change the results page. p=1 by default.",
  "example": "/steam/sharefile-changelog/2851063440/l=schinese",
  "heat": 1,
  "location": "sharefile-changelog.ts",
  "maintainers": [
    "NyaaaDoge"
  ],
  "name": "Sharefile Changelog",
  "parameters": {
    "routeParams": "Route parameters.",
    "sharefileID": "Steam community sharefile id. Usually refers to a workshop item."
  },
  "path": "/sharefile-changelog/:sharefileID/:routeParams?",
  "radar": [
    {
      "source": [
        "steamcommunity.com/sharedfiles/filedetails/changelog/:sharefileID"
      ],
      "target": "/sharefile-changelog/:sharefileID",
      "title": "Sharefile Changelog"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://steamcommunity.com/sharedfile…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "tModLoader steam community sharefile changelog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "242658970454784000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://steamcommunity.com/sharedfiles/filedetails/changelog/2815540735",
      "title": "Fargo's Souls Mod",
      "type": "feed",
      "url": "rsshub://steam/sharefile-changelog/2815540735/l=schinese"
    }
  ]
}
```
