# 四川旅游学院 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `sctu`
- Namespace Name: `四川旅游学院`
- Route Path: `/sctu/jwc/:category?`
- Route Name: `教务处`
- Example: `/sctu/jwc/tzgg`
- URL: `www.sctu.edu.cn/jwc/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `talenHuang`
- Source Location: `jwc/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "tzgg", "description": "分类", "options": [{"label": "通知公告", "value": "tzgg"}, {"label": "新闻动态", "value": "xwdt"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sctu.edu.cn/jwc/wenzhangg/:category.htm`
- `target`: `/jwc/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/sctu/jwc/tzgg",
  "heat": 0,
  "location": "jwc/index.ts",
  "maintainers": [
    "talenHuang"
  ],
  "name": "教务处",
  "parameters": {
    "category": {
      "default": "tzgg",
      "description": "分类",
      "options": [
        {
          "label": "通知公告",
          "value": "tzgg"
        },
        {
          "label": "新闻动态",
          "value": "xwdt"
        }
      ]
    }
  },
  "path": "/jwc/:category?",
  "radar": [
    {
      "source": [
        "www.sctu.edu.cn/jwc/wenzhangg/:category.htm"
      ],
      "target": "/jwc/:category"
    }
  ],
  "topFeeds": [],
  "url": "www.sctu.edu.cn/jwc/"
}
```
