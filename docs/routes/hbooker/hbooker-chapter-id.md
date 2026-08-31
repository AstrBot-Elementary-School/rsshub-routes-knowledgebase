# 欢乐书客 - 章节

## Coverage
`index-only`

## Route
- Namespace: `hbooker`
- Namespace Name: `欢乐书客`
- Route Path: `/hbooker/chapter/:id`
- Route Name: `章节`
- Example: `/hbooker/chapter/100113279`
- URL: `hbooker.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `keocheung`
- Source Location: `chapter.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


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
  - `hbooker.com/book/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/hbooker/chapter/100113279",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "chapter.ts",
  "maintainers": [
    "keocheung"
  ],
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/chapter/:id",
  "radar": [
    {
      "source": [
        "hbooker.com/book/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "安可穿越到危险的奇幻世界。 魔女，教廷，精灵，恶魔，浮空城，高塔议会……血与火，阴谋与诡计，灾厄与战争…… 作为一名平平无奇，穷得荡气回肠的小学徒，安可表示自己有一点点慌。 幸好，随身还带了个熟练度面板，任何技能只要肯练就能变强。 【魔法卷轴制作+1】【法师之手+1】【霜冻新星+1】【末日审判+1】…… 故而。 世间升起了一颗冉冉新星。 魔女之王，北境守护者，混沌学派大师，深渊恶魔永恒之敌，审判万物的灾厄太阳，诱拐圣女的罪天使，精灵公主的闺中密友…… 伟大，无需多言！ - Powered by RSSHub",
      "errorAt": "2025-08-12T10:55:45.382Z",
      "errorMessage": "[GET] \"https://www.hbooker.com/chapter/113940252\": 503 Service Temporarily Unavailable\n",
      "id": "120950392738900992",
      "image": "https://novel-cdn.kuangxiangit.com/uploads/allimg/c240715/15-07-24212441-47593.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.hbooker.com/book/100410769",
      "title": "欢乐书客 魔女大人别肝啦",
      "type": "feed",
      "url": "rsshub://hbooker/chapter/100410769"
    }
  ]
}
```
