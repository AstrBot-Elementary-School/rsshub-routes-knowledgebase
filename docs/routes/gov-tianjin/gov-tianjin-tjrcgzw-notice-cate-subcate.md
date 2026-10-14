# 天津市人民政府 - 人才工作网-公告

## Coverage
`index-only`

## Route
- Namespace: `gov/tianjin`
- Namespace Name: `天津市人民政府`
- Route Path: `/gov/tianjin/tjrcgzw-notice/:cate/:subCate`
- Route Name: `人才工作网-公告`
- Example: `/gov/tianjin/tjrcgzw-notice/rczc/sjrczc/`
- URL: `hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `tjrcgzw.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cate`: 栏目分类，可在源网站 URL 中找到，例如 rczc（人才政策）
- `subCate`: 子栏目分类，例如 sjrczc（市级人才政策）


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/rczc/sjrczc/`
- `target`: `/tjrcgzw-notice/rczc/sjrczc`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/tianjin/tjrcgzw-notice/rczc/sjrczc/",
  "heat": 0,
  "location": "tjrcgzw.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "name": "人才工作网-公告",
  "parameters": {
    "cate": "栏目分类，可在源网站 URL 中找到，例如 rczc（人才政策）",
    "subCate": "子栏目分类，例如 sjrczc（市级人才政策）"
  },
  "path": "/tjrcgzw-notice/:cate/:subCate",
  "radar": [
    {
      "source": [
        "hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/rczc/sjrczc/"
      ],
      "target": "/tjrcgzw-notice/rczc/sjrczc"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/"
}
```
