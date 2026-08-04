# 中国智库网 - 观点与实践

## Coverage
`index-only`

## Route
- Namespace: `chinathinktanks`
- Namespace Name: `中国智库网`
- Route Path: `/chinathinktanks/:id`
- Route Name: `观点与实践`
- Example: `/chinathinktanks/57`
- URL: `www.chinathinktanks.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `Aeliu`
- Source Location: `viewpoint.ts`
- Source Module: `_None_`

## Description
| `:id` | 专题名称 |
| ----- | -------- |
| 2     | 党的建设 |
| 3     | 社会     |
| 4     | 生态     |
| 5     | 政治     |
| 6     | 经济     |
| 7     | 文化     |
| 9     | 热点专题 |
| 10    | 国际关系 |
| 13    | 国外智库 |
| 46    | 智库报告 |
| 57    | 智库要闻 |
| 126   | 世界经济 |
| 127   | 宏观经济 |
| 128   | 区域经济 |
| 129   | 产业企业 |
| 130   | 三农问题 |
| 131   | 财政金融 |
| 132   | 科技创新 |
| 133   | 民主     |
| 134   | 法治     |
| 135   | 行政     |
| 136   | 国家治理 |
| 137   | 社会事业 |
| 138   | 社会保障 |
| 139   | 民族宗教 |
| 140   | 人口就业 |
| 141   | 社会治理 |
| 142   | 文化产业 |
| 143   | 公共文化 |
| 144   | 文化体制 |
| 145   | 文化思想 |
| 146   | 资源     |
| 147   | 能源     |
| 148   | 环境     |
| 149   | 生态文明 |
| 150   | 思想建设 |
| 151   | 作风建设 |
| 152   | 组织建设 |
| 153   | 制度建设 |
| 154   | 反腐倡廉 |
| 155   | 中国外交 |
| 156   | 全球治理 |
| 157   | 大国关系 |
| 158   | 地区政治 |
| 181   | 执政能力 |

## Parameters
- `id`: 见下表，亦可在网站 url 里找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| `:id` | 专题名称 |\n| ----- | -------- |\n| 2     | 党的建设 |\n| 3     | 社会     |\n| 4     | 生态     |\n| 5     | 政治     |\n| 6     | 经济     |\n| 7     | 文化     |\n| 9     | 热点专题 |\n| 10    | 国际关系 |\n| 13    | 国外智库 |\n| 46    | 智库报告 |\n| 57    | 智库要闻 |\n| 126   | 世界经济 |\n| 127   | 宏观经济 |\n| 128   | 区域经济 |\n| 129   | 产业企业 |\n| 130   | 三农问题 |\n| 131   | 财政金融 |\n| 132   | 科技创新 |\n| 133   | 民主     |\n| 134   | 法治     |\n| 135   | 行政     |\n| 136   | 国家治理 |\n| 137   | 社会事业 |\n| 138   | 社会保障 |\n| 139   | 民族宗教 |\n| 140   | 人口就业 |\n| 141   | 社会治理 |\n| 142   | 文化产业 |\n| 143   | 公共文化 |\n| 144   | 文化体制 |\n| 145   | 文化思想 |\n| 146   | 资源     |\n| 147   | 能源     |\n| 148   | 环境     |\n| 149   | 生态文明 |\n| 150   | 思想建设 |\n| 151   | 作风建设 |\n| 152   | 组织建设 |\n| 153   | 制度建设 |\n| 154   | 反腐倡廉 |\n| 155   | 中国外交 |\n| 156   | 全球治理 |\n| 157   | 大国关系 |\n| 158   | 地区政治 |\n| 181   | 执政能力 |",
  "example": "/chinathinktanks/57",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 33,
  "location": "viewpoint.ts",
  "maintainers": [
    "Aeliu"
  ],
  "name": "观点与实践",
  "parameters": {
    "id": "见下表，亦可在网站 url 里找到"
  },
  "path": "/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国智库网 —— 智库要闻 - Powered by RSSHub",
      "errorAt": "2026-01-01T08:00:14.789Z",
      "errorMessage": "502 \n[GET] \"https://www.chinathinktanks.org.cn/content/list?id=57&pt=1\": 404 Not Found\n",
      "id": "63858618178298974",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chinathinktanks.org.cn/content/list?id=57&pt=1",
      "title": "中国智库网 —— 智库要闻",
      "type": "feed",
      "url": "rsshub://chinathinktanks/57"
    },
    {
      "description": "中国智库网 —— 国外智库 - Powered by RSSHub",
      "errorAt": "2025-12-31T21:07:15.108Z",
      "errorMessage": "[GET] \"https://www.chinathinktanks.org.cn/content/list?id=13&pt=1\": 404 Not Found\n",
      "id": "75371518748737536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chinathinktanks.org.cn/content/list?id=13&pt=1",
      "title": "中国智库网 —— 国外智库",
      "type": "feed",
      "url": "rsshub://chinathinktanks/13"
    }
  ]
}
```
