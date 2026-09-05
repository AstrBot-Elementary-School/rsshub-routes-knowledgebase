# 智通财经网 - 推荐

## Coverage
`index-only`

## Route
- Namespace: `zhitongcaijing`
- Namespace Name: `智通财经网`
- Route Path: `/zhitongcaijing/:id?/:category?`
- Route Name: `推荐`
- Example: `/zhitongcaijing`
- URL: `zhitongcaijing.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| id           | 栏目 |
| ------------ | ---- |
| recommend    | 推荐 |
| hkstock      | 港股 |
| meigu        | 美股 |
| agu          | 沪深 |
| ct           | 创投 |
| esg          | ESG  |
| aqs          | 券商 |
| ajj          | 基金 |
| focus        | 要闻 |
| announcement | 公告 |
| research     | 研究 |
| shares       | 新股 |
| bazaar       | 市场 |
| company      | 公司 |

## Parameters
- `id`: 栏目 id，可在对应栏目页 URL 中找到，默认为 recommend，即推荐
- `category`: 分类 id，可在对应栏目子分类页 URL 中找到，默认为全部


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
  "description": "| id           | 栏目 |\n| ------------ | ---- |\n| recommend    | 推荐 |\n| hkstock      | 港股 |\n| meigu        | 美股 |\n| agu          | 沪深 |\n| ct           | 创投 |\n| esg          | ESG  |\n| aqs          | 券商 |\n| ajj          | 基金 |\n| focus        | 要闻 |\n| announcement | 公告 |\n| research     | 研究 |\n| shares       | 新股 |\n| bazaar       | 市场 |\n| company      | 公司 |",
  "example": "/zhitongcaijing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 515,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "推荐",
  "parameters": {
    "category": "分类 id，可在对应栏目子分类页 URL 中找到，默认为全部",
    "id": "栏目 id，可在对应栏目页 URL 中找到，默认为 recommend，即推荐"
  },
  "path": "/:id?/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "智通财经 - 推荐 - Powered by RSSHub",
      "errorAt": "2026-06-28T03:42:52.637Z",
      "errorMessage": "Cannot read properties of undefined (reading 'slice')\nFailed to fetch\n",
      "id": "63376992073142278",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhitongcaijing.com/content/recommend.html",
      "title": "智通财经 - 推荐",
      "type": "feed",
      "url": "rsshub://zhitongcaijing"
    },
    {
      "description": "智通财经 - 推荐 - Powered by RSSHub",
      "errorAt": "2026-06-03T14:02:14.769Z",
      "errorMessage": "Cannot read properties of undefined (reading 'slice')\n",
      "id": "72559122759839744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhitongcaijing.com/content/recommend.html",
      "title": "智通财经 - 推荐",
      "type": "feed",
      "url": "rsshub://zhitongcaijing/recommend"
    }
  ],
  "view": 0
}
```
