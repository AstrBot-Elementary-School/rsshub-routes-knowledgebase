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
  - `nature.com/`
- `target`: `/research/:journal?`

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
  "heat": 55646,
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
        "nature.com/"
      ],
      "target": "/research/:journal?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Read the latest Research articles from Nature - Powered by RSSHub",
      "errorAt": "2026-10-14T15:31:18.338Z",
      "errorMessage": "[GET] \"https://www.nature.com/articles/s41586-026-11242-8\": 404 \n[GET] \"https://www.nature.com/articles/s41586-026-11242-8\": 404 Not Found\n",
      "id": "79390237537101824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nature/research-articles",
      "title": "Nature (Nature) | Latest Research",
      "type": "feed",
      "url": "rsshub://nature/research"
    },
    {
      "description": "Read the latest Research articles from Nature - Powered by RSSHub",
      "errorAt": "2026-10-14T15:41:22.795Z",
      "errorMessage": "[GET] \"https://www.nature.com/articles/s41586-026-11158-3\": 404 Not Found\nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11242-8\": 404 Not Found\n[GET] \"https://www.nature.com/articles/s41586-026-11242-8\": 404 \nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11242-8\": 404 Not Found\n[GET] \"https://www.nature.com/articles/s41586-026-11242-8\": 404 Not Found\nCannot read properties of null (reading '1')\nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11242-8\": 404 Not Found\n[GET] \"https://www.nature.com/articles/s41586-026-11242-8\": 404 \n[GET] \"https://www.nature.com/articles/s41586-026-11242-8\": 404 Not Found\nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11158-3\": 404 Not Found\nMISCONF Redis is configured to save RDB snapshots, but it's currently unable to persist to disk. Commands that may modify the data set are disabled, because this instance is configured to report errors during writes if RDB snapshotting fails (stop-writes-on-bgsave-error option). Please check the Redis logs for details about the RDB error.\n[GET] \"https://www.nature.com/articles/s41586-026-11109-y\": 404 \n[GET] \"https://www.nature.com/articles/s41586-026-11162-7\": 404 \nCannot read properties of null (reading '1')\nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11162-7\": 404 \nCannot read properties of null (reading '1')\nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11158-3\": 404 Not Found\nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11162-7\": 404 \n[GET] \"https://www.nature.com/articles/s41586-026-11158-3\": 404 Not Found\nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11158-3\": 404 \nCannot read properties of null (reading '1')\nCannot read properties of null (reading '1')\nFailed to fetch\nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11162-7\": 404 \n[GET] \"https://www.nature.com/articles/s41586-026-11162-7\": 404 \nCannot read properties of null (reading '1')\n[GET] \"https://www.nature.com/articles/s41586-026-11162-7\": 404 Not Found\n",
      "id": "73606009950742535",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nature/research-articles",
      "title": "Nature (Nature) | Latest Research",
      "type": "feed",
      "url": "rsshub://nature/research/nature"
    }
  ]
}
```
