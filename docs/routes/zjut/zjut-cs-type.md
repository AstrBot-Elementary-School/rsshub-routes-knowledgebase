# 浙江工业大学 - 浙江工业大学计算机科学与技术学院、软件学院

## Coverage
`index-only`

## Route
- Namespace: `zjut`
- Namespace Name: `浙江工业大学`
- Route Path: `/zjut/cs/:type`
- Route Name: `浙江工业大学计算机科学与技术学院、软件学院`
- Example: `/zjut/cs/54`
- URL: `cs.zjut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `zhullyb`
- Source Location: `cs/index.ts`
- Source Module: `_None_`

## Description
| 新闻资讯 | 学术动态 | 通知公告 |
| -------- | -------- | -------- |
| 54       | 55       | 53       |

## Parameters
- `type`: 分类，见下表


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
  - `cs.zjut.edu.cn/jsp/newsclass.jsp`
- `target`: `/cs/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻资讯 | 学术动态 | 通知公告 |\n| -------- | -------- | -------- |\n| 54       | 55       | 53       |",
  "example": "/zjut/cs/54",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "cs/index.ts",
  "maintainers": [
    "zhullyb"
  ],
  "name": "浙江工业大学计算机科学与技术学院、软件学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/cs/:type",
  "radar": [
    {
      "source": [
        "cs.zjut.edu.cn/jsp/newsclass.jsp"
      ],
      "target": "/cs/:type"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "学院公告 - 浙江工业大学计算机科学与技术学院、软件学院 - Powered by RSSHub",
      "errorAt": "2026-05-02T16:57:53.998Z",
      "errorMessage": "[GET] \"https://cs.zjut.edu.cn/jsp/newsclass.jsp?wcId=53\": 403 Forbidden\n",
      "id": "70401803533121536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cs.zjut.edu.cn/jsp/newsclass.jsp?wcId=53",
      "title": "学院公告 - 浙江工业大学计算机科学与技术学院、软件学院",
      "type": "feed",
      "url": "rsshub://zjut/cs/53"
    },
    {
      "description": "学院新闻 - 浙江工业大学计算机科学与技术学院、软件学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70400085814460416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cs.zjut.edu.cn/jsp/newsclass.jsp?wcId=54",
      "title": "学院新闻 - 浙江工业大学计算机科学与技术学院、软件学院",
      "type": "feed",
      "url": "rsshub://zjut/cs/54"
    }
  ],
  "url": "cs.zjut.edu.cn"
}
```
