# 中债资信评估有限责任公司 - 中债研究

## Coverage
`index-only`

## Route
- Namespace: `chinaratings`
- Namespace Name: `中债资信评估有限责任公司`
- Route Path: `/chinaratings/CreditResearch/:category{.+}?`
- Route Name: `中债研究`
- Example: `/chinaratings/CreditResearch`
- URL: `www.chinaratings.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `credit-research.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [行业评论](https://www.chinaratings.com.cn/CreditResearch/Industry/Comment/)，网址为 `https://www.chinaratings.com.cn/CreditResearch/Industry/Comment/`，请截取 `https://www.chinaratings.com.cn/CreditResearch/` 到末尾 `/` 的部分 `Industry/Comment` 作为 `category` 参数填入，此时目标路由为 [`/chinaratings/CreditResearch/Industry/Comment`](https://rsshub.app/chinaratings/CreditResearch/Industry/Comment)。
:::

## Parameters
- `category`: 分类，默认为 `Industry/Comment`，即行业评论，可在对应分类页 URL 中找到


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
  - `www.chinaratings.com.cn/CreditResearch/:category`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [行业评论](https://www.chinaratings.com.cn/CreditResearch/Industry/Comment/)，网址为 `https://www.chinaratings.com.cn/CreditResearch/Industry/Comment/`，请截取 `https://www.chinaratings.com.cn/CreditResearch/` 到末尾 `/` 的部分 `Industry/Comment` 作为 `category` 参数填入，此时目标路由为 [`/chinaratings/CreditResearch/Industry/Comment`](https://rsshub.app/chinaratings/CreditResearch/Industry/Comment)。\n:::",
  "example": "/chinaratings/CreditResearch",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 21,
  "location": "credit-research.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "中债研究",
  "parameters": {
    "category": "分类，默认为 `Industry/Comment`，即行业评论，可在对应分类页 URL 中找到"
  },
  "path": "/CreditResearch/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.chinaratings.com.cn/CreditResearch/:category"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "行业评论-中债资信评估有限责任公司 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "99579340558865408",
      "image": "https://www.chinaratings.com.cn/news/1913.html",
      "ownerUserId": null,
      "siteUrl": "https://www.chinaratings.com.cn/CreditResearch/Industry/Comment/",
      "title": "行业评论-中债资信评估有限责任公司",
      "type": "feed",
      "url": "rsshub://chinaratings/CreditResearch"
    },
    {
      "description": "专题报告-中债资信评估有限责任公司 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126552501015293952",
      "image": "https://www.chinaratings.com.cn/news/1913.html",
      "ownerUserId": null,
      "siteUrl": "https://www.chinaratings.com.cn/CreditResearch/Industry/TopicReport/",
      "title": "专题报告-中债资信评估有限责任公司",
      "type": "feed",
      "url": "rsshub://chinaratings/CreditResearch/Industry/TopicReport"
    }
  ],
  "url": "www.chinaratings.com.cn",
  "view": 0
}
```
