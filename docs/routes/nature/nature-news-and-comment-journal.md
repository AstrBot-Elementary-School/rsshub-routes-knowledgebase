# Nature Journal - News & Comment

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/news-and-comment/:journal?`
- Route Name: `News & Comment`
- Example: `/nature/news-and-comment/ng`
- URL: `nature.com/latest-news`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `news-and-comment.ts`
- Source Module: `_None_`

## Description
|   `:journal`  |   Full Name of the Journal  | Route                                                                                              |
| :-----------: | :-------------------------: | -------------------------------------------------------------------------------------------------- |
|      nbt      |     Nature Biotechnology    | [/nature/news-and-comment/nbt](https://rsshub.app/nature/news-and-comment/nbt)                     |
|     neuro     |     Nature Neuroscience     | [/nature/news-and-comment/neuro](https://rsshub.app/nature/news-and-comment/neuro)                 |
|       ng      |       Nature Genetics       | [/nature/news-and-comment/ng](https://rsshub.app/nature/news-and-comment/ng)                       |
|       ni      |      Nature Immunology      | [/nature/news-and-comment/ni](https://rsshub.app/nature/news-and-comment/ni)                       |
|     nmeth     |        Nature Method        | [/nature/news-and-comment/nmeth](https://rsshub.app/nature/news-and-comment/nmeth)                 |
|     nchem     |       Nature Chemistry      | [/nature/news-and-comment/nchem](https://rsshub.app/nature/news-and-comment/nchem)                 |
|      nmat     |       Nature Materials      | [/nature/news-and-comment/nmat](https://rsshub.app/nature/news-and-comment/nmat)                   |
| natmachintell | Nature Machine Intelligence | [/nature/news-and-comment/natmachintell](https://rsshub.app/nature/news-and-comment/natmachintell) |

- Using router (`/nature/research/` + "short name for a journal") to query latest research paper for a certain journal of Nature Publishing Group.
- The journals from NPG are run by different group of people, and the website of may not be consitent for all the journals

## Parameters
- `journal`: short name for a journal


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
  - `nature.com/latest-news`
  - `nature.com/news`
  - `nature.com/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "|   `:journal`  |   Full Name of the Journal  | Route                                                                                              |\n| :-----------: | :-------------------------: | -------------------------------------------------------------------------------------------------- |\n|      nbt      |     Nature Biotechnology    | [/nature/news-and-comment/nbt](https://rsshub.app/nature/news-and-comment/nbt)                     |\n|     neuro     |     Nature Neuroscience     | [/nature/news-and-comment/neuro](https://rsshub.app/nature/news-and-comment/neuro)                 |\n|       ng      |       Nature Genetics       | [/nature/news-and-comment/ng](https://rsshub.app/nature/news-and-comment/ng)                       |\n|       ni      |      Nature Immunology      | [/nature/news-and-comment/ni](https://rsshub.app/nature/news-and-comment/ni)                       |\n|     nmeth     |        Nature Method        | [/nature/news-and-comment/nmeth](https://rsshub.app/nature/news-and-comment/nmeth)                 |\n|     nchem     |       Nature Chemistry      | [/nature/news-and-comment/nchem](https://rsshub.app/nature/news-and-comment/nchem)                 |\n|      nmat     |       Nature Materials      | [/nature/news-and-comment/nmat](https://rsshub.app/nature/news-and-comment/nmat)                   |\n| natmachintell | Nature Machine Intelligence | [/nature/news-and-comment/natmachintell](https://rsshub.app/nature/news-and-comment/natmachintell) |\n\n- Using router (`/nature/research/` + \"short name for a journal\") to query latest research paper for a certain journal of Nature Publishing Group.\n- The journals from NPG are run by different group of people, and the website of may not be consitent for all the journals",
  "example": "/nature/news-and-comment/ng",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 50,
  "location": "news-and-comment.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "News & Comment",
  "parameters": {
    "journal": "short name for a journal"
  },
  "path": "/news-and-comment/:journal?",
  "radar": [
    {
      "source": [
        "nature.com/latest-news",
        "nature.com/news",
        "nature.com/"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": [
    {
      "description": "Read the latest News & Comment articles from Nature Energy - Powered by RSSHub",
      "errorAt": "2026-06-27T11:13:28.185Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "160596099235667968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nenergy/news-and-comment",
      "title": "News & Comment | Nature Energy",
      "type": "feed",
      "url": "rsshub://nature/news-and-comment/nenergy"
    },
    {
      "description": "Read the latest News & Comment articles from Nature Geoscience - Powered by RSSHub",
      "errorAt": "2026-06-19T17:23:36.879Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "160604172723269632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/ngeo/news-and-comment",
      "title": "News & Comment | Nature Geoscience",
      "type": "feed",
      "url": "rsshub://nature/news-and-comment/ngeo"
    }
  ],
  "url": "nature.com/latest-news"
}
```
