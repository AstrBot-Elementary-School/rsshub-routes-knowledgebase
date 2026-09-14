# Bukenavi - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `bukenavi`
- Namespace Name: `Bukenavi`
- Route Path: `/bukenavi/object/:region?/:pref?`
- Route Name: `新着物件`
- Example: `/bukenavi/object/kanto/tokyo`
- URL: `bukenavi.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `object.ts`
- Source Module: `_None_`

## Description
New 居抜き listings on ぶけなび that are currently 募集中，newest first (first page, 10 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，前業態，業種制限，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`.

## Parameters
- `region`: {"default": "kanto", "description": "Region", "options": [{"label": "関東", "value": "kanto"}, {"label": "関西", "value": "kansai"}, {"label": "東海", "value": "tokai"}]}
- `pref`: Prefecture slug (tokyo, kanagawa, saitama, chiba, osaka, kyoto, hyogo, aichi) or two-digit JIS X 0401 code; omit for the whole region


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `bukenavi.jp/:region/object/list`
  - `bukenavi.jp/:region`
- `target`: `/object/:region`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "New 居抜き listings on ぶけなび that are currently 募集中，newest first (first page, 10 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，前業態，業種制限，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`.",
  "example": "/bukenavi/object/kanto/tokyo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "object.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "新着物件",
  "parameters": {
    "pref": "Prefecture slug (tokyo, kanagawa, saitama, chiba, osaka, kyoto, hyogo, aichi) or two-digit JIS X 0401 code; omit for the whole region",
    "region": {
      "default": "kanto",
      "description": "Region",
      "options": [
        {
          "label": "関東",
          "value": "kanto"
        },
        {
          "label": "関西",
          "value": "kansai"
        },
        {
          "label": "東海",
          "value": "tokai"
        }
      ]
    }
  },
  "path": "/object/:region?/:pref?",
  "radar": [
    {
      "source": [
        "bukenavi.jp/:region/object/list",
        "bukenavi.jp/:region"
      ],
      "target": "/object/:region"
    }
  ],
  "topFeeds": [],
  "url": "bukenavi.jp"
}
```
