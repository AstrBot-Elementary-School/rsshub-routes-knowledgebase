# 中华人民共和国交通运输部 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/mot`
- Namespace Name: `中华人民共和国交通运输部`
- Route Path: `/gov/mot/:category{.+}?`
- Route Name: `通用`
- Example: `/gov/mot/jiaotongyaowen`
- URL: `www.mot.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ladeng07, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [重要会议](https://www.mot.gov.cn/zhongyaohuiyi/)，网址为 `https://www.mot.gov.cn/zhongyaohuiyi/`，请截取 `https://www.mot.gov.cn/` 到末尾 `/` 的部分 `zhongyaohuiyi` 作为 `category` 参数填入，此时目标路由为 [`/gov/mot/zhongyaohuiyi`](https://rsshub.app/gov/mot/zhongyaohuiyi)。
:::

## Parameters
- `category`: {"description": "分类，默认为 `jiaotongyaowen`，即交通要闻，可在对应分类页 URL 中找到", "options": [{"label": "交通要闻", "value": "jiaotongyaowen"}, {"label": "时政要闻", "value": "shizhengyaowen"}, {"label": "重要会议", "value": "zhongyaohuiyi"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.mot.gov.cn/:category`
### Rule 2
- `title`: `交通要闻`
- `source`:
  - `www.mot.gov.cn/jiaotongyaowen/`
- `target`: `/jiaotongyaowen`
### Rule 3
- `title`: `时政要闻`
- `source`:
  - `www.mot.gov.cn/shizhengyaowen/`
- `target`: `/shizhengyaowen`
### Rule 4
- `title`: `重要会议`
- `source`:
  - `www.mot.gov.cn/zhongyaohuiyi/`
- `target`: `/zhongyaohuiyi`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [重要会议](https://www.mot.gov.cn/zhongyaohuiyi/)，网址为 `https://www.mot.gov.cn/zhongyaohuiyi/`，请截取 `https://www.mot.gov.cn/` 到末尾 `/` 的部分 `zhongyaohuiyi` 作为 `category` 参数填入，此时目标路由为 [`/gov/mot/zhongyaohuiyi`](https://rsshub.app/gov/mot/zhongyaohuiyi)。\n:::",
  "example": "/gov/mot/jiaotongyaowen",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "index.ts",
  "maintainers": [
    "ladeng07",
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "category": {
      "description": "分类，默认为 `jiaotongyaowen`，即交通要闻，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "交通要闻",
          "value": "jiaotongyaowen"
        },
        {
          "label": "时政要闻",
          "value": "shizhengyaowen"
        },
        {
          "label": "重要会议",
          "value": "zhongyaohuiyi"
        }
      ]
    }
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.mot.gov.cn/:category"
      ]
    },
    {
      "source": [
        "www.mot.gov.cn/jiaotongyaowen/"
      ],
      "target": "/jiaotongyaowen",
      "title": "交通要闻"
    },
    {
      "source": [
        "www.mot.gov.cn/shizhengyaowen/"
      ],
      "target": "/shizhengyaowen",
      "title": "时政要闻"
    },
    {
      "source": [
        "www.mot.gov.cn/zhongyaohuiyi/"
      ],
      "target": "/zhongyaohuiyi",
      "title": "重要会议"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中华人民共和国交通运输部,, 交通要闻栏目最新信息发布，想了解“交通要闻”相关信息，请点击访问！ - Powered by RSSHub",
      "errorAt": "2025-10-07T16:03:30.077Z",
      "errorMessage": "[GET] \"https://www.mot.gov.cn/jiaotongyaowen/\": 404 Not Found\n",
      "id": "145746403274138624",
      "image": "https://www.mot.gov.cn/images/h_logo0625.png",
      "ownerUserId": null,
      "siteUrl": "https://www.mot.gov.cn/jiaotongyaowen/",
      "title": "交通要闻--中华人民共和国交通运输部",
      "type": "feed",
      "url": "rsshub://gov/mot/jiaotongyaowen"
    }
  ],
  "url": "www.mot.gov.cn",
  "view": 0
}
```
