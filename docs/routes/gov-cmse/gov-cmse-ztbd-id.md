# 中国载人航天工程 - 专题报道

## Coverage
`index-only`

## Route
- Namespace: `gov/cmse`
- Namespace Name: `中国载人航天工程`
- Route Path: `/gov/cmse/ztbd/:id`
- Route Name: `专题报道`
- Example: `/gov/cmse/ztbd/xwfbh`
- URL: `www.cmse.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `ztbd.ts`
- Source Module: `_None_`

## Description
| 新闻发布会 | 学术大会 | 标准 | 新闻专题 |
| ---------- | -------- | ---- | -------- |
| xwfbh      | xsdh     | bz   | xwzt     |

## Parameters
- `id`: 分类 id，见下表，可在对应分类页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.cmse.gov.cn/ztbd/:id`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 新闻发布会 | 学术大会 | 标准 | 新闻专题 |\n| ---------- | -------- | ---- | -------- |\n| xwfbh      | xsdh     | bz   | xwzt     |",
  "example": "/gov/cmse/ztbd/xwfbh",
  "heat": 0,
  "location": "ztbd.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专题报道",
  "parameters": {
    "id": "分类 id，见下表，可在对应分类页 URL 中找到"
  },
  "path": "/ztbd/:id",
  "radar": [
    {
      "source": [
        "www.cmse.gov.cn/ztbd/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
