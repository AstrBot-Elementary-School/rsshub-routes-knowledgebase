# 中华人民共和国国家发展和改革委员会 - 新闻动态

## Coverage
`index-only`

## Route
- Namespace: `gov/ndrc`
- Namespace Name: `中华人民共和国国家发展和改革委员会`
- Route Path: `/gov/ndrc/xwdt/:category{.+}?`
- Route Name: `新闻动态`
- Example: `/gov/ndrc/xwdt`
- URL: `ndrc.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `xwdt.ts`
- Source Module: `_None_`

## Description
| 新闻发布 | 通知通告 | 委领导动态 | 司局动态 | 地方动态 |
| -------- | -------- | ---------- | -------- | -------- |
| xwfb     | tzgg     | wlddt      | sjdt     | dfdt     |

## Parameters
- `category`: 分类，见下表，默认为新闻发布


## Features
_None_

## Radar
### Rule 1
- `title`: `中华人民共和国国家发展和改革委员会 - 新闻动态`
- `source`:
  - `ndrc.gov.cn/xwdt/:category*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 新闻发布 | 通知通告 | 委领导动态 | 司局动态 | 地方动态 |\n| -------- | -------- | ---------- | -------- | -------- |\n| xwfb     | tzgg     | wlddt      | sjdt     | dfdt     |",
  "example": "/gov/ndrc/xwdt",
  "heat": 1306,
  "location": "xwdt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻动态",
  "parameters": {
    "category": "分类，见下表，默认为新闻发布"
  },
  "path": "/xwdt/:category{.+}?",
  "radar": [
    {
      "source": [
        "ndrc.gov.cn/xwdt/:category*"
      ],
      "title": "中华人民共和国国家发展和改革委员会 - 新闻动态"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "新闻发布-国家发展和改革委员会 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60266822888425476",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ndrc.gov.cn/xwdt/xwfb",
      "title": "新闻发布-国家发展和改革委员会",
      "type": "feed",
      "url": "rsshub://gov/ndrc/xwdt"
    },
    {
      "description": "新闻发布-国家发展和改革委员会 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76948303329996800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ndrc.gov.cn/xwdt/xwfb",
      "title": "新闻发布-国家发展和改革委员会",
      "type": "feed",
      "url": "rsshub://gov/ndrc/xwdt/xwfb"
    }
  ]
}
```
