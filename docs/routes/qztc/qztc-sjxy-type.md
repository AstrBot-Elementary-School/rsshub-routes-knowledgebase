# 泉州师范学院 - 数学与计算机科学学院 软件学院

## Coverage
`index-only`

## Route
- Namespace: `qztc`
- Namespace Name: `泉州师范学院`
- Route Path: `/qztc/sjxy/:type`
- Route Name: `数学与计算机科学学院 软件学院`
- Example: `/qztc/sjxy/1939`
- URL: `www.qztc.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `iQNRen`
- Source Location: `sjxy/index.ts`
- Source Module: `_None_`

## Description
| 板块     | 参数 |
| -------- | ---- |
| 学院概况 | 1938 |
| 学院动态 | 1939 |
| 学科建设 | 1940 |
| 教学教务 | 1941 |
| 人才培养 | 1942 |
| 科研工作 | 1943 |
| 党群工作 | 1944 |
| 团学工作 | 1945 |
| 资料下载 | 1947 |
| 采购信息 | 1948 |
| 信息公开 | xxgk |

## Parameters
- `type`: 分类，见下表


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
  - `www.qztc.edu.cn/sjxy/:type/list.htm`
- `target`: `/sjxy/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 板块     | 参数 |\n| -------- | ---- |\n| 学院概况 | 1938 |\n| 学院动态 | 1939 |\n| 学科建设 | 1940 |\n| 教学教务 | 1941 |\n| 人才培养 | 1942 |\n| 科研工作 | 1943 |\n| 党群工作 | 1944 |\n| 团学工作 | 1945 |\n| 资料下载 | 1947 |\n| 采购信息 | 1948 |\n| 信息公开 | xxgk |",
  "example": "/qztc/sjxy/1939",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sjxy/index.ts",
  "maintainers": [
    "iQNRen"
  ],
  "name": "数学与计算机科学学院 软件学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/sjxy/:type",
  "radar": [
    {
      "source": [
        "www.qztc.edu.cn/sjxy/:type/list.htm"
      ],
      "target": "/sjxy/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.qztc.edu.cn"
}
```
