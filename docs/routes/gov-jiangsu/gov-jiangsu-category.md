# 江苏省人民政府 - 动态

## Coverage
`index-only`

## Route
- Namespace: `gov/jiangsu`
- Namespace Name: `江苏省人民政府`
- Route Path: `/gov/jiangsu/:category`
- Route Name: `动态`
- Example: `/gov/jiangsu/important-news`
- URL: `www.jiangsu.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ocleo1`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
|   省政府常务会议  |    要闻关注    |  部门资讯  |   地方动态  |        政策解读       |
| :---------------: | :------------: | :--------: | :---------: | :-------------------: |
| executive-meeting | important-news | department | city-county | policy-interpretation |

|    政府信息公开制度   |    政策文件   |     规范性文件     |
| :-------------------: | :-----------: | :----------------: |
| information-publicity | documentation | normative-document |

|          立法意见征集          |      征集调查      |
| :----------------------------: | :----------------: |
| legislative-opinion-collection | opinion-collection |

## Parameters
- `category`: 分类名，见下表


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "|   省政府常务会议  |    要闻关注    |  部门资讯  |   地方动态  |        政策解读       |\n| :---------------: | :------------: | :--------: | :---------: | :-------------------: |\n| executive-meeting | important-news | department | city-county | policy-interpretation |\n\n|    政府信息公开制度   |    政策文件   |     规范性文件     |\n| :-------------------: | :-----------: | :----------------: |\n| information-publicity | documentation | normative-document |\n\n|          立法意见征集          |      征集调查      |\n| :----------------------------: | :----------------: |\n| legislative-opinion-collection | opinion-collection |",
  "example": "/gov/jiangsu/important-news",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "ocleo1"
  ],
  "name": "动态",
  "parameters": {
    "category": "分类名，见下表"
  },
  "path": "/:category",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
