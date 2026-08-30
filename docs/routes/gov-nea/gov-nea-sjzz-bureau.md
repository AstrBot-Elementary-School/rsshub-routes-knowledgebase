# 国家能源局 - 司工作进展

## Coverage
`index-only`

## Route
- Namespace: `gov/nea`
- Namespace Name: `国家能源局`
- Route Path: `/gov/nea/sjzz/:bureau`
- Route Name: `司工作进展`
- Example: `/gov/nea/sjzz/ghs`
- URL: `www.nea.gov.cn/`
- Language: `_None_`
- Categories: `government, popular`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `bureau.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `bureau`: {"description": "司局", "options": [{"label": "综合司", "value": "zhs"}, {"label": "法改司", "value": "fgs"}, {"label": "规划司", "value": "ghs"}, {"label": "科技司", "value": "kjs"}, {"label": "电力司", "value": "dls"}, {"label": "核电司", "value": "hds"}, {"label": "煤炭司", "value": "mts"}, {"label": "油气司", "value": "yqs"}, {"label": "新能源司", "value": "xny"}, {"label": "监管司", "value": "jgs"}, {"label": "安全司", "value": "aqs"}, {"label": "国际司", "value": "gjs"}, {"label": "机关党委（人事司）", "value": "jgdw"}]}


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
  - `nea.gov.cn/sjzz/:bureau/index.htm`
- `target`: `/sjzz/:bureau`

## Raw JSON
```json
{
  "categories": [
    "government",
    "popular"
  ],
  "example": "/gov/nea/sjzz/ghs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1443,
  "location": "bureau.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "司工作进展",
  "parameters": {
    "bureau": {
      "description": "司局",
      "options": [
        {
          "label": "综合司",
          "value": "zhs"
        },
        {
          "label": "法改司",
          "value": "fgs"
        },
        {
          "label": "规划司",
          "value": "ghs"
        },
        {
          "label": "科技司",
          "value": "kjs"
        },
        {
          "label": "电力司",
          "value": "dls"
        },
        {
          "label": "核电司",
          "value": "hds"
        },
        {
          "label": "煤炭司",
          "value": "mts"
        },
        {
          "label": "油气司",
          "value": "yqs"
        },
        {
          "label": "新能源司",
          "value": "xny"
        },
        {
          "label": "监管司",
          "value": "jgs"
        },
        {
          "label": "安全司",
          "value": "aqs"
        },
        {
          "label": "国际司",
          "value": "gjs"
        },
        {
          "label": "机关党委（人事司）",
          "value": "jgdw"
        }
      ]
    }
  },
  "path": "/sjzz/:bureau",
  "radar": [
    {
      "source": [
        "nea.gov.cn/sjzz/:bureau/index.htm"
      ],
      "target": "/sjzz/:bureau"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "国家能源局 - 发展规划司工作进展 - Powered by RSSHub",
      "errorAt": "2025-09-12T15:00:21.335Z",
      "errorMessage": "200 ",
      "id": "61217794276645888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nea.gov.cn/sjzz/ghs/",
      "title": "国家能源局 - 发展规划司工作进展",
      "type": "feed",
      "url": "rsshub://gov/nea/sjzz/ghs"
    }
  ],
  "url": "www.nea.gov.cn/"
}
```
