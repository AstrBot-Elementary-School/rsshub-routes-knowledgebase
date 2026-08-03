# 哈尔滨理工大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `hrbust`
- Namespace Name: `哈尔滨理工大学`
- Route Path: `/hrbust/news/:category?`
- Route Name: `新闻网`
- Example: `/hrbust/news`
- URL: `news.hrbust.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cscnk52`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 理工要闻 | 新闻导读 | 图文报道 | 综合新闻 | 教学科研 | 院处动态 | 学术科创 | 交流合作 | 学生天地 | 招生就业 | 党建思政 | 在线播放 | 理工人物 | 理工校报 | 媒体理工 | 讲座论坛 | 人才招聘 | 学科建设 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| lgyw     | xwdd     | twbd     | zhenew   | jxky     | ycdt     | xskc     | jlhz     | xstd     | zsjy     | djsz     | zxbf     | lgrw     | lgxb     | mtlg     | jzlt     | rczp     | xkjs     |

## Parameters
- `category`: 栏目标识，默认为 lgyw（理工要闻）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `news.hrbust.edu.cn/:category.htm`
- `target`: `/news/:category`
### Rule 2
- `source`:
  - `news.hrbust.edu.cn/`
- `target`: `/news/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 理工要闻 | 新闻导读 | 图文报道 | 综合新闻 | 教学科研 | 院处动态 | 学术科创 | 交流合作 | 学生天地 | 招生就业 | 党建思政 | 在线播放 | 理工人物 | 理工校报 | 媒体理工 | 讲座论坛 | 人才招聘 | 学科建设 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| lgyw     | xwdd     | twbd     | zhenew   | jxky     | ycdt     | xskc     | jlhz     | xstd     | zsjy     | djsz     | zxbf     | lgrw     | lgxb     | mtlg     | jzlt     | rczp     | xkjs     |",
  "example": "/hrbust/news",
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
  "location": "news.ts",
  "maintainers": [
    "cscnk52"
  ],
  "name": "新闻网",
  "parameters": {
    "category": "栏目标识，默认为 lgyw（理工要闻）"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "news.hrbust.edu.cn/:category.htm"
      ],
      "target": "/news/:category"
    },
    {
      "source": [
        "news.hrbust.edu.cn/"
      ],
      "target": "/news/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "news.hrbust.edu.cn",
  "view": 5
}
```
