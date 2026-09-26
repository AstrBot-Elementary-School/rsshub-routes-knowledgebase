# 中华人民共和国交通运输部 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov/mot`
- Namespace Name: `中华人民共和国交通运输部`
- Route Path: `/gov/mot/:category{.+}?`
- Route Name: `通用`
- Example: `/gov/mot/xinwen/jiaotongyaowen`
- URL: `www.mot.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ladeng07, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [政策解读](https://www.mot.gov.cn/gongkai/zcjd/)，网址为 `https://www.mot.gov.cn/gongkai/zcjd/`，请截取 `https://www.mot.gov.cn/` 到末尾 `/` 的部分 `gongkai/zcjd` 作为 `category` 参数填入，此时目标路由为 [`/gov/mot/gongkai/zcjd`](https://rsshub.app/gov/mot/gongkai/zcjd)。
:::

## Parameters
- `category`: {"description": "分类，默认为 `xinwen/jiaotongyaowen`，即交通要闻，可在对应分类页 URL 中找到", "options": [{"label": "交通要闻", "value": "xinwen/jiaotongyaowen"}, {"label": "时政要闻", "value": "xinwen/shizhengyaowen"}, {"label": "政策解读", "value": "gongkai/zcjd"}, {"label": "预警提示", "value": "fuwu/yujingtishi"}]}


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
- `title`: `交通要闻`
- `source`:
  - `www.mot.gov.cn/xinwen/jiaotongyaowen/`
- `target`: `/xinwen/jiaotongyaowen`
### Rule 2
- `title`: `时政要闻`
- `source`:
  - `www.mot.gov.cn/xinwen/shizhengyaowen/`
- `target`: `/xinwen/shizhengyaowen`
### Rule 3
- `title`: `政策解读`
- `source`:
  - `www.mot.gov.cn/gongkai/zcjd/`
- `target`: `/gongkai/zcjd`
### Rule 4
- `title`: `预警提示`
- `source`:
  - `www.mot.gov.cn/fuwu/yujingtishi/`
- `target`: `/fuwu/yujingtishi`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [政策解读](https://www.mot.gov.cn/gongkai/zcjd/)，网址为 `https://www.mot.gov.cn/gongkai/zcjd/`，请截取 `https://www.mot.gov.cn/` 到末尾 `/` 的部分 `gongkai/zcjd` 作为 `category` 参数填入，此时目标路由为 [`/gov/mot/gongkai/zcjd`](https://rsshub.app/gov/mot/gongkai/zcjd)。\n:::",
  "example": "/gov/mot/xinwen/jiaotongyaowen",
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
      "description": "分类，默认为 `xinwen/jiaotongyaowen`，即交通要闻，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "交通要闻",
          "value": "xinwen/jiaotongyaowen"
        },
        {
          "label": "时政要闻",
          "value": "xinwen/shizhengyaowen"
        },
        {
          "label": "政策解读",
          "value": "gongkai/zcjd"
        },
        {
          "label": "预警提示",
          "value": "fuwu/yujingtishi"
        }
      ]
    }
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.mot.gov.cn/xinwen/jiaotongyaowen/"
      ],
      "target": "/xinwen/jiaotongyaowen",
      "title": "交通要闻"
    },
    {
      "source": [
        "www.mot.gov.cn/xinwen/shizhengyaowen/"
      ],
      "target": "/xinwen/shizhengyaowen",
      "title": "时政要闻"
    },
    {
      "source": [
        "www.mot.gov.cn/gongkai/zcjd/"
      ],
      "target": "/gongkai/zcjd",
      "title": "政策解读"
    },
    {
      "source": [
        "www.mot.gov.cn/fuwu/yujingtishi/"
      ],
      "target": "/fuwu/yujingtishi",
      "title": "预警提示"
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
