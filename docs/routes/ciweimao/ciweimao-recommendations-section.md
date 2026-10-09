# 刺猬猫 - 小说推荐

## Coverage
`index-only`

## Route
- Namespace: `ciweimao`
- Namespace Name: `刺猬猫`
- Route Path: `/ciweimao/recommendations/:section?`
- Route Name: `小说推荐`
- Example: `/ciweimao/recommendations/hot`
- URL: `wap.ciweimao.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `DIYgod`
- Source Location: `recommendations.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: 首页栏目：recommended（重磅推荐）、hot（最热连载小说）、featured（精选强推），默认 recommended


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `wap.ciweimao.com/`
- `target`: `/recommendations`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/ciweimao/recommendations/hot",
  "heat": 0,
  "location": "recommendations.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "小说推荐",
  "parameters": {
    "section": "首页栏目：recommended（重磅推荐）、hot（最热连载小说）、featured（精选强推），默认 recommended"
  },
  "path": "/recommendations/:section?",
  "radar": [
    {
      "source": [
        "wap.ciweimao.com/"
      ],
      "target": "/recommendations"
    }
  ],
  "topFeeds": []
}
```
