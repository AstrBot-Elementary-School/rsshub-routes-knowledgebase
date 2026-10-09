# 枫叶网 - 剧集下载更新

## Coverage
`index-only`

## Route
- Namespace: `fx57`
- Namespace Name: `枫叶网`
- Route Path: `/fx57/series/:path{.+}`
- Route Name: `剧集下载更新`
- Example: `/fx57/series/fx57/film/animation/2020-10-18/346.html`
- URL: `www.fx57.cn`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `series.ts`
- Source Module: `_None_`

## Description
Each unique magnetic link is a separate item with a BitTorrent enclosure. Subscribe to a specific series page; use common RSSHub filters to select release names or resolutions.

## Parameters
- `path`: 剧集详情 URL 中的完整路径，例如 fx57/film/animation/2020-10-18/346.html。


## Features
- `supportBT`: true

## Radar
### Rule 1
- `source`:
  - `fx57.cn/fx57/:section/:path*`
  - `www.fx57.cn/fx57/:section/:path*`
- `target`: `/series/fx57/:section/:path*`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Each unique magnetic link is a separate item with a BitTorrent enclosure. Subscribe to a specific series page; use common RSSHub filters to select release names or resolutions.",
  "example": "/fx57/series/fx57/film/animation/2020-10-18/346.html",
  "features": {
    "supportBT": true
  },
  "heat": 0,
  "location": "series.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "剧集下载更新",
  "parameters": {
    "path": "剧集详情 URL 中的完整路径，例如 fx57/film/animation/2020-10-18/346.html。"
  },
  "path": "/series/:path{.+}",
  "radar": [
    {
      "source": [
        "fx57.cn/fx57/:section/:path*",
        "www.fx57.cn/fx57/:section/:path*"
      ],
      "target": "/series/fx57/:section/:path*"
    }
  ],
  "topFeeds": []
}
```
