# 妈咪帮 - 文章

## Coverage
`index-only`

## Route
- Namespace: `mamibuy`
- Namespace Name: `妈咪帮`
- Route Path: `/mamibuy/:caty?`
- Route Name: `文章`
- Example: `/mamibuy`
- URL: `mamibuy.com.hk`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
分類

| 懷孕 | 育兒 | 母乳 | 親子關係 | 家庭生活 | 成長發展 |
| ---- | ---- | ---- | -------- | -------- | -------- |
| 2    | 3    | 4    | 5        | 6        | 7        |

## Parameters
- `caty`: {"description": "分類，默認為全部", "options": [{"label": "懷孕", "value": "2"}, {"label": "育兒", "value": "3"}, {"label": "母乳", "value": "4"}, {"label": "親子關係", "value": "5"}, {"label": "家庭生活", "value": "6"}, {"label": "成長發展", "value": "7"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mamibuy.com.hk/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "分類\n\n| 懷孕 | 育兒 | 母乳 | 親子關係 | 家庭生活 | 成長發展 |\n| ---- | ---- | ---- | -------- | -------- | -------- |\n| 2    | 3    | 4    | 5        | 6        | 7        |",
  "example": "/mamibuy",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章",
  "parameters": {
    "caty": {
      "description": "分類，默認為全部",
      "options": [
        {
          "label": "懷孕",
          "value": "2"
        },
        {
          "label": "育兒",
          "value": "3"
        },
        {
          "label": "母乳",
          "value": "4"
        },
        {
          "label": "親子關係",
          "value": "5"
        },
        {
          "label": "家庭生活",
          "value": "6"
        },
        {
          "label": "成長發展",
          "value": "7"
        }
      ]
    }
  },
  "path": "/:caty?",
  "radar": [
    {
      "source": [
        "mamibuy.com.hk/"
      ]
    }
  ],
  "topFeeds": [],
  "url": "mamibuy.com.hk"
}
```
