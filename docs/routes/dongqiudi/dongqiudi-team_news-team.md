# 懂球帝 - 球队新闻

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/dongqiudi/team_news/:team`
- Route Name: `球队新闻`
- Example: `/dongqiudi/team_news/50001755`
- URL: `m.dongqiudi.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `HenryQW`
- Source Location: `team-news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `team`: 球队 id, 可在[懂球帝数据](https://www.dongqiudi.com/data)中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dongqiudi.com/team/*team`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/dongqiudi/team_news/50001755",
  "heat": 217,
  "location": "team-news.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "球队新闻",
  "parameters": {
    "team": "球队 id, 可在[懂球帝数据](https://www.dongqiudi.com/data)中找到"
  },
  "path": "/team_news/:team",
  "radar": [
    {
      "source": [
        "www.dongqiudi.com/team/*team"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "曼联 - 相关新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60882001172427787",
      "image": "https://sd.qunliao.info/fastdfs3/M00/B5/75/ChOxM1xC2FWAK5dCAAAmr0XTTPA012.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dongqiudi.com/team/50000515.html",
      "title": "曼联 - 相关新闻",
      "type": "feed",
      "url": "rsshub://dongqiudi/team_news/50000515"
    },
    {
      "description": "阿森纳 - 相关新闻 - Powered by RSSHub",
      "errorAt": "2026-08-05T05:42:10.830Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "73340530520921095",
      "image": "https://sd.qunliao.info/fastdfs5/M00/04/C8/rB8BO15q_yaAdgetAABZZa53gBI322.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dongqiudi.com/team/50000513.html",
      "title": "阿森纳 - 相关新闻",
      "type": "feed",
      "url": "rsshub://dongqiudi/team_news/50000513"
    }
  ]
}
```
