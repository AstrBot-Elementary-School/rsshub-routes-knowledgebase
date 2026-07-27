# 香港经济日报 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `hket`
- Namespace Name: `香港经济日报`
- Route Path: `/hket/:category?`
- Route Name: `新闻`
- Example: `/hket/sran001`
- URL: `www.hket.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
香港经济日报已有提供简单 RSS，详细可前往官方网站： <https://www.hket.com/rss>

此路由主要补全官方 RSS 全文输出及完善分类输出。

<details>
<summary>分类</summary>

| sran001  | sran008  | sran010  | sran011  | sran012  | srat006  |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 全部新闻 | 财经地产 | 科技信息 | 国际新闻 | 商业新闻 | 香港新闻 |

| sran009  | sran009-1 | sran009-2 | sran009-3  | sran009-4 | sran009-5 | sran009-6 |
| -------- | --------- | --------- | ---------- | --------- | --------- | --------- |
| 即时财经 | 股市      | 新股 IPO  | 新经济追踪 | 当炒股    | 宏观解读  | Hot Talk  |

| sran011-1 | sran011-2    | sran011-3    |
| --------- | ------------ | ------------ |
| 环球政治  | 环球经济金融 | 环球社会热点 |

| sran016    | sran016-1  | sran016-2  | sran016-3  | sran016-4  | sran016-5      |
| ---------- | ---------- | ---------- | ---------- | ---------- | -------------- |
| 大湾区主页 | 大湾区发展 | 大湾区工作 | 大湾区买楼 | 大湾区消费 | 大湾区投资理财 |

| srac002  | srac003  | srac004  | srac005  |
| -------- | -------- | -------- | -------- |
| 即时中国 | 经济脉搏 | 国情动向 | 社会热点 |

| srat001 | srat008 | srat055  | srat069  | srat070   |
| ------- | ------- | -------- | -------- | --------- |
| 话题    | 观点    | 休闲消费 | 娱乐新闻 | TOPick TV |

| srat052  | srat052-1 | srat052-2  | srat052-3 |
| -------- | --------- | ---------- | --------- |
| 健康主页 | 食用安全  | 医生诊症室 | 保健美颜  |

| srat053  | srat053-1 | srat053-2 | srat053-3 | srat053-4  |
| -------- | --------- | --------- | --------- | ---------- |
| 亲子主页 | 儿童健康  | 育儿经    | 教育      | 亲子好去处 |

| srat053-6   | srat053-61 | srat053-62 | srat053-63 | srat053-64 |
| ----------- | ---------- | ---------- | ---------- | ---------- |
| Band 1 学堂 | 幼稚园     | 中小学     | 尖子教室   | 海外升学   |

| srat072-1  | srat072-2  | srat072-3        | srat072-4         |
| ---------- | ---------- | ---------------- | ----------------- |
| 健康身心活 | 抗癌新方向 | 「糖」「心」解密 | 风湿不再 你我自在 |

| sraw007  | sraw009  | sraw010  | sraw011  | sraw012  | sraw014  | sraw018  | sraw019  |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 全部博客 | Bloggers | 收息攻略 | 精明消费 | 退休规划 | 个人增值 | 财富管理 | 绿色金融 |

| sraw015  | sraw015-07 | sraw015-08 | sraw015-09 | sraw015-10 |
| -------- | ---------- | ---------- | ---------- | ---------- |
| 移民百科 | 海外置业   | 移民攻略   | 移民点滴   | 海外理财   |

| sraw020  | sraw020-1    | sraw020-2 | sraw020-3 | sraw020-4 |
| -------- | ------------ | --------- | --------- | --------- |
| ESG 主页 | ESG 趋势政策 | ESG 投资  | ESG 企业  | ESG 社会  |

</details>

## Parameters
- `category`: 分类，默认为全部新闻，可在 URL 中找到，部分见下表


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
  - `china.hket.com/:category/*`
- `target`: `/:category`
### Rule 2
- `source`:
  - `inews.hket.com/:category/*`
- `target`: `/:category`
### Rule 3
- `source`:
  - `topick.hket.com/:category/*`
- `target`: `/:category`
### Rule 4
- `source`:
  - `wealth.hket.com/:category/*`
- `target`: `/:category`
### Rule 5
- `source`:
  - `www.hket.com/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "香港经济日报已有提供简单 RSS，详细可前往官方网站： <https://www.hket.com/rss>\n\n此路由主要补全官方 RSS 全文输出及完善分类输出。\n\n<details>\n<summary>分类</summary>\n\n| sran001  | sran008  | sran010  | sran011  | sran012  | srat006  |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| 全部新闻 | 财经地产 | 科技信息 | 国际新闻 | 商业新闻 | 香港新闻 |\n\n| sran009  | sran009-1 | sran009-2 | sran009-3  | sran009-4 | sran009-5 | sran009-6 |\n| -------- | --------- | --------- | ---------- | --------- | --------- | --------- |\n| 即时财经 | 股市      | 新股 IPO  | 新经济追踪 | 当炒股    | 宏观解读  | Hot Talk  |\n\n| sran011-1 | sran011-2    | sran011-3    |\n| --------- | ------------ | ------------ |\n| 环球政治  | 环球经济金融 | 环球社会热点 |\n\n| sran016    | sran016-1  | sran016-2  | sran016-3  | sran016-4  | sran016-5      |\n| ---------- | ---------- | ---------- | ---------- | ---------- | -------------- |\n| 大湾区主页 | 大湾区发展 | 大湾区工作 | 大湾区买楼 | 大湾区消费 | 大湾区投资理财 |\n\n| srac002  | srac003  | srac004  | srac005  |\n| -------- | -------- | -------- | -------- |\n| 即时中国 | 经济脉搏 | 国情动向 | 社会热点 |\n\n| srat001 | srat008 | srat055  | srat069  | srat070   |\n| ------- | ------- | -------- | -------- | --------- |\n| 话题    | 观点    | 休闲消费 | 娱乐新闻 | TOPick TV |\n\n| srat052  | srat052-1 | srat052-2  | srat052-3 |\n| -------- | --------- | ---------- | --------- |\n| 健康主页 | 食用安全  | 医生诊症室 | 保健美颜  |\n\n| srat053  | srat053-1 | srat053-2 | srat053-3 | srat053-4  |\n| -------- | --------- | --------- | --------- | ---------- |\n| 亲子主页 | 儿童健康  | 育儿经    | 教育      | 亲子好去处 |\n\n| srat053-6   | srat053-61 | srat053-62 | srat053-63 | srat053-64 |\n| ----------- | ---------- | ---------- | ---------- | ---------- |\n| Band 1 学堂 | 幼稚园     | 中小学     | 尖子教室   | 海外升学   |\n\n| srat072-1  | srat072-2  | srat072-3        | srat072-4         |\n| ---------- | ---------- | ---------------- | ----------------- |\n| 健康身心活 | 抗癌新方向 | 「糖」「心」解密 | 风湿不再 你我自在 |\n\n| sraw007  | sraw009  | sraw010  | sraw011  | sraw012  | sraw014  | sraw018  | sraw019  |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| 全部博客 | Bloggers | 收息攻略 | 精明消费 | 退休规划 | 个人增值 | 财富管理 | 绿色金融 |\n\n| sraw015  | sraw015-07 | sraw015-08 | sraw015-09 | sraw015-10 |\n| -------- | ---------- | ---------- | ---------- | ---------- |\n| 移民百科 | 海外置业   | 移民攻略   | 移民点滴   | 海外理财   |\n\n| sraw020  | sraw020-1    | sraw020-2 | sraw020-3 | sraw020-4 |\n| -------- | ------------ | --------- | --------- | --------- |\n| ESG 主页 | ESG 趋势政策 | ESG 投资  | ESG 企业  | ESG 社会  |\n\n</details>",
  "example": "/hket/sran001",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 49,
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新闻",
  "parameters": {
    "category": "分类，默认为全部新闻，可在 URL 中找到，部分见下表"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "china.hket.com/:category/*"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "inews.hket.com/:category/*"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "topick.hket.com/:category/*"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "wealth.hket.com/:category/*"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "www.hket.com/"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "提供最新國際新聞、香港新聞、財經新聞、地產樓市新聞, 美股即時新聞、即時夜期、中國新聞及科技新聞等。 - Powered by RSSHub",
      "errorAt": "2026-07-15T05:07:25.412Z",
      "errorMessage": "[GET] \"https://inews.hket.com/sran001\": 405 Not Allowed\n",
      "id": "70034910422682624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inews.hket.com/sran001",
      "title": "國際地產財經中國即時新聞 | HKET經濟日報 | 即時新聞頻道",
      "type": "feed",
      "url": "rsshub://hket/sran001"
    },
    {
      "description": "提供最新國際新聞、香港新聞、財經新聞、地產樓市新聞, 美股即時新聞、即時夜期、中國新聞及科技新聞等。 - Powered by RSSHub",
      "errorAt": "2026-07-21T23:21:33.785Z",
      "errorMessage": "[GET] \"https://inews.hket.com/sran001\": 405 Not Allowed\n",
      "id": "94630255063479296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inews.hket.com/sran001",
      "title": "國際地產財經中國即時新聞 | HKET經濟日報 | 即時新聞頻道",
      "type": "feed",
      "url": "rsshub://hket"
    }
  ],
  "url": "www.hket.com/"
}
```
