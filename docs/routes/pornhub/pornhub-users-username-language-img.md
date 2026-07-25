# PornHub - Users

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/pornhub/users/:username/:language?/:img?`
- Route Name: `Users`
- Example: `/pornhub/users/pornhubmodels`
- URL: `pornhub.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `I2IMk, queensferryme`
- Source Location: `users.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: language, see below. defaults to `www` (English)
- `username`: username, part of the url e.g. `pornhub.com/users/pornhubmodels`
- `img`: show images, set to `img=1` to enable


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
  - `www.pornhub.com/users/:username`
  - `www.pornhub.com/users/:username/*`
- `target`: `/users/:username`
### Rule 2
- `source`:
  - `de.pornhub.com/users/:username`
  - `de.pornhub.com/users/:username/*`
- `target`: `/users/:username/de`
### Rule 3
- `source`:
  - `fr.pornhub.com/users/:username`
  - `fr.pornhub.com/users/:username/*`
- `target`: `/users/:username/fr`
### Rule 4
- `source`:
  - `es.pornhub.com/users/:username`
  - `es.pornhub.com/users/:username/*`
- `target`: `/users/:username/es`
### Rule 5
- `source`:
  - `it.pornhub.com/users/:username`
  - `it.pornhub.com/users/:username/*`
- `target`: `/users/:username/it`
### Rule 6
- `source`:
  - `pt.pornhub.com/users/:username`
  - `pt.pornhub.com/users/:username/*`
- `target`: `/users/:username/pt`
### Rule 7
- `source`:
  - `pl.pornhub.com/users/:username`
  - `pl.pornhub.com/users/:username/*`
- `target`: `/users/:username/pl`
### Rule 8
- `source`:
  - `rt.pornhub.com/users/:username`
  - `rt.pornhub.com/users/:username/*`
- `target`: `/users/:username/rt`
### Rule 9
- `source`:
  - `jp.pornhub.com/users/:username`
  - `jp.pornhub.com/users/:username/*`
- `target`: `/users/:username/jp`
### Rule 10
- `source`:
  - `nl.pornhub.com/users/:username`
  - `nl.pornhub.com/users/:username/*`
- `target`: `/users/:username/nl`
### Rule 11
- `source`:
  - `cz.pornhub.com/users/:username`
  - `cz.pornhub.com/users/:username/*`
- `target`: `/users/:username/cz`
### Rule 12
- `source`:
  - `cn.pornhub.com/users/:username`
  - `cn.pornhub.com/users/:username/*`
- `target`: `/users/:username/cn`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/pornhub/users/pornhubmodels",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 115,
  "location": "users.ts",
  "maintainers": [
    "I2IMk",
    "queensferryme"
  ],
  "name": "Users",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "language": "language, see below. defaults to `www` (English)",
    "username": "username, part of the url e.g. `pornhub.com/users/pornhubmodels`"
  },
  "path": "/users/:username/:language?/:img?",
  "radar": [
    {
      "source": [
        "www.pornhub.com/users/:username",
        "www.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username"
    },
    {
      "source": [
        "de.pornhub.com/users/:username",
        "de.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/de"
    },
    {
      "source": [
        "fr.pornhub.com/users/:username",
        "fr.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/fr"
    },
    {
      "source": [
        "es.pornhub.com/users/:username",
        "es.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/es"
    },
    {
      "source": [
        "it.pornhub.com/users/:username",
        "it.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/it"
    },
    {
      "source": [
        "pt.pornhub.com/users/:username",
        "pt.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/pt"
    },
    {
      "source": [
        "pl.pornhub.com/users/:username",
        "pl.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/pl"
    },
    {
      "source": [
        "rt.pornhub.com/users/:username",
        "rt.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/rt"
    },
    {
      "source": [
        "jp.pornhub.com/users/:username",
        "jp.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/jp"
    },
    {
      "source": [
        "nl.pornhub.com/users/:username",
        "nl.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/nl"
    },
    {
      "source": [
        "cz.pornhub.com/users/:username",
        "cz.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/cz"
    },
    {
      "source": [
        "cn.pornhub.com/users/:username",
        "cn.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/cn"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 'RSSHub' not to be 'RSSHub' // Object.is equality\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:69:30)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The Pornhub Model Program has over 165,000 models currently! We're highlighting some of the best, most interesting and newsworthy of the community. This channel will feature the marketing campaigns featuring our models, the top videos, fan clubs and creators of the month and other news and development from Pornhub. Managed by @aurora-watson @pornhubnat Follow us on Twitter: @pornhubhelp @pornhubmodels @modelhub @phmodelsgay Follow us on Instagram: @modelprogram - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60209777936441344",
      "image": "https://ei.phncdn.com/pics/users/u/001/753/486/121/avatar1591208557/(m=ewILGCjadOf)(mh=gqWx0YkWIk1VyZK8)200x200.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/users/pornhubmodels/videos",
      "title": "PornhubModels",
      "type": "feed",
      "url": "rsshub://pornhub/users/pornhubmodels"
    },
    {
      "description": " - Powered by RSSHub",
      "errorAt": "2026-07-13T17:56:35.675Z",
      "errorMessage": "[GET] \"https://www.pornhub.com/users/mrbunny4sex/videos\": 404 Not Found\n",
      "id": "150930652077867008",
      "image": "https://ei.phncdn.com/(m=bLWsSeKlbyaT)(mh=YAcOug2B1YyD62qr)a08347a3-287c-4b15-8058-b28116aca02c.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/users/mrbunny4sex/videos",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://pornhub/users/mrbunny4sex"
    }
  ]
}
```
