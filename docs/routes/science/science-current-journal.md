# Science Magazine - Current Issue

## Coverage
`index-only`

## Route
- Namespace: `science`
- Namespace Name: `Science Magazine`
- Route Path: `/science/current/:journal?`
- Route Name: `Current Issue`
- Example: `/science/current/science`
- URL: `science.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `current.ts`
- Source Module: `_None_`

## Description
|  Short name |    Full name of the journal    | Route                                                                          |
| :---------: | :----------------------------: | ------------------------------------------------------------------------------ |
|   science   |             Science            | [/science/current/science](https://rsshub.app/science/current/science)         |
|    sciadv   |        Science Advances        | [/science/current/sciadv](https://rsshub.app/science/current/sciadv)           |
|  sciimmunol |       Science Immunology       | [/science/current/sciimmunol](https://rsshub.app/science/current/sciimmunol)   |
| scirobotics |        Science Robotics        | [/science/current/scirobotics](https://rsshub.app/science/current/scirobotics) |
|  signaling  |        Science Signaling       | [/science/current/signaling](https://rsshub.app/science/current/signaling)     |
|     stm     | Science Translational Medicine | [/science/current/stm](https://rsshub.app/science/current/stm)                 |

- Using route (`/science/current/` + "short name for a journal") to get current issue of a journal from AAAS.
- Leaving it empty (`/science/current`) to get update from Science.

## Parameters
- `journal`: Short name for a journal


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `science.org/journal/:journal`
  - `science.org/toc/:journal/current`
- `target`: `/current/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "|  Short name |    Full name of the journal    | Route                                                                          |\n| :---------: | :----------------------------: | ------------------------------------------------------------------------------ |\n|   science   |             Science            | [/science/current/science](https://rsshub.app/science/current/science)         |\n|    sciadv   |        Science Advances        | [/science/current/sciadv](https://rsshub.app/science/current/sciadv)           |\n|  sciimmunol |       Science Immunology       | [/science/current/sciimmunol](https://rsshub.app/science/current/sciimmunol)   |\n| scirobotics |        Science Robotics        | [/science/current/scirobotics](https://rsshub.app/science/current/scirobotics) |\n|  signaling  |        Science Signaling       | [/science/current/signaling](https://rsshub.app/science/current/signaling)     |\n|     stm     | Science Translational Medicine | [/science/current/stm](https://rsshub.app/science/current/stm)                 |\n\n- Using route (`/science/current/` + \"short name for a journal\") to get current issue of a journal from AAAS.\n- Leaving it empty (`/science/current`) to get update from Science.",
  "example": "/science/current/science",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 8,
  "location": "current.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "Current Issue",
  "parameters": {
    "journal": "Short name for a journal"
  },
  "path": "/current/:journal?",
  "radar": [
    {
      "source": [
        "science.org/journal/:journal",
        "science.org/toc/:journal/current"
      ],
      "target": "/current/:journal"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-19T00:56:28.398Z",
      "errorMessage": "[GET] \"https://www.science.org/toc/science/current\": 403 Forbidden\n",
      "id": "191666157347082244",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://science/current/science"
    },
    {
      "description": null,
      "errorAt": "2026-06-30T06:04:23.334Z",
      "errorMessage": "[GET] \"https://www.science.org/toc/sciadv/current\": 403 Forbidden\n",
      "id": "1178645011650969612",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://science/current/sciadv"
    }
  ]
}
```
