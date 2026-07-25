# 禁漫天堂 - 成人 A 漫

## Coverage
`index-only`

## Route
- Namespace: `18comic`
- Namespace Name: `禁漫天堂`
- Route Path: `/18comic/:category?/:time?/:order?/:keyword?`
- Route Name: `成人 A 漫`
- Example: `/18comic`
- URL: `jmcomic.group/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
分类

| 全部 | 其他漫畫 | 同人   | 韓漫   | 美漫   | 短篇  | 单本   |
| ---- | -------- | ------ | ------ | ------ | ----- | ------ |
| all  | another  | doujin | hanman | meiman | short | single |

时间范围

| 全部 | 今天 | 这周 | 本月 |
| ---- | ---- | ---- | ---- |
| a    | t    | w    | m    |

排列顺序

| 最新 | 最多点阅的 | 最多图片 | 最高评分 | 最多评论 | 最多爱心 |
| ---- | ---------- | -------- | -------- | -------- | -------- |
| mr   | mv         | mp       | tr       | md       | tf       |

关键字（供参考）

| YAOI | 女性向 | NTR | 非 H | 3D | 獵奇 |
| ---- | ------ | --- | ---- | -- | ---- |

## Parameters
- `category`: 分类，见下表，默认为 `all` 即全部
- `time`: 时间范围，见下表，默认为 `a` 即全部
- `order`: 排列顺序，见下表，默认为 `mr` 即最新
- `keyword`: 关键字，见下表，默认为空


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `jmcomic.group/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "分类\n\n| 全部 | 其他漫畫 | 同人   | 韓漫   | 美漫   | 短篇  | 单本   |\n| ---- | -------- | ------ | ------ | ------ | ----- | ------ |\n| all  | another  | doujin | hanman | meiman | short | single |\n\n时间范围\n\n| 全部 | 今天 | 这周 | 本月 |\n| ---- | ---- | ---- | ---- |\n| a    | t    | w    | m    |\n\n排列顺序\n\n| 最新 | 最多点阅的 | 最多图片 | 最高评分 | 最多评论 | 最多爱心 |\n| ---- | ---------- | -------- | -------- | -------- | -------- |\n| mr   | mv         | mp       | tr       | md       | tf       |\n\n关键字（供参考）\n\n| YAOI | 女性向 | NTR | 非 H | 3D | 獵奇 |\n| ---- | ------ | --- | ---- | -- | ---- |",
  "example": "/18comic",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 474,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "成人 A 漫",
  "parameters": {
    "category": "分类，见下表，默认为 `all` 即全部",
    "keyword": "关键字，见下表，默认为空",
    "order": "排列顺序，见下表，默认为 `mr` 即最新",
    "time": "时间范围，见下表，默认为 `a` 即全部"
  },
  "path": "/:category?/:time?/:order?/:keyword?",
  "radar": [
    {
      "source": [
        "jmcomic.group/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "最新的 A漫 - 禁漫天堂 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149578173744708609",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jmcomic1.me/albums",
      "title": "最新的 Comics - 禁漫天堂",
      "type": "feed",
      "url": "rsshub://18comic"
    },
    {
      "description": "最新的 A漫 - 禁漫天堂 - Powered by RSSHub",
      "errorAt": "2026-07-19T21:38:19.182Z",
      "errorMessage": "502 \n[GET] \"https://jmcomic1.me/albums\": 403 \n[GET] \"https://jmcomic1.me/albums\": 403 Forbidden\n",
      "id": "181646966076518400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jmcomic1.me/albums",
      "title": "最新的 Comics - 禁漫天堂",
      "type": "feed",
      "url": "rsshub://18comic/all/a/mr"
    }
  ],
  "url": "jmcomic.group/"
}
```
