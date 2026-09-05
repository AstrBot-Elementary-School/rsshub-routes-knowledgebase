# 珠海网 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `hizu`
- Namespace Name: `珠海网`
- Route Path: `/hizu/:column?`
- Route Name: `栏目`
- Example: `/hizu`
- URL: `hizh.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 分类     | 编号                     |
| -------- | ------------------------ |
| 热点     | 5dd92265e4b0bf88dd8c1175 |
| 订阅     | 5dd921a7e4b0bf88dd8c116f |
| 学党史   | 604f1cbbe4b0cf5c2234d470 |
| 政经     | 5dd92242e4b0bf88dd8c1174 |
| 合作区   | 61259fd6e4b0d294f7f9786d |
| 名记名播 | 61dfe511e4b0248b60d1c568 |
| 大湾区   | 5dd9222ce4b0bf88dd8c1173 |
| 网评     | 617805e4e4b037abacfd4820 |
| TV 新闻  | 5dd9220de4b0bf88dd8c1172 |
| 音频     | 5e6edd50e4b02ebde0ab061e |
| 澳门     | 600e8ad4e4b02c3a6af6aaa8 |
| 政务     | 600f760fe4b0e33cf6f8e68e |
| 教育     | 5ff7c0fde4b0e2f210d05e20 |
| 深圳     | 5fc88615e4b0e3055e693e0a |
| 中山     | 600e8a93e4b02c3a6af6aa80 |
| 民生     | 5dd921ece4b0bf88dd8c1170 |
| 社区     | 61148184e4b08d3215364396 |
| 专题     | 5dd9215fe4b0bf88dd8c116b |
| 战疫     | 5e2e5107e4b0c14b5d0e3d04 |
| 横琴     | 5f88eaf2e4b0a27cd404e09e |
| 香洲     | 5f86a3f5e4b09d75f99dde7d |
| 金湾     | 5e8c42b4e4b0347c7e5836e0 |
| 斗门     | 5ee70534e4b07b8a779a1ad6 |
| 高新     | 607d37ade4b05c59ac2f3d40 |

## Parameters
- `column`: 栏目，见下表，默认为热点


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
  - `hizh.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 分类     | 编号                     |\n| -------- | ------------------------ |\n| 热点     | 5dd92265e4b0bf88dd8c1175 |\n| 订阅     | 5dd921a7e4b0bf88dd8c116f |\n| 学党史   | 604f1cbbe4b0cf5c2234d470 |\n| 政经     | 5dd92242e4b0bf88dd8c1174 |\n| 合作区   | 61259fd6e4b0d294f7f9786d |\n| 名记名播 | 61dfe511e4b0248b60d1c568 |\n| 大湾区   | 5dd9222ce4b0bf88dd8c1173 |\n| 网评     | 617805e4e4b037abacfd4820 |\n| TV 新闻  | 5dd9220de4b0bf88dd8c1172 |\n| 音频     | 5e6edd50e4b02ebde0ab061e |\n| 澳门     | 600e8ad4e4b02c3a6af6aaa8 |\n| 政务     | 600f760fe4b0e33cf6f8e68e |\n| 教育     | 5ff7c0fde4b0e2f210d05e20 |\n| 深圳     | 5fc88615e4b0e3055e693e0a |\n| 中山     | 600e8a93e4b02c3a6af6aa80 |\n| 民生     | 5dd921ece4b0bf88dd8c1170 |\n| 社区     | 61148184e4b08d3215364396 |\n| 专题     | 5dd9215fe4b0bf88dd8c116b |\n| 战疫     | 5e2e5107e4b0c14b5d0e3d04 |\n| 横琴     | 5f88eaf2e4b0a27cd404e09e |\n| 香洲     | 5f86a3f5e4b09d75f99dde7d |\n| 金湾     | 5e8c42b4e4b0347c7e5836e0 |\n| 斗门     | 5ee70534e4b07b8a779a1ad6 |\n| 高新     | 607d37ade4b05c59ac2f3d40 |",
  "example": "/hizu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "column": "栏目，见下表，默认为热点"
  },
  "path": "/:column?",
  "radar": [
    {
      "source": [
        "hizh.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "热点 - 珠海网 - Powered by RSSHub",
      "errorAt": "2026-09-04T03:57:22.823Z",
      "errorMessage": "[GET] \"https://www.hizh.cn/channels/zjyapp/columns/5dd92265e4b0bf88dd8c1175/stories.json\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 211.162.167.10:443, 211.162.167.14:443, 211.162.167.12:443, 211.162.167.11:443, 211.162.167.16:443, 211.162.167.13:443, 211.162.167.15:443, 211.162.167.9:443, timeout: 10000ms))\n",
      "id": "76267574626993152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hizh.cn/",
      "title": "热点 - 珠海网",
      "type": "feed",
      "url": "rsshub://hizu"
    },
    {
      "description": "香洲 - 珠海网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114507281667054592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hizh.cn/",
      "title": "香洲 - 珠海网",
      "type": "feed",
      "url": "rsshub://hizu/5f86a3f5e4b09d75f99dde7d"
    }
  ],
  "url": "hizh.cn/"
}
```
