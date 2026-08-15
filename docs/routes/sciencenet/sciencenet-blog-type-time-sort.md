# 科学网 - 精选博客

## Coverage
`index-only`

## Route
- Namespace: `sciencenet`
- Namespace Name: `科学网`
- Route Path: `/sciencenet/blog/:type?/:time?/:sort?`
- Route Name: `精选博客`
- Example: `/sciencenet/blog`
- URL: `blog.sciencenet.cn`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
类型

| 精选      | 最新 | 热门 |
| --------- | ---- | ---- |
| recommend | new  | hot  |

时间

| 36 小时内精选博文 | 一周内精选博文 | 一月内精选博文 | 半年内精选博文 | 所有时间精选博文 |
| ----------------- | -------------- | -------------- | -------------- | ---------------- |
| 1                 | 2              | 3              | 4              | 5                |

排序

| 按发表时间排序 | 按评论数排序 | 按点击数排序 |
| -------------- | ------------ | ------------ |
| 1              | 2            | 3            |

## Parameters
- `type`: 类型，见下表，默认为推荐
- `time`: 时间，见下表，默认为所有时间
- `sort`: 排序，见下表，默认为按发表时间排序


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media",
    "popular"
  ],
  "description": "类型\n\n| 精选      | 最新 | 热门 |\n| --------- | ---- | ---- |\n| recommend | new  | hot  |\n\n时间\n\n| 36 小时内精选博文 | 一周内精选博文 | 一月内精选博文 | 半年内精选博文 | 所有时间精选博文 |\n| ----------------- | -------------- | -------------- | -------------- | ---------------- |\n| 1                 | 2              | 3              | 4              | 5                |\n\n排序\n\n| 按发表时间排序 | 按评论数排序 | 按点击数排序 |\n| -------------- | ------------ | ------------ |\n| 1              | 2            | 3            |",
  "example": "/sciencenet/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2987,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "精选博客",
  "parameters": {
    "sort": "排序，见下表，默认为按发表时间排序",
    "time": "时间，见下表，默认为所有时间",
    "type": "类型，见下表，默认为推荐"
  },
  "path": "/blog/:type?/:time?/:sort?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "科学网 - 精选博文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58829412811444254",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://blog.sciencenet.cn/blog.php?mod=recommend&type=list&op=5&ord=1",
      "title": "科学网 - 精选博文",
      "type": "feed",
      "url": "rsshub://sciencenet/blog"
    },
    {
      "description": "科学网 - 精选博文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66291831749510152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://blog.sciencenet.cn/blog.php?mod=hot&type=list&op=5&ord=1",
      "title": "科学网 - 精选博文",
      "type": "feed",
      "url": "rsshub://sciencenet/blog/hot"
    }
  ]
}
```
