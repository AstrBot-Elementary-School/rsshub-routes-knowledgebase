# 69书吧 - 章节

## Coverage
`index-only`

## Route
- Namespace: `69shu`
- Namespace Name: `69书吧`
- Route Path: `/69shu/article/:id`
- Route Name: `章节`
- Example: `/69shu/article/47117`
- URL: `www.69shuba.cx`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `eternasuno`
- Source Location: `article.ts`
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
  - `www.69shuba.cx/book/:id.htm`
- `target`: `/article/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/69shu/article/47117",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "article.ts",
  "maintainers": [
    "eternasuno"
  ],
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/article/:id",
  "radar": [
    {
      "source": [
        "www.69shuba.cx/book/:id.htm"
      ],
      "target": "/article/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "我不是赛博精神病 - Powered by RSSHub",
      "errorAt": "2025-04-08T16:06:51.351Z",
      "errorMessage": "[GET] \"https://www.69shuba.cx/book/47117.htm\": 403 Forbidden\n",
      "id": "65269883630621696",
      "image": "/cdn/images/nc.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.69shuba.cx/book/47117.htm",
      "title": "我不是赛博精神病",
      "type": "feed",
      "url": "rsshub://69shu/article/47117"
    },
    {
      "description": "老者：“你想报仇？” 少年：“我被强者反复侮辱，被师尊视为垃圾，我怎么可能不想报仇？” 老者摸了摸少年的脑袋，叹道：“好孩子，我来传功给你吧。” 少年惊道：“前辈！这怎么行？” 老者伸出手：“把你手机给我。” 少年看着手机上的变化，震惊道：“前辈！这哪里来的百年功力？” 老者微微一笑：“好孩子，这是你在天庭的备用功力，以后急用的时候随用随取，别再被人侮辱了。” 少年皱眉：“这不是法力贷吗？我怕……” 老者：“天庭是大平台，新用户借百年功力有30天免息，日息最低半天功力，还没你吐纳一周天多。” …… 张羽冷哼一声，关掉了上面的广告。 - Powered by RSSHub",
      "errorAt": "2025-04-08T13:37:17.784Z",
      "errorMessage": "Failed to fetch\n",
      "id": "86390076499397632",
      "image": "https://static.69shuba.com/files/article/image/85/85122/85122s.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.69shuba.cx/book/85122.htm",
      "title": "没钱修什么仙？",
      "type": "feed",
      "url": "rsshub://69shu/article/85122"
    }
  ],
  "url": "www.69shuba.cx"
}
```
