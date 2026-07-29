# 观察者网 - 风闻话题

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/guancha/topic/:id/:order?`
- Route Name: `风闻话题`
- Example: `/guancha/topic/110/1`
- URL: `guancha.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `occupy5, nczitzk`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
| 最新回复 | 最新发布 | 24 小时最热 | 3 天最热 | 7 天最热 | 3 个月最热 | 专栏文章 |
| -------- | -------- | ----------- | -------- | -------- | ---------- | -------- |
| 1        | 2        | 3           | 6        | 7        | 8          | 5        |

::: tip
仅在话题 id 为 0，即选择 全部 时，**3 个月最热**、**24 小时最热**、**3 天最热**、**7 天最热** 和 **专栏文章** 参数生效。
:::

## Parameters
- `id`: 话题 id，可在URL中找到，默认为全部，即为 `0`
- `order`: 排序参数，见下表


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
  - `guancha.cn/`
- `target`: `/:category?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新回复 | 最新发布 | 24 小时最热 | 3 天最热 | 7 天最热 | 3 个月最热 | 专栏文章 |\n| -------- | -------- | ----------- | -------- | -------- | ---------- | -------- |\n| 1        | 2        | 3           | 6        | 7        | 8          | 5        |\n\n::: tip\n仅在话题 id 为 0，即选择 全部 时，**3 个月最热**、**24 小时最热**、**3 天最热**、**7 天最热** 和 **专栏文章** 参数生效。\n:::",
  "example": "/guancha/topic/110/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "topic.ts",
  "maintainers": [
    "occupy5",
    "nczitzk"
  ],
  "name": "风闻话题",
  "parameters": {
    "id": "话题 id，可在URL中找到，默认为全部，即为 `0`",
    "order": "排序参数，见下表"
  },
  "path": "/topic/:id/:order?",
  "radar": [
    {
      "source": [
        "guancha.cn/"
      ],
      "target": "/:category?"
    }
  ],
  "topFeeds": [
    {
      "description": "观察者网 - 国际 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "113028454025389056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://user.guancha.cn/topic/post-list?topic_id=110&page=1&order=1",
      "title": "观察者网 - 国际",
      "type": "feed",
      "url": "rsshub://guancha/topic/110/1"
    },
    {
      "description": "观察者网 - 风闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150456296214658048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://user.guancha.cn/main/index-list.json?&page=1&order=6",
      "title": "观察者网 - 风闻",
      "type": "feed",
      "url": "rsshub://guancha/topic/0/6"
    }
  ],
  "url": "guancha.cn/"
}
```
