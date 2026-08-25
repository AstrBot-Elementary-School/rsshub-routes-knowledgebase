# 学堂在线 - 课程列表

## Coverage
`index-only`

## Route
- Namespace: `xuetangx`
- Namespace Name: `学堂在线`
- Route Path: `/xuetangx/course/list/:classify?/:status?/:sellingType?`
- Route Name: `课程列表`
- Example: `/xuetangx/course/list/1/2`
- URL: `www.xuetangx.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `sanmmm`
- Source Location: `course-list.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `classify`: {"description": "学科分类，默认为全部", "options": [{"label": "计算机", "value": "1"}, {"label": "经济学", "value": "2"}, {"label": "农林园艺", "value": "4"}, {"label": "医药卫生", "value": "8"}, {"label": "理学", "value": "11"}, {"label": "历史", "value": "13"}, {"label": "法学", "value": "14"}, {"label": "文学文化", "value": "15"}, {"label": "哲学", "value": "16"}, {"label": "艺术设计", "value": "17"}, {"label": "外语", "value": "19"}, {"label": "教育教学", "value": "21"}, {"label": "管理学", "value": "23"}, {"label": "工学", "value": "24"}, {"label": "其他", "value": "27"}]}
- `status`: {"description": "课程状态，默认为全部", "options": [{"label": "即将开课", "value": "1"}, {"label": "开课中", "value": "2"}, {"label": "已结课", "value": "3"}]}
- `sellingType`: {"description": "课程类型，默认为全部", "options": [{"label": "训练营", "value": "2"}, {"label": "微学位", "value": "3"}, {"label": "高校认证", "value": "4"}, {"label": "直播课", "value": "5"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.xuetangx.com/search`
- `target`: `/course/list`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/xuetangx/course/list/1/2",
  "heat": 0,
  "location": "course-list.ts",
  "maintainers": [
    "sanmmm"
  ],
  "name": "课程列表",
  "parameters": {
    "classify": {
      "description": "学科分类，默认为全部",
      "options": [
        {
          "label": "计算机",
          "value": "1"
        },
        {
          "label": "经济学",
          "value": "2"
        },
        {
          "label": "农林园艺",
          "value": "4"
        },
        {
          "label": "医药卫生",
          "value": "8"
        },
        {
          "label": "理学",
          "value": "11"
        },
        {
          "label": "历史",
          "value": "13"
        },
        {
          "label": "法学",
          "value": "14"
        },
        {
          "label": "文学文化",
          "value": "15"
        },
        {
          "label": "哲学",
          "value": "16"
        },
        {
          "label": "艺术设计",
          "value": "17"
        },
        {
          "label": "外语",
          "value": "19"
        },
        {
          "label": "教育教学",
          "value": "21"
        },
        {
          "label": "管理学",
          "value": "23"
        },
        {
          "label": "工学",
          "value": "24"
        },
        {
          "label": "其他",
          "value": "27"
        }
      ]
    },
    "sellingType": {
      "description": "课程类型，默认为全部",
      "options": [
        {
          "label": "训练营",
          "value": "2"
        },
        {
          "label": "微学位",
          "value": "3"
        },
        {
          "label": "高校认证",
          "value": "4"
        },
        {
          "label": "直播课",
          "value": "5"
        }
      ]
    },
    "status": {
      "description": "课程状态，默认为全部",
      "options": [
        {
          "label": "即将开课",
          "value": "1"
        },
        {
          "label": "开课中",
          "value": "2"
        },
        {
          "label": "已结课",
          "value": "3"
        }
      ]
    }
  },
  "path": "/course/list/:classify?/:status?/:sellingType?",
  "radar": [
    {
      "source": [
        "www.xuetangx.com/search"
      ],
      "target": "/course/list"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
