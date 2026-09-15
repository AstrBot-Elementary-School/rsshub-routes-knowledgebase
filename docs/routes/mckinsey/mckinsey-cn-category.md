# 麦肯锡 - 洞见

## Coverage
`index-only`

## Route
- Namespace: `mckinsey`
- Namespace Name: `麦肯锡`
- Route Path: `/mckinsey/cn/:category?`
- Route Name: `洞见`
- Example: `/mckinsey/cn`
- URL: `mckinsey.com.cn`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `laampui`
- Source Location: `cn/index.ts`
- Source Module: `_None_`

## Description
| 分类                            | 分类名             |
| ------------------------------- | ------------------ |
|                                 | 全部洞见           |
| autos                           | 汽车               |
| banking-insurance               | 金融服务           |
| consumers                       | 消费者             |
| healthcare-pharmaceuticals      | 医药与医疗         |
| business-technology             | 数字化             |
| manufacturing                   | 制造业             |
| technology-media-and-telecom    | 技术，媒体与通信   |
| urbanization-sustainability     | 城市化与可持续发展 |
| innovation                      | 创新               |
| talent-leadership               | 人才与领导力       |
| macroeconomy                    | 宏观经济           |
| mckinsey-global-institute       | 麦肯锡全球研究院   |
| capital-projects-infrastructure | 资本项目和基础设施 |
| 交通运输与物流                  | 旅游、运输和物流   |
| 出海与国际化、转型              | 出海与国际化、转型 |
| 全球基础材料                    | 全球基础材料       |

## Parameters
- `category`: {"default": "最新洞见", "description": "分类，留空为 `最新洞见`", "options": [{"label": "汽车", "value": "autos"}, {"label": "金融服务", "value": "banking-insurance"}, {"label": "消费者", "value": "consumers"}, {"label": "医药与医疗", "value": "healthcare-pharmaceuticals"}, {"label": "数字化", "value": "business-technology"}, {"label": "制造业", "value": "manufacturing"}, {"label": "技术，媒体与通信", "value": "technology-media-and-telecom"}, {"label": "城市化与可持续发展", "value": "urbanization-sustainability"}, {"label": "创新", "value": "innovation"}, {"label": "人才与领导力", "value": "talent-leadership"}, {"label": "宏观经济", "value": "macroeconomy"}, {"label": "麦肯锡全球研究院", "value": "mckinsey-global-institute"}, {"label": "洞见", "value": "insights"}, {"label": "资本项目和基础设施", "value": "capital-projects-infrastructure"}, {"label": "旅游、运输和物流", "value": "交通运输与物流"}, {"label": "全球基础材料", "value": "全球基础材料"}, {"label": "出海与国际化、转型", "value": "出海与国际化、转型"}]}


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
    "finance",
    "popular"
  ],
  "description": "| 分类                            | 分类名             |\n| ------------------------------- | ------------------ |\n|                                 | 全部洞见           |\n| autos                           | 汽车               |\n| banking-insurance               | 金融服务           |\n| consumers                       | 消费者             |\n| healthcare-pharmaceuticals      | 医药与医疗         |\n| business-technology             | 数字化             |\n| manufacturing                   | 制造业             |\n| technology-media-and-telecom    | 技术，媒体与通信   |\n| urbanization-sustainability     | 城市化与可持续发展 |\n| innovation                      | 创新               |\n| talent-leadership               | 人才与领导力       |\n| macroeconomy                    | 宏观经济           |\n| mckinsey-global-institute       | 麦肯锡全球研究院   |\n| capital-projects-infrastructure | 资本项目和基础设施 |\n| 交通运输与物流                  | 旅游、运输和物流   |\n| 出海与国际化、转型              | 出海与国际化、转型 |\n| 全球基础材料                    | 全球基础材料       |",
  "example": "/mckinsey/cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2065,
  "location": "cn/index.ts",
  "maintainers": [
    "laampui"
  ],
  "name": "洞见",
  "parameters": {
    "category": {
      "default": "最新洞见",
      "description": "分类，留空为 `最新洞见`",
      "options": [
        {
          "label": "汽车",
          "value": "autos"
        },
        {
          "label": "金融服务",
          "value": "banking-insurance"
        },
        {
          "label": "消费者",
          "value": "consumers"
        },
        {
          "label": "医药与医疗",
          "value": "healthcare-pharmaceuticals"
        },
        {
          "label": "数字化",
          "value": "business-technology"
        },
        {
          "label": "制造业",
          "value": "manufacturing"
        },
        {
          "label": "技术，媒体与通信",
          "value": "technology-media-and-telecom"
        },
        {
          "label": "城市化与可持续发展",
          "value": "urbanization-sustainability"
        },
        {
          "label": "创新",
          "value": "innovation"
        },
        {
          "label": "人才与领导力",
          "value": "talent-leadership"
        },
        {
          "label": "宏观经济",
          "value": "macroeconomy"
        },
        {
          "label": "麦肯锡全球研究院",
          "value": "mckinsey-global-institute"
        },
        {
          "label": "洞见",
          "value": "insights"
        },
        {
          "label": "资本项目和基础设施",
          "value": "capital-projects-infrastructure"
        },
        {
          "label": "旅游、运输和物流",
          "value": "交通运输与物流"
        },
        {
          "label": "全球基础材料",
          "value": "全球基础材料"
        },
        {
          "label": "出海与国际化、转型",
          "value": "出海与国际化、转型"
        }
      ]
    }
  },
  "path": "/cn/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Insights – McKinsey Greater China - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71830193505483776",
      "image": "https://www.mckinsey.com.cn/wp-content/uploads/2022/07/cropped-620A014D-827F-470B-8E91-990A4222CAE8-270x270.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.mckinsey.com.cn/insights/",
      "title": "Insights – McKinsey Greater China",
      "type": "feed",
      "url": "rsshub://mckinsey/cn/25"
    },
    {
      "description": "Insights – McKinsey Greater China - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55154008868618240",
      "image": "https://www.mckinsey.com.cn/wp-content/uploads/2022/07/cropped-620A014D-827F-470B-8E91-990A4222CAE8-270x270.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.mckinsey.com.cn/insights/",
      "title": "Insights – McKinsey Greater China",
      "type": "feed",
      "url": "rsshub://mckinsey/cn"
    }
  ],
  "view": 0
}
```
