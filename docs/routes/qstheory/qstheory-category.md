# 求是网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `qstheory`
- Namespace Name: `求是网`
- Route Path: `/qstheory/:category?`
- Route Name: `分类`
- Example: `/qstheory`
- URL: `www.qstheory.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 头条    | 网评 | 视频 | 原创   | 经济    | 政治     | 文化    | 社会    | 党建 | 科教    | 生态    | 国防    | 国际          | 图书  | 学习笔记 | 理论文选 |
| ------- | ---- | ---- | ------ | ------- | -------- | ------- | ------- | ---- | ------- | ------- | ------- | ------------- | ----- | -------- | -------- |
| toutiao | qswp | qssp | qslgxd | economy | politics | culture | society | cpc  | science | zoology | defense | international | books | xxbj     | llwx     |

## Parameters
- `industry`: 分类，见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.qstheory.cn/v9zhuanqu/:category/index.htm`
  - `www.qstheory.cn/qszq/:category/index.htm`
  - `www.qstheory.cn/:category/index.htm`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 头条    | 网评 | 视频 | 原创   | 经济    | 政治     | 文化    | 社会    | 党建 | 科教    | 生态    | 国防    | 国际          | 图书  | 学习笔记 | 理论文选 |\n| ------- | ---- | ---- | ------ | ------- | -------- | ------- | ------- | ---- | ------- | ------- | ------- | ------------- | ----- | -------- | -------- |\n| toutiao | qswp | qssp | qslgxd | economy | politics | culture | society | cpc  | science | zoology | defense | international | books | xxbj     | llwx     |",
  "example": "/qstheory",
  "heat": 64,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "industry": "分类，见下表"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.qstheory.cn/v9zhuanqu/:category/index.htm",
        "www.qstheory.cn/qszq/:category/index.htm",
        "www.qstheory.cn/:category/index.htm"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "- 求是网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80832914000440320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.qstheory.cn/v9zhuanqu/toutiao/index.htm",
      "title": "- 求是网",
      "type": "feed",
      "url": "rsshub://qstheory"
    },
    {
      "description": "- 求是网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81625152130833408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.qstheory.cn/v9zhuanqu/toutiao/index.htm",
      "title": "- 求是网",
      "type": "feed",
      "url": "rsshub://qstheory/toutiao"
    }
  ]
}
```
