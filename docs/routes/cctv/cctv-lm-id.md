# 央视新闻 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cctv`
- Namespace Name: `央视新闻`
- Route Path: `/cctv/lm/:id?`
- Route Name: `栏目`
- Example: `/cctv/lm/xwzk`
- URL: `news.cctv.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `lm.ts`
- Source Module: `_None_`

## Description
| 焦点访谈 | 等着我 | 今日说法 | 开讲啦 |
| -------- | ------ | -------- | ------ |
| jdft     | dzw    | jrsf     | kjl    |

| 正大综艺 | 经济半小时 | 第一动画乐园 |
| -------- | ---------- | ------------ |
| zdzy     | jjbxs      | dydhly       |

::: tip
更多栏目请看 [这里](https://tv.cctv.com/lm)
:::

## Parameters
- `id`: 栏目 id，可在对应栏目页 URL 中找到，默认为 `xwzk` 即 新闻周刊


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
  - `news.cctv.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 焦点访谈 | 等着我 | 今日说法 | 开讲啦 |\n| -------- | ------ | -------- | ------ |\n| jdft     | dzw    | jrsf     | kjl    |\n\n| 正大综艺 | 经济半小时 | 第一动画乐园 |\n| -------- | ---------- | ------------ |\n| zdzy     | jjbxs      | dydhly       |\n\n::: tip\n更多栏目请看 [这里](https://tv.cctv.com/lm)\n:::",
  "example": "/cctv/lm/xwzk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 208,
  "location": "lm.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，可在对应栏目页 URL 中找到，默认为 `xwzk` 即 新闻周刊"
  },
  "path": "/lm/:id?",
  "radar": [
    {
      "source": [
        "news.cctv.com/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "眼下的中国,变化剧烈,选择什么样的新闻,以什么样的眼光,能将过去七天的中国浓缩在一本45分钟的电视新闻杂志里,是我们每天都在不停思索的问题。我们追求的是希望作一本有理想、有责任感、有尊严、能够记录历史的新闻杂志,而我们更期待的是,能在与您的沟通交流中获得启迪,因为这是我们一起经历的时代。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59165786861326336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tv.cctv.com/lm/xwzk/videoset",
      "title": "新闻周刊视频_央视网(cctv.com)",
      "type": "feed",
      "url": "rsshub://cctv/lm/xwzk"
    },
    {
      "description": "《焦点访谈》于1994年由中央电视台新闻评论部创办,节目定位是:时事追踪报道,新闻背景分析,社会热点透视,大众话题评说。它以深度报道为主,以舆论监督见长,是中央电视台收视率最高的栏目之一,多次获中国新闻界最高奖项。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59774961107766272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tv.cctv.com/lm/jdft/videoset",
      "title": "焦点访谈视频_央视网(cctv.com)",
      "type": "feed",
      "url": "rsshub://cctv/lm/jdft"
    }
  ]
}
```
