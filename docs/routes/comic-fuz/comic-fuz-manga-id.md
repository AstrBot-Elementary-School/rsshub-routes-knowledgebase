# COMIC FUZ - 漫画详情

## Coverage
`index-only`

## Route
- Namespace: `comic-fuz`
- Namespace Name: `COMIC FUZ`
- Route Path: `/comic-fuz/manga/:id`
- Route Name: `漫画详情`
- Example: `/comic-fuz/manga/218`
- URL: `comic-fuz.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `xiaobailoves`
- Source Location: `manga.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: ComicFuz中对应的漫画id


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
  - `comic-fuz.com/manga/:id`
- `target`: `/manga/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comic-fuz/manga/218",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "manga.ts",
  "maintainers": [
    "xiaobailoves"
  ],
  "name": "漫画详情",
  "parameters": {
    "id": "ComicFuz中对应的漫画id"
  },
  "path": "/manga/:id",
  "radar": [
    {
      "source": [
        "comic-fuz.com/manga/:id"
      ],
      "target": "/manga/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -1031878335 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "富士山が見える湖畔でキャンプをする女の子、リン。自転車に乗り富士山を見にきた女の子、なでしこ。二人でカップラーメンを食べて見た景色は…。読めばキャンプに行きたくなる。行かなくても行った気分になる。そんな新感覚キャンプマンガの登場です! - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "254832773941916672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://comic-fuz.com/manga/218",
      "title": "COMIC FUZ - ゆるキャン△",
      "type": "feed",
      "url": "rsshub://comic-fuz/manga/218"
    },
    {
      "description": "風紀委員長・亜鳥に憧れ、気を引きたい一心でなぜか不良を目指すことにした高校一年生・優。 しかしワルくてカッコいいところをアピールするはずが、天真爛漫で人たらしな亜鳥の言動に小動物のごとく翻弄される…!? ぜんぜん悪くない不良少女の学園4コマ！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1218500250046431232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://comic-fuz.com/manga/2664",
      "title": "COMIC FUZ - ばっどがーる",
      "type": "feed",
      "url": "rsshub://comic-fuz/manga/2664"
    }
  ]
}
```
