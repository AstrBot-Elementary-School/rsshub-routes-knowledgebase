# 深圳市人民政府 - 市委组织部

## Coverage
`index-only`

## Route
- Namespace: `gov/shenzhen`
- Namespace Name: `深圳市人民政府`
- Route Path: `/gov/shenzhen/zzb/:caty/:page?`
- Route Name: `市委组织部`
- Example: `/gov/shenzhen/zzb/tzgg`
- URL: `zzb.sz.gov.cn/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `zlasd`
- Source Location: `zzb/index.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 任前公示 | 政策法规 | 工作动态 | 部门预算决算公开 | 业务表格下载 |
| :------: | :------: | :------: | :------: | :--------------: | :----------: |
|   tzgg   |   rqgs   |   zcfg   |   gzdt   |       xcbd       |     bgxz     |

## Parameters
- `caty`: 信息类别
- `page`: 历史兼容参数，所有值均返回第 1 页，不翻页


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
  - `www.zzb.sz.gov.cn/notice/announcement`
  - `www.zzb.sz.gov.cn/notice/announcement/index.html`
- `target`: `/zzb/tzgg`
### Rule 2
- `source`:
  - `www.zzb.sz.gov.cn/notice/appointment`
  - `www.zzb.sz.gov.cn/notice/appointment/index.html`
- `target`: `/zzb/rqgs`
### Rule 3
- `source`:
  - `www.zzb.sz.gov.cn/service/policy`
  - `www.zzb.sz.gov.cn/service/policy/index.html`
- `target`: `/zzb/zcfg`
### Rule 4
- `source`:
  - `www.zzb.sz.gov.cn/service/file`
  - `www.zzb.sz.gov.cn/service/file/index.html`
- `target`: `/zzb/bgxz`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 | 任前公示 | 政策法规 | 工作动态 | 部门预算决算公开 | 业务表格下载 |\n| :------: | :------: | :------: | :------: | :--------------: | :----------: |\n|   tzgg   |   rqgs   |   zcfg   |   gzdt   |       xcbd       |     bgxz     |",
  "example": "/gov/shenzhen/zzb/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "zzb/index.ts",
  "maintainers": [
    "zlasd"
  ],
  "name": "市委组织部",
  "parameters": {
    "caty": "信息类别",
    "page": "历史兼容参数，所有值均返回第 1 页，不翻页"
  },
  "path": "/zzb/:caty/:page?",
  "radar": [
    {
      "source": [
        "www.zzb.sz.gov.cn/notice/announcement",
        "www.zzb.sz.gov.cn/notice/announcement/index.html"
      ],
      "target": "/zzb/tzgg"
    },
    {
      "source": [
        "www.zzb.sz.gov.cn/notice/appointment",
        "www.zzb.sz.gov.cn/notice/appointment/index.html"
      ],
      "target": "/zzb/rqgs"
    },
    {
      "source": [
        "www.zzb.sz.gov.cn/service/policy",
        "www.zzb.sz.gov.cn/service/policy/index.html"
      ],
      "target": "/zzb/zcfg"
    },
    {
      "source": [
        "www.zzb.sz.gov.cn/service/file",
        "www.zzb.sz.gov.cn/service/file/index.html"
      ],
      "target": "/zzb/bgxz"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "zzb.sz.gov.cn/*"
}
```
