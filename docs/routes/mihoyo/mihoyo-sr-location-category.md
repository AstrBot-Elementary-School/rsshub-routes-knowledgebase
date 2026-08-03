# 米哈游 - 崩坏：星穹铁道

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/sr/:location?/:category?`
- Route Name: `崩坏：星穹铁道`
- Example: `/mihoyo/sr`
- URL: `sr.mihoyo.com/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `shinanory`
- Source Location: `sr/news.ts`
- Source Module: `_None_`

## Description
#### 新闻 {#mi-ha-you-beng-huai-xing-qiong-tie-dao-xin-wen}

| 最新     | 新闻 | 公告   | 活动     |
| -------- | ---- | ------ | -------- |
| news-all | news | notice | activity |

## Parameters
- `location`: 区域，可选 `zh-cn`（国服，简中）或 `zh-tw`（国际服，繁中）
- `category`: 分类，见下表，默认为最新


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
  - `sr.mihoyo.com/news`
- `target`: `/sr`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "#### 新闻 {#mi-ha-you-beng-huai-xing-qiong-tie-dao-xin-wen}\n\n| 最新     | 新闻 | 公告   | 活动     |\n| -------- | ---- | ------ | -------- |\n| news-all | news | notice | activity |",
  "example": "/mihoyo/sr",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 42,
  "location": "sr/news.ts",
  "maintainers": [
    "shinanory"
  ],
  "name": "崩坏：星穹铁道",
  "parameters": {
    "category": "分类，见下表，默认为最新",
    "location": "区域，可选 `zh-cn`（国服，简中）或 `zh-tw`（国际服，繁中）"
  },
  "path": "/sr/:location?/:category?",
  "radar": [
    {
      "source": [
        "sr.mihoyo.com/news"
      ],
      "target": "/sr"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "最新-崩坏：星穹铁道 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59881623643134976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://api-takumi-static.mihoyo.com/content_v2_user/app/1963de8dc19e461c/getContentList?iPage=1&iPageSize=50&sLangKey=zh-cn&isPreview=0&iChanId=255",
      "title": "最新-崩坏：星穹铁道",
      "type": "feed",
      "url": "rsshub://mihoyo/sr"
    },
    {
      "description": "公告-崩坏：星穹铁道 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60890429356326912",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://api-takumi-static.mihoyo.com/content_v2_user/app/1963de8dc19e461c/getContentList?iPage=1&iPageSize=50&sLangKey=zh-cn&isPreview=0&iChanId=257",
      "title": "公告-崩坏：星穹铁道",
      "type": "feed",
      "url": "rsshub://mihoyo/sr/zh-cn/notice"
    }
  ],
  "url": "sr.mihoyo.com/news"
}
```
