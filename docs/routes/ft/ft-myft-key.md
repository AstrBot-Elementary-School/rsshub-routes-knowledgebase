# Financial Times - myFT personal RSS

## Coverage
`index-only`

## Route
- Namespace: `ft`
- Namespace Name: `Financial Times`
- Route Path: `/ft/myft/:key`
- Route Name: `myFT personal RSS`
- Example: `/ft/myft/rss-key`
- URL: `ft.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `HenryQW`
- Source Location: `myft.ts`
- Source Module: `_None_`

## Description
::: tip

- Visit ft.com -> myFT -> Contact Preferences to enable personal RSS feed, see [help.ft.com](https://help.ft.com/faq/email-alerts-and-contact-preferences/what-is-myft-rss-feed/)
- Obtain the key from the personal RSS address, it looks like `12345678-abcd-4036-82db-vdv20db024b8`

:::

## Parameters
- `key`: the last part of myFT personal RSS address


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
    "traditional-media"
  ],
  "description": "::: tip\n\n- Visit ft.com -> myFT -> Contact Preferences to enable personal RSS feed, see [help.ft.com](https://help.ft.com/faq/email-alerts-and-contact-preferences/what-is-myft-rss-feed/)\n- Obtain the key from the personal RSS address, it looks like `12345678-abcd-4036-82db-vdv20db024b8`\n\n:::",
  "example": "/ft/myft/rss-key",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "myft.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "myFT personal RSS",
  "parameters": {
    "key": "the last part of myFT personal RSS address"
  },
  "path": "/myft/:key",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-12T09:47:54.097Z",
      "errorMessage": "Attribute without value\nLine: 11\nColumn: 75\nChar: d\n",
      "id": "178028763735837702",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://ft/myft/REPLACE_WITH_KEY"
    },
    {
      "description": null,
      "errorAt": "2026-05-20T01:13:07.457Z",
      "errorMessage": "Attribute without value\nLine: 11\nColumn: 75\nChar: d\n",
      "id": "1105989238660136960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://ft/myft/all"
    }
  ]
}
```
