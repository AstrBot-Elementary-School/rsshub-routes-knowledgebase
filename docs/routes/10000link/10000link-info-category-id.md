# 10000万联网 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `10000link`
- Namespace Name: `10000万联网`
- Route Path: `/10000link/info/:category?/:id?`
- Route Name: `新闻`
- Example: `/10000link/info/newslists/My01`
- URL: `info.10000link.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `info.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [天下大势](https://info.10000link.com/newslists.aspx?chid=My01)，网址为 `https://info.10000link.com/newslists.aspx?chid=My01`，请截取 `https://info.10000link.com/` 到末尾 `.aspx` 的部分 `newslists` 作为 `category` 参数填入，而 `My01` 作为 `id` 参数填入，此时目标路由为 [`/10000link/info/newslists/My01`](https://rsshub.app/10000link/info/newslists/My01)。
:::

| 金融科技      | 物流          | 供应链金融风控 | 区块链         | B2B       |
| ------------- | ------------- | -------------- | -------------- | --------- |
| newsFinancial | newslogistics | newsRisk       | newsBlockChain | newsBTwoB |

| 跨境电商        | 投融资         | 供应链管理     | 供应链创新     | 数据          |
| --------------- | -------------- | -------------- | -------------- | ------------- |
| newsCrossborder | newsInvestment | newsManagement | newsInnovation | newslists/A02 |

| 政策          | 规划          | 案例           | 职场         | 供应链票据 |
| ------------- | ------------- | -------------- | ------------ | ---------- |
| newslists/A03 | newslists/A04 | newslists/GL03 | newslists/ZC | newsBill   |

## Parameters
- `category`: {"description": "分类，默认为 `newslists`，可在对应分类页 URL 中找到", "options": [{"label": "新闻", "value": "newslists"}, {"label": "物流", "value": "newslogistics"}, {"label": "供应链金融风控", "value": "newsRisk"}, {"label": "区块链", "value": "newsBlockChain"}, {"label": "B2B", "value": "newsBTwoB"}, {"label": "跨境电商", "value": "newsCrossborder"}, {"label": "投融资", "value": "newsInvestment"}, {"label": "供应链管理", "value": "newsManagement"}, {"label": "供应链创新", "value": "newsInnovation"}, {"label": "数据", "value": "newslists/A02"}, {"label": "政策", "value": "newslists/A03"}, {"label": "规划", "value": "newslists/A04"}, {"label": "案例", "value": "newslists/GL03"}, {"label": "职场", "value": "newslists/ZC"}, {"label": "供应链票据", "value": "newsBill"}]}
- `id`: {"description": "ID，默认为空，可在对应分类页 URL 中找到"}


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
  - `info.10000link.com/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [天下大势](https://info.10000link.com/newslists.aspx?chid=My01)，网址为 `https://info.10000link.com/newslists.aspx?chid=My01`，请截取 `https://info.10000link.com/` 到末尾 `.aspx` 的部分 `newslists` 作为 `category` 参数填入，而 `My01` 作为 `id` 参数填入，此时目标路由为 [`/10000link/info/newslists/My01`](https://rsshub.app/10000link/info/newslists/My01)。\n:::\n\n| 金融科技      | 物流          | 供应链金融风控 | 区块链         | B2B       |\n| ------------- | ------------- | -------------- | -------------- | --------- |\n| newsFinancial | newslogistics | newsRisk       | newsBlockChain | newsBTwoB |\n\n| 跨境电商        | 投融资         | 供应链管理     | 供应链创新     | 数据          |\n| --------------- | -------------- | -------------- | -------------- | ------------- |\n| newsCrossborder | newsInvestment | newsManagement | newsInnovation | newslists/A02 |\n\n| 政策          | 规划          | 案例           | 职场         | 供应链票据 |\n| ------------- | ------------- | -------------- | ------------ | ---------- |\n| newslists/A03 | newslists/A04 | newslists/GL03 | newslists/ZC | newsBill   |",
  "example": "/10000link/info/newslists/My01",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 11,
  "location": "info.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "category": {
      "description": "分类，默认为 `newslists`，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "新闻",
          "value": "newslists"
        },
        {
          "label": "物流",
          "value": "newslogistics"
        },
        {
          "label": "供应链金融风控",
          "value": "newsRisk"
        },
        {
          "label": "区块链",
          "value": "newsBlockChain"
        },
        {
          "label": "B2B",
          "value": "newsBTwoB"
        },
        {
          "label": "跨境电商",
          "value": "newsCrossborder"
        },
        {
          "label": "投融资",
          "value": "newsInvestment"
        },
        {
          "label": "供应链管理",
          "value": "newsManagement"
        },
        {
          "label": "供应链创新",
          "value": "newsInnovation"
        },
        {
          "label": "数据",
          "value": "newslists/A02"
        },
        {
          "label": "政策",
          "value": "newslists/A03"
        },
        {
          "label": "规划",
          "value": "newslists/A04"
        },
        {
          "label": "案例",
          "value": "newslists/GL03"
        },
        {
          "label": "职场",
          "value": "newslists/ZC"
        },
        {
          "label": "供应链票据",
          "value": "newsBill"
        }
      ]
    },
    "id": {
      "description": "ID，默认为空，可在对应分类页 URL 中找到"
    }
  },
  "path": "/info/:category?/:id?",
  "radar": [
    {
      "source": [
        "info.10000link.com/:category"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "国资委最新要求：将合规嵌入业务，对虚假贸易、违规支付佣金等开展源头治理 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "138893356640117760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://info.10000link.com/newslists.aspx?chid=My01",
      "title": "10000万联网 - 国资委最新要求：将合规嵌入业务，对虚假贸易、违规支付佣金等开展源头治理",
      "type": "feed",
      "url": "rsshub://10000link/info/newslists/My01"
    },
    {
      "description": "国资委重磅发文：绿色低碳供应链成为央企硬性绩效考核！不懂“绿”，央企领导的帽子和票子可能不稳！ - Powered by RSSHub",
      "errorAt": "2026-05-19T12:43:23.284Z",
      "errorMessage": "Failed to fetch\n",
      "id": "166018536566226944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://info.10000link.com/newslists.aspx",
      "title": "10000万联网 - 国资委重磅发文：绿色低碳供应链成为央企硬性绩效考核！不懂“绿”，央企领导的帽子和票子可能不稳！",
      "type": "feed",
      "url": "rsshub://10000link/info"
    }
  ],
  "url": "info.10000link.com",
  "view": 0
}
```
