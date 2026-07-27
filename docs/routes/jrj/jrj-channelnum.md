# 金融界 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `jrj`
- Namespace Name: `金融界`
- Route Path: `/jrj/:channelNum`
- Route Name: `资讯`
- Example: `/jrj/103`
- URL: `www.jrj.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `p3psi-boo`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| column | Description |
| ------ | ----------- |
| 103    | 财经资讯    |
| 508    | 科技资讯    |
| 106    | 商业资讯    |
| 632    | 消费资讯    |
| 630    | 医疗资讯    |
| 119    | 康养资讯    |
| 004    | 汽车资讯    |
| 009    | 房产资讯    |
| 629    | ESG 资讯    |
| 001    | 港股资讯    |
| 102    | 美股资讯    |
| 113    | 银行资讯    |
| 115    | 保险资讯    |
| 104    | 基金资讯    |
| 503    | 私募资讯    |
| 112    | 信托资讯    |
| 007    | 外汇资讯    |
| 107    | 期货资讯    |
| 118    | 债券资讯    |
| 603    | 券商资讯    |
| 105    | 观点        |

## Parameters
- `channelNum`: {"description": "栏目编号", "options": [{"label": "美股资讯", "value": "102"}, {"label": "财经资讯", "value": "103"}, {"label": "基金资讯", "value": "104"}, {"label": "观点", "value": "105"}, {"label": "商业资讯", "value": "106"}, {"label": "期货资讯", "value": "107"}, {"label": "信托资讯", "value": "112"}, {"label": "银行资讯", "value": "113"}, {"label": "保险资讯", "value": "115"}, {"label": "债券资讯", "value": "118"}, {"label": "康养资讯", "value": "119"}, {"label": "私募资讯", "value": "503"}, {"label": "科技资讯", "value": "508"}, {"label": "券商资讯", "value": "603"}, {"label": "ESG 资讯", "value": "629"}, {"label": "医疗资讯", "value": "630"}, {"label": "消费资讯", "value": "632"}, {"label": "汽车资讯", "value": "004"}, {"label": "房产资讯", "value": "009"}, {"label": "A股资讯", "value": "010"}, {"label": "港股资讯", "value": "001"}, {"label": "外汇资讯", "value": "007"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| column | Description |\n| ------ | ----------- |\n| 103    | 财经资讯    |\n| 508    | 科技资讯    |\n| 106    | 商业资讯    |\n| 632    | 消费资讯    |\n| 630    | 医疗资讯    |\n| 119    | 康养资讯    |\n| 004    | 汽车资讯    |\n| 009    | 房产资讯    |\n| 629    | ESG 资讯    |\n| 001    | 港股资讯    |\n| 102    | 美股资讯    |\n| 113    | 银行资讯    |\n| 115    | 保险资讯    |\n| 104    | 基金资讯    |\n| 503    | 私募资讯    |\n| 112    | 信托资讯    |\n| 007    | 外汇资讯    |\n| 107    | 期货资讯    |\n| 118    | 债券资讯    |\n| 603    | 券商资讯    |\n| 105    | 观点        |",
  "example": "/jrj/103",
  "heat": 68,
  "location": "index.ts",
  "maintainers": [
    "p3psi-boo"
  ],
  "name": "资讯",
  "parameters": {
    "channelNum": {
      "description": "栏目编号",
      "options": [
        {
          "label": "美股资讯",
          "value": "102"
        },
        {
          "label": "财经资讯",
          "value": "103"
        },
        {
          "label": "基金资讯",
          "value": "104"
        },
        {
          "label": "观点",
          "value": "105"
        },
        {
          "label": "商业资讯",
          "value": "106"
        },
        {
          "label": "期货资讯",
          "value": "107"
        },
        {
          "label": "信托资讯",
          "value": "112"
        },
        {
          "label": "银行资讯",
          "value": "113"
        },
        {
          "label": "保险资讯",
          "value": "115"
        },
        {
          "label": "债券资讯",
          "value": "118"
        },
        {
          "label": "康养资讯",
          "value": "119"
        },
        {
          "label": "私募资讯",
          "value": "503"
        },
        {
          "label": "科技资讯",
          "value": "508"
        },
        {
          "label": "券商资讯",
          "value": "603"
        },
        {
          "label": "ESG 资讯",
          "value": "629"
        },
        {
          "label": "医疗资讯",
          "value": "630"
        },
        {
          "label": "消费资讯",
          "value": "632"
        },
        {
          "label": "汽车资讯",
          "value": "004"
        },
        {
          "label": "房产资讯",
          "value": "009"
        },
        {
          "label": "A股资讯",
          "value": "010"
        },
        {
          "label": "港股资讯",
          "value": "001"
        },
        {
          "label": "外汇资讯",
          "value": "007"
        }
      ]
    }
  },
  "path": "/:channelNum",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "美股资讯 - 金融界 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "137746341036184576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jrj.com/",
      "title": "美股资讯 - 金融界",
      "type": "feed",
      "url": "rsshub://jrj/102"
    },
    {
      "description": "财经资讯 - 金融界 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "110335328538370048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jrj.com/",
      "title": "财经资讯 - 金融界",
      "type": "feed",
      "url": "rsshub://jrj/103"
    }
  ],
  "url": "www.jrj.com.cn"
}
```
