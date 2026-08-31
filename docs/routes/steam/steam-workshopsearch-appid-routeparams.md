# Steam - Community Workshop Search

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/steam/workshopsearch/:appid?/:routeParams?`
- Route Name: `Community Workshop Search`
- Example: `/steam/workshopsearch/730`
- URL: `store.steampowered.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `NyaaaDoge`
- Source Location: `workshop-search.tsx`
- Source Module: `_None_`

## Description
Steam Community Workshop Search Results.
The parameter 'l=language' changes the language of search results(if possible).
For example, route `/workshopsearch/730/l=schinese` will display the simplified Chinese descriptions of the entry.

Language Parameter:

| English | 简体中文 | 繁體中文 | 日本語   | 한국어  | ภาษาไทย | български | čeština | dansk  | Deutsch | español | latam | ελληνικά | français | italiano | Bahasa Indonesia | magyar    | Nederlands | norsk     | polski | português  | brasileiro | română   | русский | suomi   | svenska | Türkçe  | Tiếng Việt | українська |
| ------- | -------- | -------- | -------- | ------- | ------- | --------- | ------- | ------ | ------- | ------- | ----- | -------- | -------- | -------- | ---------------- | --------- | ---------- | --------- | ------ | ---------- | ---------- | -------- | ------- | ------- | ------- | ------- | ---------- | ---------- |
| english | schinese | tchinese | japanese | koreana | thai    | bulgarian | czech   | danish | german  | spanish | latam | greek    | french   | italian  | indonesian       | hungarian | dutch      | norwegian | polish | portuguese | brazilian  | romanian | russian | finnish | swedish | turkish | vietnamese | ukrainian  |

## Parameters
- `appid`: Steam appid, can be found on the community hub page or store page URL, 730 by default.
- `routeParams`: Route parameters, can be found on the search result page URL. Route parameters located after the appid.


## Features
_None_

## Radar
### Rule 1
- `title`: `Workshop Search Results`
- `source`:
  - `steamcommunity.com/app/:appid/workshop/`
- `target`: `/workshopsearch/:appid`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Steam Community Workshop Search Results.\nThe parameter 'l=language' changes the language of search results(if possible).\nFor example, route `/workshopsearch/730/l=schinese` will display the simplified Chinese descriptions of the entry.\n\nLanguage Parameter:\n\n| English | 简体中文 | 繁體中文 | 日本語   | 한국어  | ภาษาไทย | български | čeština | dansk  | Deutsch | español | latam | ελληνικά | français | italiano | Bahasa Indonesia | magyar    | Nederlands | norsk     | polski | português  | brasileiro | română   | русский | suomi   | svenska | Türkçe  | Tiếng Việt | українська |\n| ------- | -------- | -------- | -------- | ------- | ------- | --------- | ------- | ------ | ------- | ------- | ----- | -------- | -------- | -------- | ---------------- | --------- | ---------- | --------- | ------ | ---------- | ---------- | -------- | ------- | ------- | ------- | ------- | ---------- | ---------- |\n| english | schinese | tchinese | japanese | koreana | thai    | bulgarian | czech   | danish | german  | spanish | latam | greek    | french   | italian  | indonesian       | hungarian | dutch      | norwegian | polish | portuguese | brazilian  | romanian | russian | finnish | swedish | turkish | vietnamese | ukrainian  |",
  "example": "/steam/workshopsearch/730",
  "heat": 5,
  "location": "workshop-search.tsx",
  "maintainers": [
    "NyaaaDoge"
  ],
  "name": "Community Workshop Search",
  "parameters": {
    "appid": "Steam appid, can be found on the community hub page or store page URL, 730 by default.",
    "routeParams": "Route parameters, can be found on the search result page URL. Route parameters located after the appid."
  },
  "path": "/workshopsearch/:appid?/:routeParams?",
  "radar": [
    {
      "source": [
        "steamcommunity.com/app/:appid/workshop/"
      ],
      "target": "/workshopsearch/:appid",
      "title": "Workshop Search Results"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "有兴趣为《反恐精英》创作内容吗？ 那就来展示一下您的能耐吧。 探索我们的武器、印花、地图制作指南，并开始提交作品吧。 了解更多 - Powered by RSSHub",
      "errorAt": "2026-05-27T21:02:28.198Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "58572516674359296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://steamcommunity.com/workshop/browse/?appid=730&searchtext=ze&browsesort=mostrecent&section=&actualsort=mostrecent&l=schinese",
      "title": "Counter-Strike 2 Steam Workshop Content",
      "type": "feed",
      "url": "rsshub://steam/workshopsearch/730/searchtext=ze&browsesort=mostrecent&section=&actualsort=mostrecent&l=schinese"
    },
    {
      "description": "Interested in making content for Counter-Strike? Show us what you can do. Explore our guides for creating weapons, stickers, maps and start submitting. Learn More - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58747758573134848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://steamcommunity.com/workshop/browse/?appid=730",
      "title": "Counter-Strike 2 Steam Workshop Content",
      "type": "feed",
      "url": "rsshub://steam/workshopsearch/730"
    }
  ]
}
```
