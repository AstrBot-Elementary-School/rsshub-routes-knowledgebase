# 中华人民共和国生态环境部 - 政策文件

## Coverage
`index-only`

## Route
- Namespace: `gov/mee`
- Namespace Name: `中华人民共和国生态环境部`
- Route Path: `/gov/mee/zcwj/:category?`
- Route Name: `政策文件`
- Example: `/gov/mee/zcwj`
- URL: `www.mee.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `DIYgod`
- Source Location: `zcwj.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 栏目路径：zyygwj、gwywj、bwj、bgtwj、xzspwj、haqjwj 或 qt，默认合并政策文件首页的各栏目


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.mee.gov.cn/zcwj/:category?`
- `target`: `/zcwj/:category?`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/mee/zcwj",
  "heat": 0,
  "location": "zcwj.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "政策文件",
  "parameters": {
    "category": "栏目路径：zyygwj、gwywj、bwj、bgtwj、xzspwj、haqjwj 或 qt，默认合并政策文件首页的各栏目"
  },
  "path": "/zcwj/:category?",
  "radar": [
    {
      "source": [
        "www.mee.gov.cn/zcwj/:category?"
      ],
      "target": "/zcwj/:category?"
    }
  ],
  "topFeeds": []
}
```
