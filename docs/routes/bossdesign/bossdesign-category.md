# Boss 设计 - 分类

## Coverage
`index-only`

## Route
- Namespace: `bossdesign`
- Namespace Name: `Boss 设计`
- Route Path: `/bossdesign/:category?`
- Route Name: `分类`
- Example: `/bossdesign`
- URL: `bossdesign.cn`
- Language: `_None_`
- Categories: `design`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Boss 笔记 | 电脑日志        | 素材资源         | 设计师神器      | 设计教程        | 设计资讯            |
| --------- | --------------- | ---------------- | --------------- | --------------- | ------------------- |
| note      | computer-skills | design-resources | design-software | design-tutorial | design\_information |

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，留空为全部


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
    "design"
  ],
  "description": "| Boss 笔记 | 电脑日志        | 素材资源         | 设计师神器      | 设计教程        | 设计资讯            |\n| --------- | --------------- | ---------------- | --------------- | --------------- | ------------------- |\n| note      | computer-skills | design-resources | design-software | design-tutorial | design\\_information |",
  "example": "/bossdesign",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 141,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，留空为全部"
  },
  "path": "/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Boss设计-收集国外设计素材网站的资源平台。专注于收集国外设计素材和国外设计网站，以及超实用的设计师神器，只为设计初学者和设计师提供海量的资源平台。.. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82629451109655552",
      "image": "https://www.bossdesign.cn/wp-content/themes/pinghsu/images/Bossdesign-ico.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.bossdesign.cn/",
      "title": "Boss设计 | 收集国外设计素材网站的资源平台。",
      "type": "feed",
      "url": "rsshub://bossdesign"
    },
    {
      "description": "Boss设计-收集国外设计素材网站的资源平台。专注于收集国外设计素材和国外设计网站，以及超实用的设计师神器，只为设计初学者和设计师提供海量的资源平台。.. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "89541310338965504",
      "image": "https://www.bossdesign.cn/wp-content/themes/pinghsu/images/Bossdesign-ico.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.bossdesign.cn/",
      "title": "Boss设计 | 收集国外设计素材网站的资源平台。",
      "type": "feed",
      "url": "rsshub://bossdesign/:category"
    }
  ]
}
```
