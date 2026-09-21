# Temposmart - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `temposmart`
- Namespace Name: `Temposmart`
- Route Path: `/temposmart/estates/:pref?/:district?`
- Route Name: `新着物件`
- Example: `/temposmart/estates/tokyo`
- URL: `www.temposmart.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `estates.ts`
- Source Module: `_None_`

## Description
New listings on テンポスマート for one prefecture — or one 市区町村 when `district` is given — sorted by 新着順 (first page, 50 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，保証金，礼金，造作譲渡料，現況，業種制限，登録日，…) parsed from the list and detail pages; unknown values are `null`.

`district` is a 5-digit JIS X 0402 市区町村 code whose first two digits are the prefecture — `/temposmart/estates/tokyo/13104` is 新宿区. A code from another prefecture is rejected rather than silently returning that prefecture's listings.

| Query   | Description                                                                  | Default |
| ------- | ---------------------------------------------------------------------------- | ------- |
| `limit` | Number of listings to process (detail pages are fetched per listing), max 50 | 30      |

## Parameters
- `pref`: {"default": "tokyo", "description": "都道府県 slug or JIS X 0401 code", "options": [{"label": "東京都 (13)", "value": "tokyo"}, {"label": "神奈川県 (14)", "value": "kanagawa"}, {"label": "埼玉県 (11)", "value": "saitama"}, {"label": "千葉県 (12)", "value": "chiba"}, {"label": "大阪府 (27)", "value": "osaka"}, {"label": "京都府 (26)", "value": "kyoto"}, {"label": "兵庫県 (28)", "value": "hyogo"}]}
- `district`: {"description": "Optional 市区町村, as a 5-digit JIS X 0402 code (新宿区 `13104`, 港区 `13103`, 横浜市中区 `14104`). Must belong to `pref`; omit for the whole prefecture."}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.temposmart.jp/estates/pref/:pref`
- `target`: `/estates/:pref`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "New listings on テンポスマート for one prefecture — or one 市区町村 when `district` is given — sorted by 新着順 (first page, 50 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，保証金，礼金，造作譲渡料，現況，業種制限，登録日，…) parsed from the list and detail pages; unknown values are `null`.\n\n`district` is a 5-digit JIS X 0402 市区町村 code whose first two digits are the prefecture — `/temposmart/estates/tokyo/13104` is 新宿区. A code from another prefecture is rejected rather than silently returning that prefecture's listings.\n\n| Query   | Description                                                                  | Default |\n| ------- | ---------------------------------------------------------------------------- | ------- |\n| `limit` | Number of listings to process (detail pages are fetched per listing), max 50 | 30      |",
  "example": "/temposmart/estates/tokyo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "estates.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "新着物件",
  "parameters": {
    "district": {
      "description": "Optional 市区町村, as a 5-digit JIS X 0402 code (新宿区 `13104`, 港区 `13103`, 横浜市中区 `14104`). Must belong to `pref`; omit for the whole prefecture."
    },
    "pref": {
      "default": "tokyo",
      "description": "都道府県 slug or JIS X 0401 code",
      "options": [
        {
          "label": "東京都 (13)",
          "value": "tokyo"
        },
        {
          "label": "神奈川県 (14)",
          "value": "kanagawa"
        },
        {
          "label": "埼玉県 (11)",
          "value": "saitama"
        },
        {
          "label": "千葉県 (12)",
          "value": "chiba"
        },
        {
          "label": "大阪府 (27)",
          "value": "osaka"
        },
        {
          "label": "京都府 (26)",
          "value": "kyoto"
        },
        {
          "label": "兵庫県 (28)",
          "value": "hyogo"
        }
      ]
    }
  },
  "path": "/estates/:pref?/:district?",
  "radar": [
    {
      "source": [
        "www.temposmart.jp/estates/pref/:pref"
      ],
      "target": "/estates/:pref"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [],
  "url": "www.temposmart.jp"
}
```
