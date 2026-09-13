# 哈尔滨工程大学 - 航天与建筑工程学院

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/hrbeu/cec/:id`
- Route Name: `航天与建筑工程学院`
- Example: `/hrbeu/cec/tzgg`
- URL: `yjsy.hrbeu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `tsinglinrain`
- Source Location: `cec/list.ts`
- Source Module: `_None_`

## Description
汉语拼音和中文不对应，猜测后三个为：教务工作、科研成果、学生工作的拼音。

| 新闻动态 | 通知公告 | 综合办公 | 教务动态 | 科研动态 | 学工动态 |
| :------: | :------: | :------: | :------: | :------: | :------: |
|   xwdt   |   tzgg   |   zhbg   |   jxgz   |   kycg   |   xsgz   |

## Parameters
- `id`: 栏目编号，由 `URL` 中获取。


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
  - `cec.hrbeu.edu.cn/:id/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "汉语拼音和中文不对应，猜测后三个为：教务工作、科研成果、学生工作的拼音。\n\n| 新闻动态 | 通知公告 | 综合办公 | 教务动态 | 科研动态 | 学工动态 |\n| :------: | :------: | :------: | :------: | :------: | :------: |\n|   xwdt   |   tzgg   |   zhbg   |   jxgz   |   kycg   |   xsgz   |",
  "example": "/hrbeu/cec/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cec/list.ts",
  "maintainers": [
    "tsinglinrain"
  ],
  "name": "航天与建筑工程学院",
  "parameters": {
    "id": "栏目编号，由 `URL` 中获取。"
  },
  "path": "/cec/:id",
  "radar": [
    {
      "source": [
        "cec.hrbeu.edu.cn/:id/list.htm"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
