# BioOne - Journals

## Coverage
`index-only`

## Route
- Namespace: `bioone`
- Namespace Name: `BioOne`
- Route Path: `/bioone/journals/:journal?`
- Route Name: `Journals`
- Example: `/bioone/journals/acta-chiropterologica`
- URL: `bioone.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `journal.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `journal`: Journals, can be found in URL


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
  - `bioone.org/journals/:journal`
  - `bioone.org/`
- `target`: `/journals/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/bioone/journals/acta-chiropterologica",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "journal.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Journals",
  "parameters": {
    "journal": "Journals, can be found in URL"
  },
  "path": "/journals/:journal?",
  "radar": [
    {
      "source": [
        "bioone.org/journals/:journal",
        "bioone.org/"
      ],
      "target": "/journals/:journal"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "VOL. 45 · NO. 1 | April 2026 - Powered by RSSHub",
      "errorAt": "2026-06-11T16:28:06.225Z",
      "errorMessage": "Failed to fetch\n",
      "id": "72828126275162112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bioone.org/journals/journal-of-shellfish-research/current",
      "title": "Journal of Shellfish Research - BioOne",
      "type": "feed",
      "url": "rsshub://bioone/journals/journal-of-shellfish-research"
    },
    {
      "description": "VOL. 27 · NO. 1 | June 2025 - Powered by RSSHub",
      "errorAt": "2025-10-28T14:39:56.921Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "199614407438218240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bioone.org/journals/acta-chiropterologica/current",
      "title": "Acta Chiropterologica - BioOne",
      "type": "feed",
      "url": "rsshub://bioone/journals"
    }
  ]
}
```
