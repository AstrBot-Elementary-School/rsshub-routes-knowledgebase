# Nature Journal - Latest Research

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/research/:journal?`
- Route Name: `Latest Research`
- Example: `/nature/research/ng`
- URL: `nature.com`
- Language: `_None_`
- Categories: `journal, popular`
- Maintainers: `y9c, TonyRL, pseudoyu`
- Source Location: `research.ts`
- Source Module: `_None_`

## Description
|   `:journal`  |   Full Name of the Journal  | Route                                                                              |
| :-----------: | :-------------------------: | ---------------------------------------------------------------------------------- |
|     nature    |            Nature           | [/nature/research/nature](https://rsshub.app/nature/research/nature)               |
|      nbt      |     Nature Biotechnology    | [/nature/research/nbt](https://rsshub.app/nature/research/nbt)                     |
|     neuro     |     Nature Neuroscience     | [/nature/research/neuro](https://rsshub.app/nature/research/neuro)                 |
|       ng      |       Nature Genetics       | [/nature/research/ng](https://rsshub.app/nature/research/ng)                       |
|       ni      |      Nature Immunology      | [/nature/research/ni](https://rsshub.app/nature/research/ni)                       |
|     nmeth     |        Nature Method        | [/nature/research/nmeth](https://rsshub.app/nature/research/nmeth)                 |
|     nchem     |       Nature Chemistry      | [/nature/research/nchem](https://rsshub.app/nature/research/nchem)                 |
|      nmat     |       Nature Materials      | [/nature/research/nmat](https://rsshub.app/nature/research/nmat)                   |
| natmachintell | Nature Machine Intelligence | [/nature/research/natmachintell](https://rsshub.app/nature/research/natmachintell) |

- Using router (`/nature/research/` + "short name for a journal") to query latest research paper for a certain journal of Nature Publishing Group.
  If the `:journal` parameter is blank, then latest research of Nature will return.
- The journals from NPG are run by different group of people, and the website of may not be consitent for all the journals
- Only abstract is rendered in some researches

## Parameters
- `journal`: short name for a journal, `nature` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nature.com/:journal/research-articles`
  - `nature.com/:journal`
  - `nature.com/`
- `target`: `/research/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal",
    "popular"
  ],
  "description": "|   `:journal`  |   Full Name of the Journal  | Route                                                                              |\n| :-----------: | :-------------------------: | ---------------------------------------------------------------------------------- |\n|     nature    |            Nature           | [/nature/research/nature](https://rsshub.app/nature/research/nature)               |\n|      nbt      |     Nature Biotechnology    | [/nature/research/nbt](https://rsshub.app/nature/research/nbt)                     |\n|     neuro     |     Nature Neuroscience     | [/nature/research/neuro](https://rsshub.app/nature/research/neuro)                 |\n|       ng      |       Nature Genetics       | [/nature/research/ng](https://rsshub.app/nature/research/ng)                       |\n|       ni      |      Nature Immunology      | [/nature/research/ni](https://rsshub.app/nature/research/ni)                       |\n|     nmeth     |        Nature Method        | [/nature/research/nmeth](https://rsshub.app/nature/research/nmeth)                 |\n|     nchem     |       Nature Chemistry      | [/nature/research/nchem](https://rsshub.app/nature/research/nchem)                 |\n|      nmat     |       Nature Materials      | [/nature/research/nmat](https://rsshub.app/nature/research/nmat)                   |\n| natmachintell | Nature Machine Intelligence | [/nature/research/natmachintell](https://rsshub.app/nature/research/natmachintell) |\n\n- Using router (`/nature/research/` + \"short name for a journal\") to query latest research paper for a certain journal of Nature Publishing Group.\n  If the `:journal` parameter is blank, then latest research of Nature will return.\n- The journals from NPG are run by different group of people, and the website of may not be consitent for all the journals\n- Only abstract is rendered in some researches",
  "example": "/nature/research/ng",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 43841,
  "location": "research.ts",
  "maintainers": [
    "y9c",
    "TonyRL",
    "pseudoyu"
  ],
  "name": "Latest Research",
  "parameters": {
    "journal": "short name for a journal, `nature` by default"
  },
  "path": "/research/:journal?",
  "radar": [
    {
      "source": [
        "nature.com/:journal/research-articles",
        "nature.com/:journal",
        "nature.com/"
      ],
      "target": "/research/:journal"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Read the latest Research articles from Nature - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73606009950742535",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nature/research-articles",
      "title": "Nature (Nature) | Latest Research",
      "type": "feed",
      "url": "rsshub://nature/research/nature"
    },
    {
      "description": "Read the latest Research articles from Nature - Powered by RSSHub",
      "errorAt": "2026-06-20T04:13:11.899Z",
      "errorMessage": "Cannot read properties of null (reading '1')\n502 \nAuthentication failed. Access denied.\n/nature/research\nCannot read properties of null (reading '1')\n",
      "id": "79390237537101824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nature/research-articles",
      "title": "Nature (Nature) | Latest Research",
      "type": "feed",
      "url": "rsshub://nature/research"
    }
  ]
}
```
