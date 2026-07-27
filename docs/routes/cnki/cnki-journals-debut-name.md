# 中国知网 - 网络首发

## Coverage
`index-only`

## Route
- Namespace: `cnki`
- Namespace Name: `中国知网`
- Route Path: `/cnki/journals/debut/:name`
- Route Name: `网络首发`
- Example: `/cnki/journals/debut/LKGP`
- URL: `navi.cnki.net`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Fatpandac`
- Source Location: `debut.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 期刊缩写，可以在网址中得到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `navi.cnki.net/knavi/journals/:name/detail`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/cnki/journals/debut/LKGP",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 590,
  "location": "debut.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "网络首发",
  "parameters": {
    "name": "期刊缩写，可以在网址中得到"
  },
  "path": "/journals/debut/:name",
  "radar": [
    {
      "source": [
        "navi.cnki.net/knavi/journals/:name/detail"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "软件学报 - 全网首发 - Powered by RSSHub",
      "errorAt": "2026-01-14T10:25:00.992Z",
      "errorMessage": "[POST] \"https://chn.oversea.cnki.net/knavi/JournalDetail/GetnfAllOutline\": 404 Not Found\n502 \n[GET] \"https://chn.oversea.cnki.net/knavi/JournalDetail?pcode=CjFD&pykm=RJXB\": 404 Not Found\n502 \n[GET] \"https://chn.oversea.cnki.net/knavi/JournalDetail?pcode=CjFD&pykm=RJXB\": 404 Not Found\n[POST] \"https://chn.oversea.cnki.net/knavi/JournalDetail/GetnfAllOutline\": 404 Not Found\n",
      "id": "71804585523221504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://navi.cnki.net/knavi/journals/RJXB/detail",
      "title": "软件学报 - 全网首发",
      "type": "feed",
      "url": "rsshub://cnki/journals/debut/RJXB"
    },
    {
      "description": "心理学报 - 全网首发 - Powered by RSSHub",
      "errorAt": "2026-01-14T09:07:04.332Z",
      "errorMessage": "[POST] \"https://chn.oversea.cnki.net/knavi/JournalDetail/GetnfAllOutline\": 404 Not Found\n[POST] \"https://chn.oversea.cnki.net/knavi/JournalDetail/GetnfAllOutline\": 404 Not Found\n[GET] \"https://chn.oversea.cnki.net/knavi/JournalDetail?pcode=CjFD&pykm=XLXB\": 404 Not Found\n[POST] \"https://chn.oversea.cnki.net/knavi/JournalDetail/GetnfAllOutline\": 404 Not Found\n",
      "id": "73613364969526272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://navi.cnki.net/knavi/journals/XLXB/detail",
      "title": "心理学报 - 全网首发",
      "type": "feed",
      "url": "rsshub://cnki/journals/debut/XLXB"
    }
  ]
}
```
