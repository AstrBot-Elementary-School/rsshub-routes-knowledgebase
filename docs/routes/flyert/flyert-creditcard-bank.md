# 飞客茶馆 - 信用卡

## Coverage
`index-only`

## Route
- Namespace: `flyert`
- Namespace Name: `飞客茶馆`
- Route Path: `/flyert/creditcard/:bank`
- Route Name: `信用卡`
- Example: `/flyert/creditcard/zhongxin`
- URL: `flyert.com/`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `nicolaszf`
- Source Location: `creditcard.ts`
- Source Module: `_None_`

## Description
| 信用卡模块 | bank          |
| ---------- | ------------- |
| 国内信用卡 | creditcard    |
| 浦发银行   | pufa          |
| 招商银行   | zhaoshang     |
| 中信银行   | zhongxin      |
| 交通银行   | jiaotong      |
| 中国银行   | zhonghang     |
| 工商银行   | gongshang     |
| 广发银行   | guangfa       |
| 农业银行   | nongye        |
| 建设银行   | jianshe       |
| 汇丰银行   | huifeng       |
| 民生银行   | mingsheng     |
| 兴业银行   | xingye        |
| 花旗银行   | huaqi         |
| 上海银行   | shanghai      |
| 无卡支付   | wuka          |
| 投资理财   | 137           |
| 网站权益汇 | 145           |
| 境外信用卡 | intcreditcard |

## Parameters
- `bank`: 信用卡板块各银行的拼音简称


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
  - `flyert.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "description": "| 信用卡模块 | bank          |\n| ---------- | ------------- |\n| 国内信用卡 | creditcard    |\n| 浦发银行   | pufa          |\n| 招商银行   | zhaoshang     |\n| 中信银行   | zhongxin      |\n| 交通银行   | jiaotong      |\n| 中国银行   | zhonghang     |\n| 工商银行   | gongshang     |\n| 广发银行   | guangfa       |\n| 农业银行   | nongye        |\n| 建设银行   | jianshe       |\n| 汇丰银行   | huifeng       |\n| 民生银行   | mingsheng     |\n| 兴业银行   | xingye        |\n| 花旗银行   | huaqi         |\n| 上海银行   | shanghai      |\n| 无卡支付   | wuka          |\n| 投资理财   | 137           |\n| 网站权益汇 | 145           |\n| 境外信用卡 | intcreditcard |",
  "example": "/flyert/creditcard/zhongxin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 166,
  "location": "creditcard.ts",
  "maintainers": [
    "nicolaszf"
  ],
  "name": "信用卡",
  "parameters": {
    "bank": "信用卡板块各银行的拼音简称"
  },
  "path": "/creditcard/:bank",
  "radar": [
    {
      "source": [
        "flyert.com.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "飞客茶馆信用卡 - 国内信用卡 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55873225615650816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.flyert.com.cn/",
      "title": "飞客茶馆信用卡 - 国内信用卡",
      "type": "feed",
      "url": "rsshub://flyert/creditcard/creditcard"
    },
    {
      "description": "飞客茶馆信用卡 - 招商银行 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56955741222491136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.flyert.com.cn/",
      "title": "飞客茶馆信用卡 - 招商银行",
      "type": "feed",
      "url": "rsshub://flyert/creditcard/zhaoshang"
    }
  ],
  "url": "flyert.com/"
}
```
