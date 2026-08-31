# 艾瑞咨询 - 周度市场观察

## Coverage
`index-only`

## Route
- Namespace: `iresearch`
- Namespace Name: `艾瑞咨询`
- Route Path: `/iresearch/weekly/:id?`
- Route Name: `周度市场观察`
- Example: `/iresearch/weekly`
- URL: `www.iresearch.com.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `weekly.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [家电行业](https://www.iresearch.com.cn/report.shtml?type=3\&classId=1)，其源网址为 `https://www.iresearch.com.cn/report.shtml?type=3&classId=1`，请参考该 URL 指定部分构成参数，此时路由为 [`/iresearch/weekly/家电行业`](https://rsshub.app/iresearch/weekly/家电行业) 或 [`/iresearch/weekly/1`](https://rsshub.app/iresearch/weekly/1)。
:::

| 名称                                                                        | ID                                           |
| --------------------------------------------------------------------------- | -------------------------------------------- |
| [家电行业](https://www.iresearch.com.cn/report.shtml?type=3\&classId=1)     | [1](https://rsshub.app/iresearch/report/3/1) |
| [服装行业](https://www.iresearch.com.cn/report.shtml?type=3\&classId=2)     | [2](https://rsshub.app/iresearch/report/3/2) |
| [美妆行业](https://www.iresearch.com.cn/report.shtml?type=3\&classId=3)     | [3](https://rsshub.app/iresearch/report/3/3) |
| [食品饮料行业](https://www.iresearch.com.cn/report.shtml?type=3\&classId=4) | [4](https://rsshub.app/iresearch/report/3/4) |
| [酒行业](https://www.iresearch.com.cn/report.shtml?type=3\&classId=5)       | [5](https://rsshub.app/iresearch/report/3/5) |

## Parameters
- `id`: {"description": "行业 ID，默认为全部，即全部行业，可在对应行业页 URL 中找到", "options": [{"label": "全部", "value": ""}, {"label": "家电行业", "value": "1"}, {"label": "服装行业", "value": "2"}, {"label": "美妆行业", "value": "3"}, {"label": "食品饮料行业", "value": "4"}, {"label": "酒行业", "value": "5"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.iresearch.com.cn/report.shtml`
### Rule 2
- `title`: `家电行业`
- `source`:
  - `www.iresearch.com.cn/report.shtml`
- `target`: `/weekly/1`
### Rule 3
- `title`: `服装行业`
- `source`:
  - `www.iresearch.com.cn/report.shtml`
- `target`: `/weekly/2`
### Rule 4
- `title`: `美妆行业`
- `source`:
  - `www.iresearch.com.cn/report.shtml`
- `target`: `/weekly/3`
### Rule 5
- `title`: `食品饮料行业`
- `source`:
  - `www.iresearch.com.cn/report.shtml`
- `target`: `/weekly/4`
### Rule 6
- `title`: `酒行业`
- `source`:
  - `www.iresearch.com.cn/report.shtml`
- `target`: `/weekly/5`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\n订阅 [家电行业](https://www.iresearch.com.cn/report.shtml?type=3\\&classId=1)，其源网址为 `https://www.iresearch.com.cn/report.shtml?type=3&classId=1`，请参考该 URL 指定部分构成参数，此时路由为 [`/iresearch/weekly/家电行业`](https://rsshub.app/iresearch/weekly/家电行业) 或 [`/iresearch/weekly/1`](https://rsshub.app/iresearch/weekly/1)。\n:::\n\n| 名称                                                                        | ID                                           |\n| --------------------------------------------------------------------------- | -------------------------------------------- |\n| [家电行业](https://www.iresearch.com.cn/report.shtml?type=3\\&classId=1)     | [1](https://rsshub.app/iresearch/report/3/1) |\n| [服装行业](https://www.iresearch.com.cn/report.shtml?type=3\\&classId=2)     | [2](https://rsshub.app/iresearch/report/3/2) |\n| [美妆行业](https://www.iresearch.com.cn/report.shtml?type=3\\&classId=3)     | [3](https://rsshub.app/iresearch/report/3/3) |\n| [食品饮料行业](https://www.iresearch.com.cn/report.shtml?type=3\\&classId=4) | [4](https://rsshub.app/iresearch/report/3/4) |\n| [酒行业](https://www.iresearch.com.cn/report.shtml?type=3\\&classId=5)       | [5](https://rsshub.app/iresearch/report/3/5) |",
  "example": "/iresearch/weekly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "weekly.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "周度市场观察",
  "parameters": {
    "id": {
      "description": "行业 ID，默认为全部，即全部行业，可在对应行业页 URL 中找到",
      "options": [
        {
          "label": "全部",
          "value": ""
        },
        {
          "label": "家电行业",
          "value": "1"
        },
        {
          "label": "服装行业",
          "value": "2"
        },
        {
          "label": "美妆行业",
          "value": "3"
        },
        {
          "label": "食品饮料行业",
          "value": "4"
        },
        {
          "label": "酒行业",
          "value": "5"
        }
      ]
    }
  },
  "path": "/weekly/:id?",
  "radar": [
    {
      "source": [
        "www.iresearch.com.cn/report.shtml"
      ]
    },
    {
      "source": [
        "www.iresearch.com.cn/report.shtml"
      ],
      "target": "/weekly/1",
      "title": "家电行业"
    },
    {
      "source": [
        "www.iresearch.com.cn/report.shtml"
      ],
      "target": "/weekly/2",
      "title": "服装行业"
    },
    {
      "source": [
        "www.iresearch.com.cn/report.shtml"
      ],
      "target": "/weekly/3",
      "title": "美妆行业"
    },
    {
      "source": [
        "www.iresearch.com.cn/report.shtml"
      ],
      "target": "/weekly/4",
      "title": "食品饮料行业"
    },
    {
      "source": [
        "www.iresearch.com.cn/report.shtml"
      ],
      "target": "/weekly/5",
      "title": "酒行业"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 301 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.iresearch.com.cn",
  "view": 0
}
```
