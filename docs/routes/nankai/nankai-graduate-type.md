# 南开大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/nankai/graduate/:type?`
- Route Name: `研究生院`
- Example: `/nankai/graduate/zxdt`
- URL: `graduate.nankai.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ladeng07`
- Source Location: `graduate-notice.ts`
- Source Module: `_None_`

## Description
| 最新动态 | 综合信息 | 招生工作 | 培养管理 | 国际交流 | 学科建设 | 学位管理 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| zxdt     | 82       | 83       | 72       | 73       | xkjs     | xwgl     |

## Parameters
- `type`: 栏目编号（若为空则默认为"zxdt"）


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
  - `graduate.nankai.edu.cn`
  - `graduate.nankai.edu.cn/:type/list.htm`
- `target`: `/graduate/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 最新动态 | 综合信息 | 招生工作 | 培养管理 | 国际交流 | 学科建设 | 学位管理 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| zxdt     | 82       | 83       | 72       | 73       | xkjs     | xwgl     |",
  "example": "/nankai/graduate/zxdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "graduate-notice.ts",
  "maintainers": [
    "ladeng07"
  ],
  "name": "研究生院",
  "parameters": {
    "type": "栏目编号（若为空则默认为\"zxdt\"）"
  },
  "path": "/graduate/:type?",
  "radar": [
    {
      "source": [
        "graduate.nankai.edu.cn",
        "graduate.nankai.edu.cn/:type/list.htm"
      ],
      "target": "/graduate/:type?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "南开大学研究生院-综合信息 - Powered by RSSHub",
      "errorAt": "2026-09-04T07:32:23.137Z",
      "errorMessage": "[GET] \"https://graduate.nankai.edu.cn/82/list.htm\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 222.30.45.190:443, 2001:250:401:d450::190:443, timeout: 10000ms))\n",
      "id": "190697912128162816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://graduate.nankai.edu.cn/82/list.htm",
      "title": "南开大学研究生院-综合信息",
      "type": "feed",
      "url": "rsshub://nankai/graduate/82"
    }
  ],
  "url": "graduate.nankai.edu.cn"
}
```
