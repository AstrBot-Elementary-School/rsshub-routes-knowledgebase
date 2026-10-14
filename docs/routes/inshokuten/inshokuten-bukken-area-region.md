# Inshokuten.com - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `inshokuten`
- Namespace Name: `Inshokuten.com`
- Route Path: `/inshokuten/bukken/:area?/:region?`
- Route Name: `新着物件`
- Example: `/inshokuten/bukken/23ward`
- URL: `www.inshokuten.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `bukken.ts`
- Source Module: `_None_`

## Description
New restaurant-property listings on 飲食店.COM sorted by 登録日 (first page, 20 listings) — for a whole area, or for one 区市 when `region` is given. Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，造作譲渡料，現況，前業態，出店可能業態，登録日，…); unknown values are `null`. 保証金 and 礼金 are members-only on the site and therefore always `null`.

`region` is 飲食店.COM's own numeric 区市 id, **not** a JIS code, and applies only to the `local-*` sub-areas — `/inshokuten/bukken/23ward/7` is 新宿区 and `/inshokuten/bukken/yokohama_kawasaki/63` is 横浜市中区。東京 23 区 runs 1–23 and 横浜・川崎 runs 51–72; the site answers an unknown id with a 404, so a wrong value fails loudly instead of silently returning the parent area.

## Parameters
- `area`: {"default": "kanto", "description": "Region or 首都圏 sub-area", "options": [{"label": "首都圏", "value": "kanto"}, {"label": "東京23区", "value": "23ward"}, {"label": "東京都下", "value": "23ward_out"}, {"label": "神奈川", "value": "yokohama_kawasaki"}, {"label": "千葉", "value": "chiba"}, {"label": "埼玉", "value": "saitama"}, {"label": "関西", "value": "kansai"}, {"label": "東海", "value": "tokai"}, {"label": "九州", "value": "kyushu"}]}
- `region`: {"description": "Optional 区市, as 飲食店.COM's own numeric id — **not** a JIS code (新宿区 `7`, 港区 `4`, 横浜市中区 `63`). Only valid for the `local-*` sub-areas (`23ward`, `23ward_out`, `yokohama_kawasaki`, `chiba`, `saitama`); omit for the whole area."}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.inshokuten.com/bukken/kanto/bukkens/list`
- `target`: `/bukken/kanto`
### Rule 2
- `source`:
  - `www.inshokuten.com/bukken/kanto/bukkens/list/local-23ward`
- `target`: `/bukken/23ward`
### Rule 3
- `source`:
  - `www.inshokuten.com/bukken/kanto/bukkens/list/local-23ward_out`
- `target`: `/bukken/23ward_out`
### Rule 4
- `source`:
  - `www.inshokuten.com/bukken/kanto/bukkens/list/local-yokohama_kawasaki`
- `target`: `/bukken/yokohama_kawasaki`
### Rule 5
- `source`:
  - `www.inshokuten.com/bukken/kanto/bukkens/list/local-chiba`
- `target`: `/bukken/chiba`
### Rule 6
- `source`:
  - `www.inshokuten.com/bukken/kanto/bukkens/list/local-saitama`
- `target`: `/bukken/saitama`
### Rule 7
- `source`:
  - `www.inshokuten.com/bukken/kansai/bukkens/list`
- `target`: `/bukken/kansai`
### Rule 8
- `source`:
  - `www.inshokuten.com/bukken/tokai/bukkens/list`
- `target`: `/bukken/tokai`
### Rule 9
- `source`:
  - `www.inshokuten.com/bukken/kyushu/bukkens/list`
- `target`: `/bukken/kyushu`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "New restaurant-property listings on 飲食店.COM sorted by 登録日 (first page, 20 listings) — for a whole area, or for one 区市 when `region` is given. Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，造作譲渡料，現況，前業態，出店可能業態，登録日，…); unknown values are `null`. 保証金 and 礼金 are members-only on the site and therefore always `null`.\n\n`region` is 飲食店.COM's own numeric 区市 id, **not** a JIS code, and applies only to the `local-*` sub-areas — `/inshokuten/bukken/23ward/7` is 新宿区 and `/inshokuten/bukken/yokohama_kawasaki/63` is 横浜市中区。東京 23 区 runs 1–23 and 横浜・川崎 runs 51–72; the site answers an unknown id with a 404, so a wrong value fails loudly instead of silently returning the parent area.",
  "example": "/inshokuten/bukken/23ward",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "bukken.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "新着物件",
  "parameters": {
    "area": {
      "default": "kanto",
      "description": "Region or 首都圏 sub-area",
      "options": [
        {
          "label": "首都圏",
          "value": "kanto"
        },
        {
          "label": "東京23区",
          "value": "23ward"
        },
        {
          "label": "東京都下",
          "value": "23ward_out"
        },
        {
          "label": "神奈川",
          "value": "yokohama_kawasaki"
        },
        {
          "label": "千葉",
          "value": "chiba"
        },
        {
          "label": "埼玉",
          "value": "saitama"
        },
        {
          "label": "関西",
          "value": "kansai"
        },
        {
          "label": "東海",
          "value": "tokai"
        },
        {
          "label": "九州",
          "value": "kyushu"
        }
      ]
    },
    "region": {
      "description": "Optional 区市, as 飲食店.COM's own numeric id — **not** a JIS code (新宿区 `7`, 港区 `4`, 横浜市中区 `63`). Only valid for the `local-*` sub-areas (`23ward`, `23ward_out`, `yokohama_kawasaki`, `chiba`, `saitama`); omit for the whole area."
    }
  },
  "path": "/bukken/:area?/:region?",
  "radar": [
    {
      "source": [
        "www.inshokuten.com/bukken/kanto/bukkens/list"
      ],
      "target": "/bukken/kanto"
    },
    {
      "source": [
        "www.inshokuten.com/bukken/kanto/bukkens/list/local-23ward"
      ],
      "target": "/bukken/23ward"
    },
    {
      "source": [
        "www.inshokuten.com/bukken/kanto/bukkens/list/local-23ward_out"
      ],
      "target": "/bukken/23ward_out"
    },
    {
      "source": [
        "www.inshokuten.com/bukken/kanto/bukkens/list/local-yokohama_kawasaki"
      ],
      "target": "/bukken/yokohama_kawasaki"
    },
    {
      "source": [
        "www.inshokuten.com/bukken/kanto/bukkens/list/local-chiba"
      ],
      "target": "/bukken/chiba"
    },
    {
      "source": [
        "www.inshokuten.com/bukken/kanto/bukkens/list/local-saitama"
      ],
      "target": "/bukken/saitama"
    },
    {
      "source": [
        "www.inshokuten.com/bukken/kansai/bukkens/list"
      ],
      "target": "/bukken/kansai"
    },
    {
      "source": [
        "www.inshokuten.com/bukken/tokai/bukkens/list"
      ],
      "target": "/bukken/tokai"
    },
    {
      "source": [
        "www.inshokuten.com/bukken/kyushu/bukkens/list"
      ],
      "target": "/bukken/kyushu"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.inshokuten.com"
}
```
