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
- `title`: `新闻发布`
- `source`:
  - `ndrc.gov.cn/xwdt/xwfb/`
  - `ndrc.gov.cn/xwdt/xwfb/*`
- `target`: `/xwdt/xwfb`
### Rule 2
- `title`: `通知通告`
- `source`:
  - `ndrc.gov.cn/xwdt/tzgg/`
  - `ndrc.gov.cn/xwdt/tzgg/*`
- `target`: `/xwdt/tzgg`
### Rule 3
- `title`: `委领导动态`
- `source`:
  - `ndrc.gov.cn/xwdt/dt/wlddt/`
  - `ndrc.gov.cn/xwdt/dt/wlddt/*`
- `target`: `/xwdt/wlddt`
### Rule 4
- `title`: `司局动态`
- `source`:
  - `ndrc.gov.cn/xwdt/dt/sjdt/`
  - `ndrc.gov.cn/xwdt/dt/sjdt/*`
- `target`: `/xwdt/sjdt`
### Rule 5
- `title`: `地方动态`
- `source`:
  - `ndrc.gov.cn/xwdt/dt/dfdt/`
  - `ndrc.gov.cn/xwdt/dt/dfdt/*`
- `target`: `/xwdt/dfdt`

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
        "ndrc.gov.cn/xwdt/xwfb/",
        "ndrc.gov.cn/xwdt/xwfb/*"
      ],
      "target": "/xwdt/xwfb",
      "title": "新闻发布"
    },
    {
      "source": [
        "ndrc.gov.cn/xwdt/tzgg/",
        "ndrc.gov.cn/xwdt/tzgg/*"
      ],
      "target": "/xwdt/tzgg",
      "title": "通知通告"
    },
    {
      "source": [
        "ndrc.gov.cn/xwdt/dt/wlddt/",
        "ndrc.gov.cn/xwdt/dt/wlddt/*"
      ],
      "target": "/xwdt/wlddt",
      "title": "委领导动态"
    },
    {
      "source": [
        "ndrc.gov.cn/xwdt/dt/sjdt/",
        "ndrc.gov.cn/xwdt/dt/sjdt/*"
      ],
      "target": "/xwdt/sjdt",
      "title": "司局动态"
    },
    {
      "source": [
        "ndrc.gov.cn/xwdt/dt/dfdt/",
        "ndrc.gov.cn/xwdt/dt/dfdt/*"
      ],
      "target": "/xwdt/dfdt",
      "title": "地方动态"
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
      "id": "76948303329996800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ndrc.gov.cn/xwdt/xwfb",
      "title": "新闻发布-国家发展和改革委员会",
      "type": "feed",
      "url": "rsshub://gov/ndrc/xwdt/xwfb"
    },
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
    }
  ]
}
```
