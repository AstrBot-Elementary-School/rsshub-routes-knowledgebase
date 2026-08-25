# 湖北工业大学 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `hbut`
- Namespace Name: `湖北工业大学`
- Route Path: `/hbut/news/:type`
- Route Name: `新闻中心`
- Example: `/hbut/news/tzgg`
- URL: `www.hbut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LandonLi`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学校新闻 | 菁菁校园 | 媒体聚焦 | 人物风采 |
| -------- | -------- | -------- | -------- | -------- |
| tzgg     | xxxw     | jjxy     | mtjj     | rwfc     |

## Parameters
- `type`: 分类


## Features
_None_

## Radar
### Rule 1
- `title`: `通知公告`
- `source`:
  - `www.hbut.edu.cn/index/tzgg.htm`
- `target`: `/news/tzgg`
### Rule 2
- `title`: `学校新闻`
- `source`:
  - `news.hbut.edu.cn/xxxw.htm`
- `target`: `/news/xxxw`
### Rule 3
- `title`: `菁菁校园`
- `source`:
  - `news.hbut.edu.cn/jjxy.htm`
- `target`: `/news/jjxy`
### Rule 4
- `title`: `媒体聚焦`
- `source`:
  - `news.hbut.edu.cn/mtjj.htm`
- `target`: `/news/mtjj`
### Rule 5
- `title`: `人物风采`
- `source`:
  - `news.hbut.edu.cn/rwfc.htm`
- `target`: `/news/rwfc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 学校新闻 | 菁菁校园 | 媒体聚焦 | 人物风采 |\n| -------- | -------- | -------- | -------- | -------- |\n| tzgg     | xxxw     | jjxy     | mtjj     | rwfc     |",
  "example": "/hbut/news/tzgg",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "LandonLi"
  ],
  "name": "新闻中心",
  "parameters": {
    "type": "分类"
  },
  "path": "/news/:type",
  "radar": [
    {
      "source": [
        "www.hbut.edu.cn/index/tzgg.htm"
      ],
      "target": "/news/tzgg",
      "title": "通知公告"
    },
    {
      "source": [
        "news.hbut.edu.cn/xxxw.htm"
      ],
      "target": "/news/xxxw",
      "title": "学校新闻"
    },
    {
      "source": [
        "news.hbut.edu.cn/jjxy.htm"
      ],
      "target": "/news/jjxy",
      "title": "菁菁校园"
    },
    {
      "source": [
        "news.hbut.edu.cn/mtjj.htm"
      ],
      "target": "/news/mtjj",
      "title": "媒体聚焦"
    },
    {
      "source": [
        "news.hbut.edu.cn/rwfc.htm"
      ],
      "target": "/news/rwfc",
      "title": "人物风采"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
