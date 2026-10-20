# PornHub - Model

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/pornhub/model/:username/:language?/:sort?/:img?`
- Route Name: `Model`
- Example: `/pornhub/model/stacy-starando`
- URL: `pornhub.com`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `I2IMk, queensferryme`
- Source Location: `model.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: language, see below. defaults to www
- `username`: username, part of the url e.g. `pornhub.com/model/stacy-starando`
- `sort`: sorting method, see below. Defaults to mr (most recent)
- `img`: show images, set to `img=1` to enable


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.pornhub.com/model/:username`
  - `www.pornhub.com/model/:username/*`
- `target`: `/model/:username`
### Rule 2
- `source`:
  - `de.pornhub.com/model/:username`
  - `de.pornhub.com/model/:username/*`
- `target`: `/model/:username/de`
### Rule 3
- `source`:
  - `fr.pornhub.com/model/:username`
  - `fr.pornhub.com/model/:username/*`
- `target`: `/model/:username/fr`
### Rule 4
- `source`:
  - `es.pornhub.com/model/:username`
  - `es.pornhub.com/model/:username/*`
- `target`: `/model/:username/es`
### Rule 5
- `source`:
  - `it.pornhub.com/model/:username`
  - `it.pornhub.com/model/:username/*`
- `target`: `/model/:username/it`
### Rule 6
- `source`:
  - `pt.pornhub.com/model/:username`
  - `pt.pornhub.com/model/:username/*`
- `target`: `/model/:username/pt`
### Rule 7
- `source`:
  - `pl.pornhub.com/model/:username`
  - `pl.pornhub.com/model/:username/*`
- `target`: `/model/:username/pl`
### Rule 8
- `source`:
  - `rt.pornhub.com/model/:username`
  - `rt.pornhub.com/model/:username/*`
- `target`: `/model/:username/rt`
### Rule 9
- `source`:
  - `jp.pornhub.com/model/:username`
  - `jp.pornhub.com/model/:username/*`
- `target`: `/model/:username/jp`
### Rule 10
- `source`:
  - `nl.pornhub.com/model/:username`
  - `nl.pornhub.com/model/:username/*`
- `target`: `/model/:username/nl`
### Rule 11
- `source`:
  - `cz.pornhub.com/model/:username`
  - `cz.pornhub.com/model/:username/*`
- `target`: `/model/:username/cz`
### Rule 12
- `source`:
  - `cn.pornhub.com/model/:username`
  - `cn.pornhub.com/model/:username/*`
- `target`: `/model/:username/cn`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "example": "/pornhub/model/stacy-starando",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21691,
  "location": "model.ts",
  "maintainers": [
    "I2IMk",
    "queensferryme"
  ],
  "name": "Model",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "language": "language, see below. defaults to www",
    "sort": "sorting method, see below. Defaults to mr (most recent)",
    "username": "username, part of the url e.g. `pornhub.com/model/stacy-starando`"
  },
  "path": "/model/:username/:language?/:sort?/:img?",
  "radar": [
    {
      "source": [
        "www.pornhub.com/model/:username",
        "www.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username"
    },
    {
      "source": [
        "de.pornhub.com/model/:username",
        "de.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/de"
    },
    {
      "source": [
        "fr.pornhub.com/model/:username",
        "fr.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/fr"
    },
    {
      "source": [
        "es.pornhub.com/model/:username",
        "es.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/es"
    },
    {
      "source": [
        "it.pornhub.com/model/:username",
        "it.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/it"
    },
    {
      "source": [
        "pt.pornhub.com/model/:username",
        "pt.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/pt"
    },
    {
      "source": [
        "pl.pornhub.com/model/:username",
        "pl.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/pl"
    },
    {
      "source": [
        "rt.pornhub.com/model/:username",
        "rt.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/rt"
    },
    {
      "source": [
        "jp.pornhub.com/model/:username",
        "jp.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/jp"
    },
    {
      "source": [
        "nl.pornhub.com/model/:username",
        "nl.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/nl"
    },
    {
      "source": [
        "cz.pornhub.com/model/:username",
        "cz.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/cz"
    },
    {
      "source": [
        "cn.pornhub.com/model/:username",
        "cn.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/cn"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "About Qiobnxingcaiii It’s 桥本香菜 QioBnXingCai(Coriander) here🧡 I create diverse sexual role-plays from my wet dreams🥰 Join me to enjoy playful Fetish. Click the official links and crave me with curiosity🫶🏻Leave me a comment X 嗨 我是你爱变装的女友 - 桥本香菜，让你对我上瘾 - 在右边的官方网站探索💋https://linktr.ee/qiobnxingcai 留言給我唷 ! - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58048142056827904",
      "image": "https://ei.phncdn.com/pics/users/0025/4226/8071/avatar97653765/(m=ewILGCjadOf)(mh=8eOa3KuFv_kv5s2G)200x200.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/model/qiobnxingcaiii/videos",
      "title": "Qiobnxingcaiii",
      "type": "feed",
      "url": "rsshub://pornhub/model/qiobnxingcaiii"
    },
    {
      "description": "About HongKongDoll I post new videos and exclusive clips on onlyfans, check out more on https://www.hongkongdoll.tv - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59119449662853120",
      "image": "https://ei.phncdn.com/(m=bLWsSeKlbyaT)(mh=KwF8w99zeBMs0dzt)81743a3d-252c-4984-b1a6-3a29edc7dcd1.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/model/hongkongdoll/videos",
      "title": "HongKongDoll",
      "type": "feed",
      "url": "rsshub://pornhub/model/hongkongdoll"
    }
  ],
  "view": 3
}
```
