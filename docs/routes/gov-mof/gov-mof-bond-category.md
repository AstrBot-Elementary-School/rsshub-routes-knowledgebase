# 中华人民共和国财政部 - 专题

## Coverage
`index-only`

## Route
- Namespace: `gov/mof`
- Namespace Name: `中华人民共和国财政部`
- Route Path: `/gov/mof/bond/:category?`
- Route Name: `专题`
- Example: `/gov/mof/bond`
- URL: `www.mof.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `la3rence`
- Source Location: `bond.ts`
- Source Module: `_None_`

## Description
#### 政府债券管理

| 国债管理工作动态 | 记账式国债 (含特别国债) 发行 | 储蓄国债发行 | 地方政府债券管理      |
| ---------------- | ---------------------------- | ------------ | --------------------- |
| gzfxgzdt         | gzfxzjs                      | gzfxdzs      | difangzhengfuzhaiquan |

## Parameters
- `category`: 专题，见下表，默认为国债管理工作动态


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
    "government"
  ],
  "description": "#### 政府债券管理\n\n| 国债管理工作动态 | 记账式国债 (含特别国债) 发行 | 储蓄国债发行 | 地方政府债券管理      |\n| ---------------- | ---------------------------- | ------------ | --------------------- |\n| gzfxgzdt         | gzfxzjs                      | gzfxdzs      | difangzhengfuzhaiquan |",
  "example": "/gov/mof/bond",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 53,
  "location": "bond.ts",
  "maintainers": [
    "la3rence"
  ],
  "name": "专题",
  "parameters": {
    "category": "专题，见下表，默认为国债管理工作动态"
  },
  "path": "/bond/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "国债管理工作动态 - 中华人民共和国财政部 - Powered by RSSHub",
      "errorAt": "2026-02-12T02:46:43.224Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "72200004362793984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gks.mof.gov.cn/ztztz/guozaiguanli/gzfxgzdt/",
      "title": "国债管理工作动态",
      "type": "feed",
      "url": "rsshub://gov/mof/bond"
    },
    {
      "description": "储蓄国债发行 - 中华人民共和国财政部 - Powered by RSSHub",
      "errorAt": "2026-02-12T06:18:06.323Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "100135024449222656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gks.mof.gov.cn/ztztz/guozaiguanli/gzfxdzs/",
      "title": "储蓄国债发行",
      "type": "feed",
      "url": "rsshub://gov/mof/bond/gzfxdzs"
    }
  ]
}
```
