# 腾讯网 - 腾讯频道

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/qq/pd/guild/:id/:sub?/:sort?`
- Route Name: `腾讯频道`
- Example: `/qq/pd/guild/qrp4pkq01d/650967831/created`
- URL: `pd.qq.com/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `mobyw`
- Source Location: `pd/guild.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 频道号
- `sub`: 子频道 ID，网页端 URL `subc` 参数的值，默认为 `hot`（全部）
- `sort`: 排序方式，`hot`（热门），`created`（最新发布），`replied`（最新回复），默认为 `created`


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
  - `pd.qq.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/qq/pd/guild/qrp4pkq01d/650967831/created",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "pd/guild.ts",
  "maintainers": [
    "mobyw"
  ],
  "name": "腾讯频道",
  "parameters": {
    "id": "频道号",
    "sort": "排序方式，`hot`（热门），`created`（最新发布），`replied`（最新回复），默认为 `created`",
    "sub": "子频道 ID，网页端 URL `subc` 参数的值，默认为 `hot`（全部）"
  },
  "path": "/pd/guild/:id/:sub?/:sort?",
  "radar": [
    {
      "source": [
        "pd.qq.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "北京邮电大学生活圈 - 腾讯频道 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "123203042771095552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pd.qq.com/g/mb76a3g9ey",
      "title": "北京邮电大学生活圈 - 腾讯频道",
      "type": "feed",
      "url": "rsshub://qq/pd/guild/mb76a3g9ey"
    },
    {
      "description": "自由学习 - 腾讯频道 - Powered by RSSHub",
      "errorAt": "2025-03-08T09:35:20.989Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "121071855026880512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pd.qq.com/g/785d69ddf5",
      "title": "自由学习 - 腾讯频道",
      "type": "feed",
      "url": "rsshub://qq/pd/guild/785d69ddf5/hot/created"
    }
  ],
  "url": "pd.qq.com/"
}
```
