# Huggingface - Daily Papers

## Coverage
`index-only`

## Route
- Namespace: `huggingface`
- Namespace Name: `Huggingface`
- Route Path: `/huggingface/daily-papers/:cycle?/:voteFliter?`
- Route Name: `Daily Papers`
- Example: `/huggingface/daily-papers/week/50`
- URL: `huggingface.co/papers`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zeyugao, ovo-tim`
- Source Location: `daily-papers.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cycle`: The publication cycle you want to follow. Choose from: date, week, month. Default: date
- `voteFliter`: Filter papers by vote count.


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
  - `huggingface.co/papers/:cycle`
- `target`: `/daily-papers/:cycle`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/huggingface/daily-papers/week/50",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1064,
  "location": "daily-papers.ts",
  "maintainers": [
    "zeyugao",
    "ovo-tim"
  ],
  "name": "Daily Papers",
  "parameters": {
    "cycle": "The publication cycle you want to follow. Choose from: date, week, month. Default: date",
    "voteFliter": "Filter papers by vote count."
  },
  "path": "/daily-papers/:cycle?/:voteFliter?",
  "radar": [
    {
      "source": [
        "huggingface.co/papers/:cycle"
      ],
      "target": "/daily-papers/:cycle"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Huggingface Daily Papers - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41359648680482832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://huggingface.co/papers",
      "title": "Huggingface Daily Papers",
      "type": "feed",
      "url": "rsshub://huggingface/daily-papers"
    },
    {
      "description": "Huggingface Daily Papers - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "182620255922244608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://huggingface.co/papers",
      "title": "Huggingface Daily Papers",
      "type": "feed",
      "url": "rsshub://huggingface/daily-papers/week/50"
    }
  ],
  "url": "huggingface.co/papers"
}
```
