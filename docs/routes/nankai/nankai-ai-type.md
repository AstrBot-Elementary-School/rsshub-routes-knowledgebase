# 南开大学 - 人工智能学院

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/nankai/ai/:type?`
- Route Name: `人工智能学院`
- Example: `/nankai/ai/zxdt`
- URL: `ai.nankai.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LMark`
- Source Location: `ai-notice.ts`
- Source Module: `_None_`

## Description
| 最新动态 | 学院公告 | 学生之窗 | 科研信息 | 本科生教学 | 党团园地 | 研究生招生 | 研究生教学 | 就业信息 | 国际交流 |
| -------- | -------- | -------- | -------- | ---------- | -------- | ---------- | ---------- | -------- | -------- |
| zxdt     | xygg     | xszc     | kyxx     | bksjx      | dtyd     | yjszs      | yjsjx      | jyxx     | gjjl     |

## Parameters
- `type`: 栏目类型（若为空则默认为"最新动态"）


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
  - `ai.nankai.edu.cn`
  - `ai.nankai.edu.cn/xwzx/:type.htm`
- `target`: `/ai/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 最新动态 | 学院公告 | 学生之窗 | 科研信息 | 本科生教学 | 党团园地 | 研究生招生 | 研究生教学 | 就业信息 | 国际交流 |\n| -------- | -------- | -------- | -------- | ---------- | -------- | ---------- | ---------- | -------- | -------- |\n| zxdt     | xygg     | xszc     | kyxx     | bksjx      | dtyd     | yjszs      | yjsjx      | jyxx     | gjjl     |",
  "example": "/nankai/ai/zxdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "ai-notice.ts",
  "maintainers": [
    "LMark"
  ],
  "name": "人工智能学院",
  "parameters": {
    "type": "栏目类型（若为空则默认为\"最新动态\"）"
  },
  "path": "/ai/:type?",
  "radar": [
    {
      "source": [
        "ai.nankai.edu.cn",
        "ai.nankai.edu.cn/xwzx/:type.htm"
      ],
      "target": "/ai/:type?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "南开大学人工智能学院-最新动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "188273958932923392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ai.nankai.edu.cn/xwzx/zxdt.htm",
      "title": "南开大学人工智能学院-最新动态",
      "type": "feed",
      "url": "rsshub://nankai/ai/zxdt"
    }
  ],
  "url": "ai.nankai.edu.cn"
}
```
