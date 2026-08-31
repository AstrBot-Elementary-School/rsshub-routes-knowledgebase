# 中山大学 - 粤港澳发展研究院

## Coverage
`index-only`

## Route
- Namespace: `sysu`
- Namespace Name: `中山大学`
- Route Path: `/sysu/ygafz/:type?`
- Route Name: `粤港澳发展研究院`
- Example: `/sysu/ygafz`
- URL: `cse.sysu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `TonyRL`
- Source Location: `ygafz.ts`
- Source Module: `_None_`

## Description
| 人才招聘   | 人才培养      | 新闻动态 | 通知公告 | 专家观点 |
| ---------- | ------------- | -------- | -------- | -------- |
| jobopening | personnelplan | news     | notice   | opinion  |

| 研究成果 | 研究论文 | 学术著作 | 形势政策 |
| -------- | -------- | -------- | -------- |
| results  | papers   | writings | policy   |

## Parameters
- `type`: 分类，见下表，默认为 `notice`


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ygafz.sysu.edu.cn/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 人才招聘   | 人才培养      | 新闻动态 | 通知公告 | 专家观点 |\n| ---------- | ------------- | -------- | -------- | -------- |\n| jobopening | personnelplan | news     | notice   | opinion  |\n\n| 研究成果 | 研究论文 | 学术著作 | 形势政策 |\n| -------- | -------- | -------- | -------- |\n| results  | papers   | writings | policy   |",
  "example": "/sysu/ygafz",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "ygafz.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "粤港澳发展研究院",
  "parameters": {
    "type": "分类，见下表，默认为 `notice`"
  },
  "path": "/ygafz/:type?",
  "radar": [
    {
      "source": [
        "ygafz.sysu.edu.cn/:type?"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
