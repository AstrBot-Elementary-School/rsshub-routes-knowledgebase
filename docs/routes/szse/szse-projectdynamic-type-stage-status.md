# 深圳证券交易所 - 创业板项目动态

## Coverage
`index-only`

## Route
- Namespace: `szse`
- Namespace Name: `深圳证券交易所`
- Route Path: `/szse/projectdynamic/:type?/:stage?/:status?`
- Route Name: `创业板项目动态`
- Example: `/szse/projectdynamic`
- URL: `listing.szse.cn/projectdynamic/1/index.html`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `projectdynamic.tsx`
- Source Module: `_None_`

## Description
类型

| IPO | 再融资 | 重大资产重组 |
| --- | ------ | ------------ |
| 1   | 2      | 3            |

阶段

| 全部 | 受理 | 问询 | 上市委会议 |
| ---- | ---- | ---- | ---------- |
| 0    | 10   | 20   | 30         |

| 提交注册 | 注册结果 | 中止 | 终止 |
| -------- | -------- | ---- | ---- |
| 35       | 40       | 50   | 60   |

状态

| 全部 | 新受理 | 已问询 | 通过 | 未通过 |
| ---- | ------ | ------ | ---- | ------ |
| 0    | 20     | 30     | 45   | 44     |

| 暂缓审议 | 复审通过 | 复审不通过 | 提交注册 |
| -------- | -------- | ---------- | -------- |
| 46       | 56       | 54         | 60       |

| 注册生效 | 不予注册 | 补充审核 | 终止注册 |
| -------- | -------- | -------- | -------- |
| 70       | 74       | 78       | 76       |

| 中止 | 审核不通过 | 撤回 |
| ---- | ---------- | ---- |
| 80   | 90         | 95   |

## Parameters
- `type`: 类型，见下表，默认为IPO
- `stage`: 阶段，见下表，默认为全部
- `status`: 状态，见下表，默认为全部


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
  - `listing.szse.cn/projectdynamic/1/index.html`
  - `listing.szse.cn/projectdynamic/2/index.html`
  - `listing.szse.cn/projectdynamic/3/index.html`
  - `listing.szse.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "类型\n\n| IPO | 再融资 | 重大资产重组 |\n| --- | ------ | ------------ |\n| 1   | 2      | 3            |\n\n阶段\n\n| 全部 | 受理 | 问询 | 上市委会议 |\n| ---- | ---- | ---- | ---------- |\n| 0    | 10   | 20   | 30         |\n\n| 提交注册 | 注册结果 | 中止 | 终止 |\n| -------- | -------- | ---- | ---- |\n| 35       | 40       | 50   | 60   |\n\n状态\n\n| 全部 | 新受理 | 已问询 | 通过 | 未通过 |\n| ---- | ------ | ------ | ---- | ------ |\n| 0    | 20     | 30     | 45   | 44     |\n\n| 暂缓审议 | 复审通过 | 复审不通过 | 提交注册 |\n| -------- | -------- | ---------- | -------- |\n| 46       | 56       | 54         | 60       |\n\n| 注册生效 | 不予注册 | 补充审核 | 终止注册 |\n| -------- | -------- | -------- | -------- |\n| 70       | 74       | 78       | 76       |\n\n| 中止 | 审核不通过 | 撤回 |\n| ---- | ---------- | ---- |\n| 80   | 90         | 95   |",
  "example": "/szse/projectdynamic",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "projectdynamic.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "创业板项目动态",
  "parameters": {
    "stage": "阶段，见下表，默认为全部",
    "status": "状态，见下表，默认为全部",
    "type": "类型，见下表，默认为IPO"
  },
  "path": "/projectdynamic/:type?/:stage?/:status?",
  "radar": [
    {
      "source": [
        "listing.szse.cn/projectdynamic/1/index.html",
        "listing.szse.cn/projectdynamic/2/index.html",
        "listing.szse.cn/projectdynamic/3/index.html",
        "listing.szse.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "IPO项目动态 - 创业板发行上市审核信息公开网站 - 深圳证券交易所 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64720907966178304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://listing.szse.cn/projectdynamic/1/index.html",
      "title": "IPO项目动态 - 创业板发行上市审核信息公开网站 - 深圳证券交易所",
      "type": "feed",
      "url": "rsshub://szse/projectdynamic"
    }
  ],
  "url": "listing.szse.cn/projectdynamic/1/index.html"
}
```
