# 北京科技大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `ustb`
- Namespace Name: `北京科技大学`
- Route Path: `/ustb/yjsy/news/:type`
- Route Name: `研究生院`
- Example: `/ustb/yjsy/news/all`
- URL: `gs.ustb.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `DA1Y1`
- Source Location: `yjsy/news.ts`
- Source Module: `_None_`

## Description
| 北京科技大学研究生院 | 土木与资源工程学院 | 能源与环境工程学院 | 冶金与生态工程学院 | 材料科学与工程学院 | 机械工程学院 | 自动化学院 | 计算机与通信工程学院 | 数理学院 | 化学与生物工程学院 | 经济管理学院 | 文法学院 | 马克思主义学院 | 外国语学院 | 国家材料服役安全科学中心 | 新金属材料国家重点实验室 | 工程技术研究院 | 钢铁共性技术协同创新中心 | 钢铁冶金新技术国家重点实验室 | 新材料技术研究院 | 科技史与文化遗产研究院 | 顺德研究生院 |
| -------------------- | ------------------ | ------------------ | ------------------ | ------------------ | ------------ | ---------- | -------------------- | -------- | ------------------ | ------------ | -------- | -------------- | ---------- | ------------------------ | ------------------------ | -------------- | ------------------------ | ---------------------------- | ---------------- | ---------------------- | ------------ |
| all                  | cres               | seee               | metall             | mse                | me           | saee       | scce                 | shuli    | huasheng           | sem          | wenfa    | marx           | sfs        | ncms                     | skl                      | iet            | cicst                    | slam                         | adma             | ihmm                   | sd           |

## Parameters
- `type`: 文章类别


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
  - `gs.ustb.edu.cn/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 北京科技大学研究生院 | 土木与资源工程学院 | 能源与环境工程学院 | 冶金与生态工程学院 | 材料科学与工程学院 | 机械工程学院 | 自动化学院 | 计算机与通信工程学院 | 数理学院 | 化学与生物工程学院 | 经济管理学院 | 文法学院 | 马克思主义学院 | 外国语学院 | 国家材料服役安全科学中心 | 新金属材料国家重点实验室 | 工程技术研究院 | 钢铁共性技术协同创新中心 | 钢铁冶金新技术国家重点实验室 | 新材料技术研究院 | 科技史与文化遗产研究院 | 顺德研究生院 |\n| -------------------- | ------------------ | ------------------ | ------------------ | ------------------ | ------------ | ---------- | -------------------- | -------- | ------------------ | ------------ | -------- | -------------- | ---------- | ------------------------ | ------------------------ | -------------- | ------------------------ | ---------------------------- | ---------------- | ---------------------- | ------------ |\n| all                  | cres               | seee               | metall             | mse                | me           | saee       | scce                 | shuli    | huasheng           | sem          | wenfa    | marx           | sfs        | ncms                     | skl                      | iet            | cicst                    | slam                         | adma             | ihmm                   | sd           |",
  "example": "/ustb/yjsy/news/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "yjsy/news.ts",
  "maintainers": [
    "DA1Y1"
  ],
  "name": "研究生院",
  "parameters": {
    "type": "文章类别"
  },
  "path": "/yjsy/news/:type",
  "radar": [
    {
      "source": [
        "gs.ustb.edu.cn/:type"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "北京科技大学研究生院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75547009398577156",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://gs.ustb.edu.cn/index.php/cms/item-list-category-1049?role=3",
      "title": "最新通知 - 北京科技大学研究生院",
      "type": "feed",
      "url": "rsshub://ustb/yjsy/news/all"
    }
  ]
}
```
