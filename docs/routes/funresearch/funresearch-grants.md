# 泛研网 - 项目申报

## Coverage
`index-only`

## Route
- Namespace: `funresearch`
- Namespace Name: `泛研网`
- Route Path: `/funresearch/grants`
- Route Name: `项目申报`
- Example: `/funresearch/grants`
- URL: `www.funresearch.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `DIYgod`
- Source Location: `grants.ts`
- Source Module: `_None_`

## Description
订阅公众版项目申报列表的首屏公告，提供标题、发布机构、官方发布日期，以及申报状态和资助区域分类。正文、原文链接及附件需要在源站使用自己的账号查看。可使用通用过滤参数筛选标题、发布机构或分类。

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.funresearch.cn/grant/index`
  - `www.funresearch.cn/grant/search`
- `target`: `/grants`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "订阅公众版项目申报列表的首屏公告，提供标题、发布机构、官方发布日期，以及申报状态和资助区域分类。正文、原文链接及附件需要在源站使用自己的账号查看。可使用通用过滤参数筛选标题、发布机构或分类。",
  "example": "/funresearch/grants",
  "heat": 0,
  "location": "grants.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "项目申报",
  "path": "/grants",
  "radar": [
    {
      "source": [
        "www.funresearch.cn/grant/index",
        "www.funresearch.cn/grant/search"
      ],
      "target": "/grants"
    }
  ],
  "topFeeds": []
}
```
