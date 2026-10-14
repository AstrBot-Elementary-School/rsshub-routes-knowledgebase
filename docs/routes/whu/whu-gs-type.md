# 武汉大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/whu/gs/:type?`
- Route Name: `研究生院`
- Example: `/whu/gs/0`
- URL: `gs.whu.edu.cn/index.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Delreyaa`
- Source Location: `gs/index.ts`
- Source Module: `_None_`

## Description
| 公告类型 | 新闻动态 | 学术探索 | 院系风采 | 通知 (全部) | 通知 (招生) | 通知 (培养) | 通知 (学位) | 通知 (质量与专业学位) | 通知 (综合) |
| -------- | -------- | -------- | -------- | ----------- | ----------- | ----------- | ----------- | --------------------- | ----------- |
| 参数     | 0        | 1        | 2        | 3           | 4           | 5           | 6           | 7                     | 8           |

## Parameters
- `type`: 分类，默认为 `0`，具体参数见下表


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
  - `gs.whu.edu.cn/index.htm`
  - `gs.whu.edu.cn/`
  - `gs.whu.edu.cn/xwdt.htm`
- `target`: `/gs`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公告类型 | 新闻动态 | 学术探索 | 院系风采 | 通知 (全部) | 通知 (招生) | 通知 (培养) | 通知 (学位) | 通知 (质量与专业学位) | 通知 (综合) |\n| -------- | -------- | -------- | -------- | ----------- | ----------- | ----------- | ----------- | --------------------- | ----------- |\n| 参数     | 0        | 1        | 2        | 3           | 4           | 5           | 6           | 7                     | 8           |",
  "example": "/whu/gs/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "gs/index.ts",
  "maintainers": [
    "Delreyaa"
  ],
  "name": "研究生院",
  "parameters": {
    "type": "分类，默认为 `0`，具体参数见下表"
  },
  "path": "/gs/:type?",
  "radar": [
    {
      "source": [
        "gs.whu.edu.cn/index.htm",
        "gs.whu.edu.cn/",
        "gs.whu.edu.cn/xwdt.htm"
      ],
      "target": "/gs"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "武大研究生院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68864970425129984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gs.whu.edu.cn/xwdt.htm",
      "title": "武汉大学研究生院 - 首页 > 新闻动态",
      "type": "feed",
      "url": "rsshub://whu/gs/0"
    }
  ],
  "url": "gs.whu.edu.cn/index.htm"
}
```
