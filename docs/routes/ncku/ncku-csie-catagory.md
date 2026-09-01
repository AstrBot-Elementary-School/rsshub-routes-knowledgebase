# National Cheng Kung University - CSIE News

## Coverage
`index-only`

## Route
- Namespace: `ncku`
- Namespace Name: `National Cheng Kung University`
- Route Path: `/ncku/csie/:catagory?`
- Route Name: `CSIE News`
- Example: `/ncku/csie/normal`
- URL: `www.ncku.edu.tw`
- Language: `_None_`
- Categories: `university`
- Maintainers: `simbafs`
- Source Location: `csie.ts`
- Source Module: `_None_`

## Description
Availible catagories：\_all, normal, bachelorAdmission, masterAdmission, speeches, awards, scholarship, jobs

## Parameters
_None_


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
  - `www.csie.ncku.edu.tw/zh-hant/news/`
- `target`: `/csie/_all`
### Rule 2
- `source`:
  - `www.csie.ncku.edu.tw/zh-hant/news/:catagory`
- `target`: `/csie/:catagory`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "Availible catagories：\\_all, normal, bachelorAdmission, masterAdmission, speeches, awards, scholarship, jobs",
  "example": "/ncku/csie/normal",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "csie.ts",
  "maintainers": [
    "simbafs"
  ],
  "name": "CSIE News",
  "path": "/csie/:catagory?",
  "radar": [
    {
      "source": [
        "www.csie.ncku.edu.tw/zh-hant/news/"
      ],
      "target": "/csie/_all"
    },
    {
      "source": [
        "www.csie.ncku.edu.tw/zh-hant/news/:catagory"
      ],
      "target": "/csie/:catagory"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "成大資訊系公告 - 研究所招生 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71205838842910720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.csie.ncku.edu.tw/zh-hant/news/masterAdmission?page=1",
      "title": "成大資訊系公告 - 研究所招生",
      "type": "feed",
      "url": "rsshub://ncku/csie/masterAdmission"
    },
    {
      "description": "成大資訊系公告 - 全部資訊 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71206036941230080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.csie.ncku.edu.tw/zh-hant/news?page=1",
      "title": "成大資訊系公告 - 全部資訊",
      "type": "feed",
      "url": "rsshub://ncku/csie/_all"
    }
  ]
}
```
