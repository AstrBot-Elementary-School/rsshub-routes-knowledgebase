# Inuki Ichiba - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `inuki-ichiba`
- Namespace Name: `Inuki Ichiba`
- Route Path: `/inuki-ichiba/rent/:pref?`
- Route Name: `新着物件`
- Example: `/inuki-ichiba/rent/tokyo`
- URL: `inuki-ichiba.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `rent.ts`
- Source Module: `_None_`

## Description
New listings on 居抜き市場，20 per page (first page only). With a prefecture the search results are sorted by 新着順；without one the site's 新着物件 page is used. Each item's `_extra` carries the structured listing fields (賃料，坪，階，最寄駅，敷金・保証金，造作価格，物件タイプ，現業態，飲食条件，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`.

| Query   | Description                                                                  | Default |
| ------- | ---------------------------------------------------------------------------- | ------- |
| `limit` | Number of listings to process (detail pages are fetched per listing), max 20 | 20      |

## Parameters
- `pref`: {"description": "都道府県 slug or JIS X 0401 code; omit for the site-wide 新着物件 page (一都三県 mixed)", "options": [{"label": "東京都 (13)", "value": "tokyo"}, {"label": "神奈川県 (14)", "value": "kanagawa"}, {"label": "埼玉県 (11)", "value": "saitama"}, {"label": "千葉県 (12)", "value": "chiba"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `inuki-ichiba.jp/sp_rent/1`
  - `inuki-ichiba.jp/`
- `target`: `/rent`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "New listings on 居抜き市場，20 per page (first page only). With a prefecture the search results are sorted by 新着順；without one the site's 新着物件 page is used. Each item's `_extra` carries the structured listing fields (賃料，坪，階，最寄駅，敷金・保証金，造作価格，物件タイプ，現業態，飲食条件，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`.\n\n| Query   | Description                                                                  | Default |\n| ------- | ---------------------------------------------------------------------------- | ------- |\n| `limit` | Number of listings to process (detail pages are fetched per listing), max 20 | 20      |",
  "example": "/inuki-ichiba/rent/tokyo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "rent.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "新着物件",
  "parameters": {
    "pref": {
      "description": "都道府県 slug or JIS X 0401 code; omit for the site-wide 新着物件 page (一都三県 mixed)",
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
        }
      ]
    }
  },
  "path": "/rent/:pref?",
  "radar": [
    {
      "source": [
        "inuki-ichiba.jp/sp_rent/1",
        "inuki-ichiba.jp/"
      ],
      "target": "/rent"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [],
  "url": "inuki-ichiba.jp"
}
```
