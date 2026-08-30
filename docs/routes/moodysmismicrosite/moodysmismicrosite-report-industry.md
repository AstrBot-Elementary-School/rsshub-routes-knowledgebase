# 穆迪评级 - industry

## Coverage
`index-only`

## Route
- Namespace: `moodysmismicrosite`
- Namespace Name: `穆迪评级`
- Route Path: `/moodysmismicrosite/report/:industry?`
- Route Name: `industry`
- Example: `/moodysmismicrosite/report/企业&金融机构`
- URL: `www.moodysmismicrosite.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Cedaric`
- Source Location: `report.ts`
- Source Module: `_None_`

## Description
| ID | Description        |
| -- | ------------------ |
| 0  | 企业               |
| 1  | 金融机构           |
| 2  | 主权               |
| 3  | 地方政府及城投公司 |
| 4  | 宏观经济           |
| 5  | 结构融资           |
| 6  | 基础设施项目融资   |
| 7  | ESG                |
| 8  | 其他               |

## Parameters
- `industry`: {"default": "全部", "description": "可选参数，默认为全部行业。行业选择，支持使用&连接多个。", "options": [{"label": "企业", "value": "0"}, {"label": "金融机构", "value": "1"}, {"label": "主权", "value": "2"}, {"label": "地方政府及城投公司", "value": "3"}, {"label": "宏观经济", "value": "4"}, {"label": "结构融资", "value": "5"}, {"label": "基础设施及项目融资", "value": "6"}, {"label": "ESG", "value": "7"}, {"label": "其他", "value": "8"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.moodysmismicrosite.com/report`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| ID | Description        |\n| -- | ------------------ |\n| 0  | 企业               |\n| 1  | 金融机构           |\n| 2  | 主权               |\n| 3  | 地方政府及城投公司 |\n| 4  | 宏观经济           |\n| 5  | 结构融资           |\n| 6  | 基础设施项目融资   |\n| 7  | ESG                |\n| 8  | 其他               |",
  "example": "/moodysmismicrosite/report/企业&金融机构",
  "heat": 159,
  "location": "report.ts",
  "maintainers": [
    "Cedaric"
  ],
  "name": "industry",
  "parameters": {
    "industry": {
      "default": "全部",
      "description": "可选参数，默认为全部行业。行业选择，支持使用&连接多个。",
      "options": [
        {
          "label": "企业",
          "value": "0"
        },
        {
          "label": "金融机构",
          "value": "1"
        },
        {
          "label": "主权",
          "value": "2"
        },
        {
          "label": "地方政府及城投公司",
          "value": "3"
        },
        {
          "label": "宏观经济",
          "value": "4"
        },
        {
          "label": "结构融资",
          "value": "5"
        },
        {
          "label": "基础设施及项目融资",
          "value": "6"
        },
        {
          "label": "ESG",
          "value": "7"
        },
        {
          "label": "其他",
          "value": "8"
        }
      ]
    }
  },
  "path": "/report/:industry?",
  "radar": [
    {
      "source": [
        "www.moodysmismicrosite.com/report"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "穆迪评级(全部) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150839360846191616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.moodysmismicrosite.com/report",
      "title": "穆迪评级(全部)",
      "type": "feed",
      "url": "rsshub://moodysmismicrosite/report/%E5%85%A8%E9%83%A8"
    },
    {
      "description": "穆迪评级(宏观经济&主权&行业&地方政府及城投公司) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "94559628931010560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.moodysmismicrosite.com/report",
      "title": "穆迪评级(宏观经济&主权&行业&地方政府及城投公司)",
      "type": "feed",
      "url": "rsshub://moodysmismicrosite/report/%E5%AE%8F%E8%A7%82%E7%BB%8F%E6%B5%8E&%E4%B8%BB%E6%9D%83&%E8%A1%8C%E4%B8%9A&%E5%9C%B0%E6%96%B9%E6%94%BF%E5%BA%9C%E5%8F%8A%E5%9F%8E%E6%8A%95%E5%85%AC%E5%8F%B8"
    }
  ],
  "view": 0
}
```
