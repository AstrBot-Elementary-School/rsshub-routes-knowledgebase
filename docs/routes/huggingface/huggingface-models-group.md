# Huggingface - Group Models

## Coverage
`index-only`

## Route
- Namespace: `huggingface`
- Namespace Name: `Huggingface`
- Route Path: `/huggingface/models/:group`
- Route Name: `Group Models`
- Example: `/huggingface/models/deepseek-ai`
- URL: `huggingface.co`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `WuNein`
- Source Location: `models.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `group`: The organization or user group name


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
  - `huggingface.co/:group/models`
- `target`: `/models/:group`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/huggingface/models/deepseek-ai",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 27,
  "location": "models.ts",
  "maintainers": [
    "WuNein"
  ],
  "name": "Group Models",
  "parameters": {
    "group": "The organization or user group name"
  },
  "path": "/models/:group",
  "radar": [
    {
      "source": [
        "huggingface.co/:group/models"
      ],
      "target": "/models/:group"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Huggingface zai-org Models - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "239230213876544512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://huggingface.co/zai-org/models?sort=created",
      "title": "Huggingface zai-org Models",
      "type": "feed",
      "url": "rsshub://huggingface/models/zai-org"
    },
    {
      "description": "Huggingface deepseek-ai Models - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "220819952297147392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://huggingface.co/deepseek-ai/models?sort=created",
      "title": "Huggingface deepseek-ai Models",
      "type": "feed",
      "url": "rsshub://huggingface/models/deepseek-ai"
    }
  ],
  "url": "huggingface.co"
}
```
