# Hanime1 - 搜索结果

## Coverage
`index-only`

## Route
- Namespace: `hanime1`
- Namespace Name: `Hanime1`
- Route Path: `/hanime1/search/:params`
- Route Name: `搜索结果`
- Example: `/hanime1/search/tags%5B%5D=%E7%B4%94%E6%84%9B&`
- URL: `hanime1.me`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `kjasn`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `params`: {"description": "\n| 参数                | 说明                              | 示例或可选值                                                                                                          |\n| ------------------- | --------------------------------- | --------------------------------------------------------------------------------------------------------------------- |\n| `query`           | 搜索框输入的内容                  | 任意值都可以，例如：`辣妹`                                                                                          |\n| `genre`           | 番剧类型，默认为`全部`          | 可选值有：`全部` / `裏番` / `泡麵番` / `Motion+Anime` / `3D動畫` / `同人作品` / `MMD` / `Cosplay`     |\n| `tags[]`          | 标签                              | 可选值过多，不一一列举，详细请查看原网址。例如：`tags[]=純愛&tags[]=中文字幕`                                       |\n| `broad`           | 标签模糊匹配，默认为 `off`      | `on`（模糊匹配，包含任一标签） / `off`（精确匹配，包含全部标签）                                                  |\n| `sort`            | 搜索结果排序，默认 `最新上市`   | `最新上市` / `最新上傳` / `本日排行` / `本週排行` / `本月排行` / `觀看次數` / `讚好比例` / `他們在看` |\n| `year`, `month` | 筛选发布时间，默认为 `全部时间` | 例如：`year=2025&month=5`                                                                                           |\n\n::: tip\n如果你不确定标签或类型的具体名字，可以直接去原网址选好筛选条件后，把网址中的参数复制过来使用。例如： `https://hanime1.me/search?query=&genre=裏番&broad=on&sort=最新上市&tags[]=純愛&tags[]=中文字幕`，`/search?`后面的部分就是参数了,最后得到**类似**这样的路由 `https://rsshub.app/hanime1/search/query=&genre=裏番&broad=on&sort=最新上市&tags[]=純愛&tags[]=中文字幕`\n:::\n"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/hanime1/search/tags%5B%5D=%E7%B4%94%E6%84%9B&",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 44,
  "location": "search.ts",
  "maintainers": [
    "kjasn"
  ],
  "name": "搜索结果",
  "parameters": {
    "params": {
      "description": "\n| 参数                | 说明                              | 示例或可选值                                                                                                          |\n| ------------------- | --------------------------------- | --------------------------------------------------------------------------------------------------------------------- |\n| `query`           | 搜索框输入的内容                  | 任意值都可以，例如：`辣妹`                                                                                          |\n| `genre`           | 番剧类型，默认为`全部`          | 可选值有：`全部` / `裏番` / `泡麵番` / `Motion+Anime` / `3D動畫` / `同人作品` / `MMD` / `Cosplay`     |\n| `tags[]`          | 标签                              | 可选值过多，不一一列举，详细请查看原网址。例如：`tags[]=純愛&tags[]=中文字幕`                                       |\n| `broad`           | 标签模糊匹配，默认为 `off`      | `on`（模糊匹配，包含任一标签） / `off`（精确匹配，包含全部标签）                                                  |\n| `sort`            | 搜索结果排序，默认 `最新上市`   | `最新上市` / `最新上傳` / `本日排行` / `本週排行` / `本月排行` / `觀看次數` / `讚好比例` / `他們在看` |\n| `year`, `month` | 筛选发布时间，默认为 `全部时间` | 例如：`year=2025&month=5`                                                                                           |\n\n::: tip\n如果你不确定标签或类型的具体名字，可以直接去原网址选好筛选条件后，把网址中的参数复制过来使用。例如： `https://hanime1.me/search?query=&genre=裏番&broad=on&sort=最新上市&tags[]=純愛&tags[]=中文字幕`，`/search?`后面的部分就是参数了,最后得到**类似**这样的路由 `https://rsshub.app/hanime1/search/query=&genre=裏番&broad=on&sort=最新上市&tags[]=純愛&tags[]=中文字幕`\n:::\n"
    }
  },
  "path": "/search/:params",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Hanime1 搜索结果 | 类型: 全部 | 标签: 扶他 - Powered by RSSHub",
      "errorAt": "2026-01-14T05:24:14.256Z",
      "errorMessage": "[GET] \"https://hanime1.me/search?query=&genre=全部&broad=&sort=&year=&month=&tags[]=扶他\": 403 Forbidden\n[GET] \"https://hanime1.me/search?query=&genre=全部&broad=&sort=&year=&month=&tags[]=扶他\": 403 Forbidden\n",
      "id": "143852106817588235",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hanime1.me/search?query=&genre=%E5%85%A8%E9%83%A8&broad=&sort=&year=&month=&tags[]=%E6%89%B6%E4%BB%96",
      "title": "Hanime1 搜索结果 | 类型: 全部 | 标签: 扶他",
      "type": "feed",
      "url": "rsshub://hanime1/search/query=&type=&genre=%E5%85%A8%E9%83%A8&tags%5B%5D=%E6%89%B6%E4%BB%96&sort=&year=&month="
    },
    {
      "description": "Hanime1 搜索结果 | 类型: Cosplay - Powered by RSSHub",
      "errorAt": "2026-01-14T04:42:31.316Z",
      "errorMessage": "[GET] \"https://hanime1.me/search?query=&genre=Cosplay&broad=&sort=&year=&month=\": 403 Forbidden\n",
      "id": "165957469628528640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hanime1.me/search?query=&genre=Cosplay&broad=&sort=&year=&month=",
      "title": "Hanime1 搜索结果 | 类型: Cosplay",
      "type": "feed",
      "url": "rsshub://hanime1/search/genre%3DCosplay"
    }
  ]
}
```
