# 星島日報 - 即時

## Coverage
`index-only`

## Route
- Namespace: `stheadline`
- Namespace Name: `星島日報`
- Route Path: `/stheadline/std/:category{.+}?`
- Route Name: `即時`
- Example: `/stheadline/std/realtimenews`
- URL: `std.stheadline.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `std/realtime.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分類路徑，URL 中 `www.stheadline.com/` 後至中文分類名前部分，預設為 `realtimenews`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.stheadline.com/theme/:category/chineseCategory`
  - `www.stheadline.com/:category/:chineseCategory`
- `target`: `/std/:category`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/stheadline/std/realtimenews",
  "heat": 42,
  "location": "std/realtime.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "即時",
  "parameters": {
    "category": "分類路徑，URL 中 `www.stheadline.com/` 後至中文分類名前部分，預設為 `realtimenews`"
  },
  "path": "/std/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.stheadline.com/theme/:category/chineseCategory",
        "www.stheadline.com/:category/:chineseCategory"
      ],
      "target": "/std/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "全方位多角度的香港新聞、即時新聞、城中熱話、網上熱話、專題報道、中國及國際新聞。 - Powered by RSSHub",
      "errorAt": "2025-05-20T09:52:18.342Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "61348035348284416",
      "image": "https://std.stheadline.com/dist/images/favicon/icon-512.png",
      "ownerUserId": null,
      "siteUrl": "https://std.stheadline.com/realtime/%E5%8D%B3%E6%99%82",
      "title": "即時 | 星島新聞、專題報道 | 星島日報",
      "type": "feed",
      "url": "rsshub://stheadline/std/realtime/%E5%8D%B3%E6%99%82"
    },
    {
      "description": "報導第一手要聞資訊，了解最新新聞動向，全程緊貼社會議題。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "151673363572299776",
      "image": "https://www.sthlstatic.com/sthl/assets/favicon/android-icon-192x192.png",
      "ownerUserId": null,
      "siteUrl": "https://www.stheadline.com/realtimenews",
      "title": "即時｜即時更新社會時事｜星島頭條",
      "type": "feed",
      "url": "rsshub://stheadline/std/realtimenews"
    }
  ]
}
```
