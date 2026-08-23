# 湖北省软件企业协会 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `hbsea`
- Namespace Name: `湖北省软件企业协会`
- Route Path: `/hbsea/:id`
- Route Name: `栏目`
- Example: `/hbsea/19`
- URL: `www.hbsea.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `tudou027`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
|   栏目   |  id |
| :------: | :-: |
| 通知公告 |  18 |
| 协会动态 |  19 |
| 行业资讯 |  20 |
| 企业之窗 |  21 |

## Parameters
- `id`: 栏目 id，见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.hbsea.org.cn/portal/list/index/id/:id.html`
- `target`: `/:id`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "|   栏目   |  id |\n| :------: | :-: |\n| 通知公告 |  18 |\n| 协会动态 |  19 |\n| 行业资讯 |  20 |\n| 企业之窗 |  21 |",
  "example": "/hbsea/19",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "tudou027"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，见下表"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "www.hbsea.org.cn/portal/list/index/id/:id.html"
      ],
      "target": "/:id"
    }
  ],
  "topFeeds": []
}
```
