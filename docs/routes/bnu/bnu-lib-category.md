# 北京师范大学 - 图书馆通知

## Coverage
`index-only`

## Route
- Namespace: `bnu`
- Namespace Name: `北京师范大学`
- Route Path: `/bnu/lib/:category?`
- Route Name: `图书馆通知`
- Example: `/bnu/lib/zydt`
- URL: `bs.bnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `TonyRL`
- Source Location: `lib.ts`
- Source Module: `_None_`

## Description
| 资源动态 | 新闻动态 | 系列讲座 |
| -------- | -------- | -------- |
| zydt     | xwdt     | xljz1    |

## Parameters
- `category`: 分类，见下表，默认为 `zydt`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.lib.bnu.edu.cn/:category/index.htm`
- `target`: `/lib/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 资源动态 | 新闻动态 | 系列讲座 |\n| -------- | -------- | -------- |\n| zydt     | xwdt     | xljz1    |",
  "example": "/bnu/lib/zydt",
  "heat": 2,
  "location": "lib.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "图书馆通知",
  "parameters": {
    "category": "分类，见下表，默认为 `zydt`"
  },
  "path": "/lib/:category?",
  "radar": [
    {
      "source": [
        "www.lib.bnu.edu.cn/:category/index.htm"
      ],
      "target": "/lib/:category"
    }
  ],
  "topFeeds": [
    {
      "description": "北京师范大学图书馆 | 北京师范大学图书馆 - Powered by RSSHub",
      "errorAt": "2025-12-22T09:40:10.256Z",
      "errorMessage": "[GET] \"http://www.lib.bnu.edu.cn/zydt/index.htm\": 404 Not Found\n",
      "id": "63261228702728212",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.lib.bnu.edu.cn/zydt/index.htm",
      "title": "北京师范大学图书馆 | 北京师范大学图书馆",
      "type": "feed",
      "url": "rsshub://bnu/lib/zydt"
    }
  ]
}
```
