# 杭州电子科技大学 - 自动化学院

## Coverage
`index-only`

## Route
- Namespace: `hdu`
- Namespace Name: `杭州电子科技大学`
- Route Path: `/hdu/auto/:type?`
- Route Name: `自动化学院`
- Example: `/hdu/auto`
- URL: `hdu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `jalenzz`
- Source Location: `auto/notice.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 研究生教育 | 本科教学      | 学生工作 |
| -------- | ---------- | ------------- | -------- |
| notice   | graduate   | undergraduate | student  |

## Parameters
- `type`: 分类，见下表，默认为通知公告


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
  - `auto.hdu.edu.cn/main.htm`
  - `auto.hdu.edu.cn/3779/list.htm`
- `target`: `/auto/notice`
### Rule 2
- `source`:
  - `auto.hdu.edu.cn/main.htm`
  - `auto.hdu.edu.cn/3754/list.htm`
- `target`: `/auto/graduate`
### Rule 3
- `source`:
  - `auto.hdu.edu.cn/main.htm`
  - `auto.hdu.edu.cn/3745/list.htm`
- `target`: `/auto/undergraduate`
### Rule 4
- `source`:
  - `auto.hdu.edu.cn/main.htm`
  - `auto.hdu.edu.cn/3726/list.htm`
- `target`: `/auto/student`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 研究生教育 | 本科教学      | 学生工作 |\n| -------- | ---------- | ------------- | -------- |\n| notice   | graduate   | undergraduate | student  |",
  "example": "/hdu/auto",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "auto/notice.ts",
  "maintainers": [
    "jalenzz"
  ],
  "name": "自动化学院",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/auto/:type?",
  "radar": [
    {
      "source": [
        "auto.hdu.edu.cn/main.htm",
        "auto.hdu.edu.cn/3779/list.htm"
      ],
      "target": "/auto/notice"
    },
    {
      "source": [
        "auto.hdu.edu.cn/main.htm",
        "auto.hdu.edu.cn/3754/list.htm"
      ],
      "target": "/auto/graduate"
    },
    {
      "source": [
        "auto.hdu.edu.cn/main.htm",
        "auto.hdu.edu.cn/3745/list.htm"
      ],
      "target": "/auto/undergraduate"
    },
    {
      "source": [
        "auto.hdu.edu.cn/main.htm",
        "auto.hdu.edu.cn/3726/list.htm"
      ],
      "target": "/auto/student"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "杭州电子科技大学自动化学院 - 通知公告 - Powered by RSSHub",
      "errorAt": "2025-06-17T10:13:19.934Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "98947905973951488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://auto.hdu.edu.cn/3779/list.htm",
      "title": "杭州电子科技大学自动化学院 - 通知公告",
      "type": "feed",
      "url": "rsshub://hdu/auto"
    },
    {
      "description": "杭州电子科技大学自动化学院 - 本科教学 - Powered by RSSHub",
      "errorAt": "2025-06-17T09:23:02.999Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "98948106785051648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://auto.hdu.edu.cn/3745/list.htm",
      "title": "杭州电子科技大学自动化学院 - 本科教学",
      "type": "feed",
      "url": "rsshub://hdu/auto/undergraduate"
    }
  ]
}
```
