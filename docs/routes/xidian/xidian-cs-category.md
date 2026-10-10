# 西安电子科技大学 - 计算机科学与技术学院

## Coverage
`index-only`

## Route
- Namespace: `xidian`
- Namespace Name: `西安电子科技大学`
- Route Path: `/xidian/cs/:category?`
- Route Name: `计算机科学与技术学院`
- Example: `/xidian/cs/xyxw`
- URL: `cs.xidian.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ZiHao256`
- Source Location: `cs.ts`
- Source Module: `_None_`

## Description
| 文章来源                                      | 参数         |
| --------------------------------------------- | ------------ |
| ✅主页 - 学院新闻                             | xyxw         |
| ✅主页 - 通知公告                             | tzgg         |
| ✅主页 - 交流合作                             | jlhz1        |
| ✅主页 - 人事人才                             | rsrc         |
| ✅主页 - 本科生教育 / 本科教育 - 教学新闻     | bkjy\_jxxw   |
| ✅主页 - 研究生教育 / 研究生教育 - 研究生通知 | yjsjy\_yjstz |
| ✅主页 - 就业招聘                             | jyzhaop      |

## Parameters
- `category`: 通知类别，默认为主页-学院新闻


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
  - `cs.xidian.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 文章来源                                      | 参数         |\n| --------------------------------------------- | ------------ |\n| ✅主页 - 学院新闻                             | xyxw         |\n| ✅主页 - 通知公告                             | tzgg         |\n| ✅主页 - 交流合作                             | jlhz1        |\n| ✅主页 - 人事人才                             | rsrc         |\n| ✅主页 - 本科生教育 / 本科教育 - 教学新闻     | bkjy\\_jxxw   |\n| ✅主页 - 研究生教育 / 研究生教育 - 研究生通知 | yjsjy\\_yjstz |\n| ✅主页 - 就业招聘                             | jyzhaop      |",
  "example": "/xidian/cs/xyxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "cs.ts",
  "maintainers": [
    "ZiHao256"
  ],
  "name": "计算机科学与技术学院",
  "parameters": {
    "category": "通知类别，默认为主页-学院新闻"
  },
  "path": "/cs/:category?",
  "radar": [
    {
      "source": [
        "cs.xidian.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "学院新闻-西安电子科技大学计算机科学与技术学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "109117891452432384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cs.xidian.edu.cn//xyxw.htm",
      "title": "学院新闻-西安电子科技大学计算机科学与技术学院",
      "type": "feed",
      "url": "rsshub://xidian/cs/xyxw"
    },
    {
      "description": "通知公告-西安电子科技大学计算机科学与技术学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "181646857914188800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cs.xidian.edu.cn//tzgg.htm",
      "title": "通知公告-西安电子科技大学计算机科学与技术学院",
      "type": "feed",
      "url": "rsshub://xidian/cs/tzgg"
    }
  ],
  "url": "cs.xidian.edu.cn"
}
```
