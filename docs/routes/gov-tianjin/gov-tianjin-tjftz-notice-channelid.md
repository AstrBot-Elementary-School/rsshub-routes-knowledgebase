# 天津市人民政府 - 港保税区公告

## Coverage
`index-only`

## Route
- Namespace: `gov/tianjin`
- Namespace Name: `天津市人民政府`
- Route Path: `/gov/tianjin/tjftz-notice/:channelId`
- Route Name: `港保税区公告`
- Example: `/gov/tianjin/tjftz-notice/6302`
- URL: `tjftz.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `tjftz.ts`
- Source Module: `_None_`

## Description
| 公告类别                            | channelId |
| ----------------------------------- | --------- |
| 首页 > 新闻 > 保税区要闻 > 区域聚焦 | 6302      |

## Parameters
- `channelId`: 公告分类id、详细信息点击源网站https://www.tjftz.gov.cn/请求中寻找


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.tjftz.gov.cn/channels/6302.html`
  - `tjftz.gov.cn/channels/6302.html`
- `target`: `/tjftz-notice/6302`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 公告类别                            | channelId |\n| ----------------------------------- | --------- |\n| 首页 > 新闻 > 保税区要闻 > 区域聚焦 | 6302      |",
  "example": "/gov/tianjin/tjftz-notice/6302",
  "heat": 0,
  "location": "tjftz.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "name": "港保税区公告",
  "parameters": {
    "channelId": "公告分类id、详细信息点击源网站https://www.tjftz.gov.cn/请求中寻找"
  },
  "path": "/tjftz-notice/:channelId",
  "radar": [
    {
      "source": [
        "www.tjftz.gov.cn/channels/6302.html",
        "tjftz.gov.cn/channels/6302.html"
      ],
      "target": "/tjftz-notice/6302"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "tjftz.gov.cn"
}
```
