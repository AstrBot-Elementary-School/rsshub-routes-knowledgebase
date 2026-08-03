# 国务院政策文件库 - 最新文件

## Coverage
`index-only`

## Route
- Namespace: `gov/zhengce`
- Namespace Name: `国务院政策文件库`
- Route Path: `/gov/zhengce/wenjian/:pcodeJiguan?`
- Route Name: `最新文件`
- Example: `/gov/zhengce/wenjian`
- URL: `www.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ciaranchen`
- Source Location: `wenjian.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `pcodeJiguan`: 文种分类。国令、国发、国函、国发明电、国办发、国办函、国办发明电、其他


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
  - `www.gov.cn/`
- `target`: `/wenjian`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/zhengce/wenjian",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "wenjian.ts",
  "maintainers": [
    "ciaranchen"
  ],
  "name": "最新文件",
  "parameters": {
    "pcodeJiguan": "文种分类。国令、国发、国函、国发明电、国办发、国办函、国办发明电、其他"
  },
  "path": "/wenjian/:pcodeJiguan?",
  "radar": [
    {
      "source": [
        "www.gov.cn/"
      ],
      "target": "/wenjian"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-15T12:16:26.855Z",
      "errorMessage": "[GET] \"http://sousuo.gov.cn/list.htm?n=20&sort=pubtime&t=paper&pcodeJiguan\": <no response> fetch failed (getaddrinfo EAI_AGAIN sousuo.gov.cn)\n",
      "id": "145767488928582665",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://gov/zhengce/wenjian"
    }
  ],
  "url": "www.gov.cn/"
}
```
