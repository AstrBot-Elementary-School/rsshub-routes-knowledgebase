# 牛客网 - 实习广场 & 社招广场

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/nowcoder/jobcenter/:recruitType?/:city?/:type?/:order?/:latest?`
- Route Name: `实习广场 & 社招广场`
- Example: `/nowcoder/jobcenter/1/北京/1/1/true`
- URL: `nowcoder.com/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `jobcenter.ts`
- Source Module: `_None_`

## Description
可选城市有：北京、上海、广州、深圳、杭州、南京、成都、厦门、武汉、西安、长沙、哈尔滨、合肥、其他

职位类型代码见下表：

| 研发 | 测试 | 数据 | 算法 | 前端 | 产品 | 运营 | 其他 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 1    | 2    | 3    | 4    | 5    | 6    | 7    | 0    |

排序参数见下表：

| 最新发布 | 最快处理 | 处理率最高 |
| -------- | -------- | ---------- |
| 1        | 2        | 3          |

## Parameters
- `recruitType`: 招聘分类，`1` 指 实习广场，`2` 指 社招广场，默认为 `1`
- `city`: 所在城市，可选城市见下表，若空则为 `全国`
- `type`: 职位类型，可选职位代码见下表，若空则为 `全部`
- `order`: 排序参数，可选排序参数代码见下表，若空则为 `默认`
- `latest`: 是否仅查看最近一周，可选 `true` 和 `false`，默认为 `false`


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
  - `nowcoder.com/`
- `target`: `/jobcenter`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "可选城市有：北京、上海、广州、深圳、杭州、南京、成都、厦门、武汉、西安、长沙、哈尔滨、合肥、其他\n\n职位类型代码见下表：\n\n| 研发 | 测试 | 数据 | 算法 | 前端 | 产品 | 运营 | 其他 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 1    | 2    | 3    | 4    | 5    | 6    | 7    | 0    |\n\n排序参数见下表：\n\n| 最新发布 | 最快处理 | 处理率最高 |\n| -------- | -------- | ---------- |\n| 1        | 2        | 3          |",
  "example": "/nowcoder/jobcenter/1/北京/1/1/true",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jobcenter.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "实习广场 & 社招广场",
  "parameters": {
    "city": "所在城市，可选城市见下表，若空则为 `全国`",
    "latest": "是否仅查看最近一周，可选 `true` 和 `false`，默认为 `false`",
    "order": "排序参数，可选排序参数代码见下表，若空则为 `默认`",
    "recruitType": "招聘分类，`1` 指 实习广场，`2` 指 社招广场，默认为 `1`",
    "type": "职位类型，可选职位代码见下表，若空则为 `全部`"
  },
  "path": "/jobcenter/:recruitType?/:city?/:type?/:order?/:latest?",
  "radar": [
    {
      "source": [
        "nowcoder.com/"
      ],
      "target": "/jobcenter"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "nowcoder.com/"
}
```
