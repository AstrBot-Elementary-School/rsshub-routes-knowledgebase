# 四月网 - 军事

## Coverage
`index-only`

## Route
- Namespace: `m4`
- Namespace Name: `四月网`
- Route Path: `/m4/mil/:category?`
- Route Name: `军事`
- Example: `/m4/mil/china`
- URL: `mil.m4.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `mil.ts`
- Source Module: `_None_`

## Description
| 分类                                  | ID      |
| ------------------------------------- | ------- |
| [中国军情](http://mil.m4.cn/china/)   | china   |
| [国际军情](http://mil.m4.cn/world/)   | world   |
| [军事评论](http://mil.m4.cn/views/)   | views   |
| [军事历史](http://mil.m4.cn/history/) | history |
| [军迷说](http://mil.m4.cn/talk/)      | talk    |
| [武器库](http://mil.m4.cn/arms/)      | arms    |

## Parameters
- `category`: 分类，见下表，默认为中国军情


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mil.m4.cn/:category`
  - `mil.m4.cn/`
- `target`: `/mil/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 分类                                  | ID      |\n| ------------------------------------- | ------- |\n| [中国军情](http://mil.m4.cn/china/)   | china   |\n| [国际军情](http://mil.m4.cn/world/)   | world   |\n| [军事评论](http://mil.m4.cn/views/)   | views   |\n| [军事历史](http://mil.m4.cn/history/) | history |\n| [军迷说](http://mil.m4.cn/talk/)      | talk    |\n| [武器库](http://mil.m4.cn/arms/)      | arms    |",
  "example": "/m4/mil/china",
  "heat": 0,
  "location": "mil.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "军事",
  "parameters": {
    "category": "分类，见下表，默认为中国军情"
  },
  "path": "/mil/:category?",
  "radar": [
    {
      "source": [
        "mil.m4.cn/:category",
        "mil.m4.cn/"
      ],
      "target": "/mil/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "mil.m4.cn"
}
```
