# 格隆汇 - 首页

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/gelonghui/home/:tag?`
- Route Name: `首页`
- Example: `/gelonghui/home`
- URL: `gelonghui.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `home.ts`
- Source Module: `_None_`

## Description
| 推荐            | 股票  | 基金 | 新股       | 研报     |
| --------------- | ----- | ---- | ---------- | -------- |
| web\_home\_page | stock | fund | new\_stock | research |

## Parameters
- `tag`: {"description": "分类标签，见下表，默认为 `web_home_page`", "options": [{"label": "推荐", "value": "web_home_page"}, {"label": "股票", "value": "stock"}, {"label": "基金", "value": "fund"}, {"label": "新股", "value": "new_stock"}, {"label": "研报", "value": "research"}]}


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
    "finance"
  ],
  "description": "| 推荐            | 股票  | 基金 | 新股       | 研报     |\n| --------------- | ----- | ---- | ---------- | -------- |\n| web\\_home\\_page | stock | fund | new\\_stock | research |",
  "example": "/gelonghui/home",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 645,
  "location": "home.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "首页",
  "parameters": {
    "tag": {
      "description": "分类标签，见下表，默认为 `web_home_page`",
      "options": [
        {
          "label": "推荐",
          "value": "web_home_page"
        },
        {
          "label": "股票",
          "value": "stock"
        },
        {
          "label": "基金",
          "value": "fund"
        },
        {
          "label": "新股",
          "value": "new_stock"
        },
        {
          "label": "研报",
          "value": "research"
        }
      ]
    }
  },
  "path": "/home/:tag?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "格隆汇为中国投资者出海投资及中国公司出海融资,提供海外投资,港股开户行情,科创板股票发行数据、资讯、研究、交易等一站式服务,目前业务范围主要涉及港股与美股两大市场,未来将陆续开通台湾、日本、印度、欧洲等市场. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61615021957515264",
      "image": "https://cdn.gelonghui.com/static/web/www.ico.la.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/",
      "title": "格隆汇-财经资讯动态-股市行情",
      "type": "feed",
      "url": "rsshub://gelonghui/home"
    },
    {
      "description": "格隆汇为中国投资者出海投资及中国公司出海融资,提供海外投资,港股开户行情,科创板股票发行数据、资讯、研究、交易等一站式服务,目前业务范围主要涉及港股与美股两大市场,未来将陆续开通台湾、日本、印度、欧洲等市场. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72552727933810688",
      "image": "https://cdn.gelonghui.com/static/web/www.ico.la.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/",
      "title": "格隆汇-财经资讯动态-股市行情",
      "type": "feed",
      "url": "rsshub://gelonghui/home/web_home_page"
    }
  ],
  "view": 0
}
```
