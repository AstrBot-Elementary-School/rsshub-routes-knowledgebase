# 西安电子科技大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `xidian`
- Namespace Name: `西安电子科技大学`
- Route Path: `/xidian/jwc/:category?`
- Route Name: `教务处`
- Example: `/xidian/jwc/tzgg`
- URL: `jwc.xidian.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ShadowySpirits`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教学信息 | 教学研究 | 实践教学 | 质量监控 | 通知公告 |
| :------: | :------: | :------: | :------: | :------: |
|   jxxx   |   jxyj   |   sjjx   |   zljk   |   tzgg   |

## Parameters
- `category`: 通知类别，默认为通知公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教学信息 | 教学研究 | 实践教学 | 质量监控 | 通知公告 |\n| :------: | :------: | :------: | :------: | :------: |\n|   jxxx   |   jxyj   |   sjjx   |   zljk   |   tzgg   |",
  "example": "/xidian/jwc/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "jwc.ts",
  "maintainers": [
    "ShadowySpirits"
  ],
  "name": "教务处",
  "parameters": {
    "category": "通知类别，默认为通知公告"
  },
  "path": "/jwc/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "通知公告-西安电子科技大学 教务处 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80953491612598272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.xidian.edu.cn/tzgg.htm",
      "title": "通知公告-西安电子科技大学 教务处",
      "type": "feed",
      "url": "rsshub://xidian/jwc"
    },
    {
      "description": "通知公告-西安电子科技大学 教务处 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69997970126835712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.xidian.edu.cn/tzgg.htm",
      "title": "通知公告-西安电子科技大学 教务处",
      "type": "feed",
      "url": "rsshub://xidian/jwc/tzgg"
    }
  ],
  "url": "jwc.xidian.edu.cn"
}
```
