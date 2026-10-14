# Civitai - Model discussions

## Coverage
`index-only`

## Route
- Namespace: `civitai`
- Namespace Name: `Civitai`
- Route Path: `/civitai/discussions/:modelId`
- Route Name: `Model discussions`
- Example: `/civitai/discussions/4384`
- URL: `civitai.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `discussions.ts`
- Source Module: `_None_`

## Description
::: warning
Need to configure `CIVITAI_COOKIE` to obtain image information of NSFW models.
:::

## Parameters
- `modelId`: N


## Features
- `requireConfig`: [{"description": "", "name": "CIVITAI_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `civitai.com/models/:modelId`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: warning\nNeed to configure `CIVITAI_COOKIE` to obtain image information of NSFW models.\n:::",
  "example": "/civitai/discussions/4384",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "CIVITAI_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "discussions.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Model discussions",
  "parameters": {
    "modelId": "N"
  },
  "path": "/discussions/:modelId",
  "radar": [
    {
      "source": [
        "civitai.com/models/:modelId"
      ]
    }
  ],
  "topFeeds": []
}
```
