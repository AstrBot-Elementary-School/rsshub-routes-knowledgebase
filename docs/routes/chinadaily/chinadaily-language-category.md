# 中国日报网 - 英语点津

## Coverage
`index-only`

## Route
- Namespace: `chinadaily`
- Namespace Name: `中国日报网`
- Route Path: `/chinadaily/language/:category{.+}?`
- Route Name: `英语点津`
- Example: `/chinadaily/language/thelatest`
- URL: `language.chinadaily.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `language.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [精彩推荐](https://language.chinadaily.com.cn/thelatest)，网址为 `https://language.chinadaily.com.cn/thelatest`，请截取 `https://language.chinadaily.com.cn/` 到末尾的部分 `thelatest` 作为 `category` 参数填入，此时目标路由为 [`/chinadaily/language/thelatest`](https://rsshub.app/chinadaily/language/thelatest)。
:::

<details>
  <summary>更多分类</summary>

| 分类                                                                         | ID                                                                                                        |
| ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| [精彩推荐](https://language.chinadaily.com.cn/thelatest)                     | [thelatest](https://rsshub.app/chinadaily/language/thelatest)                                             |
| [每日一词](https://language.chinadaily.com.cn/news_hotwords/word_of_the_day) | [news\_hotwords/word\_of\_the\_day](https://rsshub.app/chinadaily/language/news_hotwords/word_of_the_day) |
| [双语新闻](https://language.chinadaily.com.cn/news_bilingual)                | [news\_bilingual](https://rsshub.app/chinadaily/language/news_bilingual)                                  |
| [新闻热词](https://language.chinadaily.com.cn/news_hotwords)                 | [news\_hotwords](https://rsshub.app/chinadaily/language/news_hotwords)                                    |
| [实用口语](https://language.chinadaily.com.cn/practice_tongue)               | [practice\_tongue](https://rsshub.app/chinadaily/language/practice_tongue)                                |
| [译词课堂](https://language.chinadaily.com.cn/trans_collect)                 | [trans\_collect](https://rsshub.app/chinadaily/language/trans_collect)                                    |
| [图片新闻](https://language.chinadaily.com.cn/news_photo)                    | [news\_photo](https://rsshub.app/chinadaily/language/news_photo)                                          |
| [视频精选](https://language.chinadaily.com.cn/video_links)                   | [video\_links](https://rsshub.app/chinadaily/language/video_links)                                        |
| [新闻播报](https://language.chinadaily.com.cn/audio_cd)                      | [audio\_cd](https://rsshub.app/chinadaily/language/audio_cd)                                              |
| [专栏作家](https://language.chinadaily.com.cn/columnist)                     | [audio\_cd](https://rsshub.app/chinadaily/language/columnist)                                             |
| [权威发布](https://language.chinadaily.com.cn/5af95d44a3103f6866ee845c)      | [5af95d44a3103f6866ee845c](https://rsshub.app/chinadaily/language/5af95d44a3103f6866ee845c)               |

</details>

## Parameters
- `category`: {"description": "分类，默认为 `thelatest`，即精彩推荐，可在对应分类页 URL 中找到, Category, `thelatest`，即精彩推荐  by default", "options": [{"label": "精彩推荐", "value": "thelatest"}, {"label": "每日一词", "value": "news_hotwords/word_of_the_day"}, {"label": "双语新闻", "value": "news_bilingual"}, {"label": "新闻热词", "value": "news_hotwords"}, {"label": "实用口语", "value": "practice_tongue"}, {"label": "译词课堂", "value": "trans_collect"}, {"label": "图片新闻", "value": "news_photo"}, {"label": "视频精选", "value": "video_links"}, {"label": "新闻播报", "value": "audio_cd"}, {"label": "专栏作家", "value": "columnist"}, {"label": "权威发布", "value": "5af95d44a3103f6866ee845c"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `language.chinadaily.com.cn/:category`
### Rule 2
- `title`: `精彩推荐`
- `source`:
  - `language.chinadaily.com.cn/thelatest`
- `target`: `/language/thelatest`
### Rule 3
- `title`: `每日一词`
- `source`:
  - `language.chinadaily.com.cn/news_hotwords/word_of_the_day`
- `target`: `/language/news_hotwords/word_of_the_day`
### Rule 4
- `title`: `双语新闻`
- `source`:
  - `language.chinadaily.com.cn/news_bilingual`
- `target`: `/language/news_bilingual`
### Rule 5
- `title`: `新闻热词`
- `source`:
  - `language.chinadaily.com.cn/news_hotwords`
- `target`: `/language/news_hotwords`
### Rule 6
- `title`: `实用口语`
- `source`:
  - `language.chinadaily.com.cn/practice_tongue`
- `target`: `/language/practice_tongue`
### Rule 7
- `title`: `译词课堂`
- `source`:
  - `language.chinadaily.com.cn/trans_collect`
- `target`: `/language/trans_collect`
### Rule 8
- `title`: `图片新闻`
- `source`:
  - `language.chinadaily.com.cn/news_photo`
- `target`: `/language/news_photo`
### Rule 9
- `title`: `视频精选`
- `source`:
  - `language.chinadaily.com.cn/video_links`
- `target`: `/language/video_links`
### Rule 10
- `title`: `新闻播报`
- `source`:
  - `language.chinadaily.com.cn/audio_cd`
- `target`: `/language/audio_cd`
### Rule 11
- `title`: `专栏作家`
- `source`:
  - `language.chinadaily.com.cn/columnist`
- `target`: `/language/columnist`
### Rule 12
- `title`: `权威发布`
- `source`:
  - `language.chinadaily.com.cn/5af95d44a3103f6866ee845c`
- `target`: `/language/5af95d44a3103f6866ee845c`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n若订阅 [精彩推荐](https://language.chinadaily.com.cn/thelatest)，网址为 `https://language.chinadaily.com.cn/thelatest`，请截取 `https://language.chinadaily.com.cn/` 到末尾的部分 `thelatest` 作为 `category` 参数填入，此时目标路由为 [`/chinadaily/language/thelatest`](https://rsshub.app/chinadaily/language/thelatest)。\n:::\n\n<details>\n  <summary>更多分类</summary>\n\n| 分类                                                                         | ID                                                                                                        |\n| ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |\n| [精彩推荐](https://language.chinadaily.com.cn/thelatest)                     | [thelatest](https://rsshub.app/chinadaily/language/thelatest)                                             |\n| [每日一词](https://language.chinadaily.com.cn/news_hotwords/word_of_the_day) | [news\\_hotwords/word\\_of\\_the\\_day](https://rsshub.app/chinadaily/language/news_hotwords/word_of_the_day) |\n| [双语新闻](https://language.chinadaily.com.cn/news_bilingual)                | [news\\_bilingual](https://rsshub.app/chinadaily/language/news_bilingual)                                  |\n| [新闻热词](https://language.chinadaily.com.cn/news_hotwords)                 | [news\\_hotwords](https://rsshub.app/chinadaily/language/news_hotwords)                                    |\n| [实用口语](https://language.chinadaily.com.cn/practice_tongue)               | [practice\\_tongue](https://rsshub.app/chinadaily/language/practice_tongue)                                |\n| [译词课堂](https://language.chinadaily.com.cn/trans_collect)                 | [trans\\_collect](https://rsshub.app/chinadaily/language/trans_collect)                                    |\n| [图片新闻](https://language.chinadaily.com.cn/news_photo)                    | [news\\_photo](https://rsshub.app/chinadaily/language/news_photo)                                          |\n| [视频精选](https://language.chinadaily.com.cn/video_links)                   | [video\\_links](https://rsshub.app/chinadaily/language/video_links)                                        |\n| [新闻播报](https://language.chinadaily.com.cn/audio_cd)                      | [audio\\_cd](https://rsshub.app/chinadaily/language/audio_cd)                                              |\n| [专栏作家](https://language.chinadaily.com.cn/columnist)                     | [audio\\_cd](https://rsshub.app/chinadaily/language/columnist)                                             |\n| [权威发布](https://language.chinadaily.com.cn/5af95d44a3103f6866ee845c)      | [5af95d44a3103f6866ee845c](https://rsshub.app/chinadaily/language/5af95d44a3103f6866ee845c)               |\n\n</details>",
  "example": "/chinadaily/language/thelatest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 39,
  "location": "language.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "英语点津",
  "parameters": {
    "category": {
      "description": "分类，默认为 `thelatest`，即精彩推荐，可在对应分类页 URL 中找到, Category, `thelatest`，即精彩推荐  by default",
      "options": [
        {
          "label": "精彩推荐",
          "value": "thelatest"
        },
        {
          "label": "每日一词",
          "value": "news_hotwords/word_of_the_day"
        },
        {
          "label": "双语新闻",
          "value": "news_bilingual"
        },
        {
          "label": "新闻热词",
          "value": "news_hotwords"
        },
        {
          "label": "实用口语",
          "value": "practice_tongue"
        },
        {
          "label": "译词课堂",
          "value": "trans_collect"
        },
        {
          "label": "图片新闻",
          "value": "news_photo"
        },
        {
          "label": "视频精选",
          "value": "video_links"
        },
        {
          "label": "新闻播报",
          "value": "audio_cd"
        },
        {
          "label": "专栏作家",
          "value": "columnist"
        },
        {
          "label": "权威发布",
          "value": "5af95d44a3103f6866ee845c"
        }
      ]
    }
  },
  "path": "/language/:category{.+}?",
  "radar": [
    {
      "source": [
        "language.chinadaily.com.cn/:category"
      ]
    },
    {
      "source": [
        "language.chinadaily.com.cn/thelatest"
      ],
      "target": "/language/thelatest",
      "title": "精彩推荐"
    },
    {
      "source": [
        "language.chinadaily.com.cn/news_hotwords/word_of_the_day"
      ],
      "target": "/language/news_hotwords/word_of_the_day",
      "title": "每日一词"
    },
    {
      "source": [
        "language.chinadaily.com.cn/news_bilingual"
      ],
      "target": "/language/news_bilingual",
      "title": "双语新闻"
    },
    {
      "source": [
        "language.chinadaily.com.cn/news_hotwords"
      ],
      "target": "/language/news_hotwords",
      "title": "新闻热词"
    },
    {
      "source": [
        "language.chinadaily.com.cn/practice_tongue"
      ],
      "target": "/language/practice_tongue",
      "title": "实用口语"
    },
    {
      "source": [
        "language.chinadaily.com.cn/trans_collect"
      ],
      "target": "/language/trans_collect",
      "title": "译词课堂"
    },
    {
      "source": [
        "language.chinadaily.com.cn/news_photo"
      ],
      "target": "/language/news_photo",
      "title": "图片新闻"
    },
    {
      "source": [
        "language.chinadaily.com.cn/video_links"
      ],
      "target": "/language/video_links",
      "title": "视频精选"
    },
    {
      "source": [
        "language.chinadaily.com.cn/audio_cd"
      ],
      "target": "/language/audio_cd",
      "title": "新闻播报"
    },
    {
      "source": [
        "language.chinadaily.com.cn/columnist"
      ],
      "target": "/language/columnist",
      "title": "专栏作家"
    },
    {
      "source": [
        "language.chinadaily.com.cn/5af95d44a3103f6866ee845c"
      ],
      "target": "/language/5af95d44a3103f6866ee845c",
      "title": "权威发布"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "精彩推荐 - 中国日报网英语点津-LanguageTips - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "140547468012002304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://language.chinadaily.com.cn/thelatest",
      "title": "精彩推荐 - 中国日报网英语点津-LanguageTips",
      "type": "feed",
      "url": "rsshub://chinadaily/language/thelatest"
    },
    {
      "description": "精彩推荐 - 中国日报网英语点津-LanguageTips - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "164468082809828352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://language.chinadaily.com.cn/thelatest",
      "title": "精彩推荐 - 中国日报网英语点津-LanguageTips",
      "type": "feed",
      "url": "rsshub://chinadaily/language"
    }
  ],
  "url": "language.chinadaily.com.cn",
  "view": 0
}
```
