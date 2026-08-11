# 重庆市人民政府 - 人力社保局 - 事业单位公开招聘

## Coverage
`index-only`

## Route
- Namespace: `gov/chongqing`
- Namespace Name: `重庆市人民政府`
- Route Path: `/gov/chongqing/sydwgkzp/:year?`
- Route Name: `人力社保局 - 事业单位公开招聘`
- Example: `/gov/chongqing/sydwgkzp`
- URL: `rlsbj.cq.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `MajexH`
- Source Location: `sydwgkzp.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `year`: 需要订阅的年份，格式为`YYYY`，必须小于等于当前年份，默认为当前年份


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rlsbj.cq.gov.cn/`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/chongqing/sydwgkzp",
  "heat": 8,
  "location": "sydwgkzp.ts",
  "maintainers": [
    "MajexH"
  ],
  "name": "人力社保局 - 事业单位公开招聘",
  "parameters": {
    "year": "需要订阅的年份，格式为`YYYY`，必须小于等于当前年份，默认为当前年份"
  },
  "path": "/sydwgkzp/:year?",
  "radar": [
    {
      "source": [
        "rlsbj.cq.gov.cn/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "重庆市事业单位2026年公开招聘 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56020776125420544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rlsbj.cq.gov.cn/zwxx_182/sydw/sydwgkzp2026/",
      "title": "重庆市事业单位2026年公开招聘",
      "type": "feed",
      "url": "rsshub://gov/chongqing/sydwgkzp"
    }
  ],
  "url": "rlsbj.cq.gov.cn/"
}
```
