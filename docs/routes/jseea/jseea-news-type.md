# 江苏省教育考试院 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `jseea`
- Namespace Name: `江苏省教育考试院`
- Route Path: `/jseea/news/:type?`
- Route Name: `新闻中心`
- Example: `/jseea/news/zkyw`
- URL: `jseea.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `schen1024`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 招考要闻 | 教育动态 | 招考信息 | 政策文件 | 院校动态 |
| :------: | :------: | :------: | :------: | :------: |
|   zkyw   |   jydt   |   zkxx   |   zcwj   |   yxdt   |

## Parameters
- `type`: 分类，默认为 `zkyw`，具体参数见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `jseea.cn/webfile/news/:type`
- `target`: `/news/:type`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 招考要闻 | 教育动态 | 招考信息 | 政策文件 | 院校动态 |\n| :------: | :------: | :------: | :------: | :------: |\n|   zkyw   |   jydt   |   zkxx   |   zcwj   |   yxdt   |",
  "example": "/jseea/news/zkyw",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "schen1024"
  ],
  "name": "新闻中心",
  "parameters": {
    "type": "分类，默认为 `zkyw`，具体参数见下表"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "jseea.cn/webfile/news/:type"
      ],
      "target": "/news/:type"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
