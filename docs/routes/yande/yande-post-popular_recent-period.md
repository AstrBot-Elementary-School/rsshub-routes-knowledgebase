# yande.re - Popular Recent Posts

## Coverage
`index-only`

## Route
- Namespace: `yande`
- Namespace Name: `yande.re`
- Route Path: `/yande/post/popular_recent/:period?`
- Route Name: `Popular Recent Posts`
- Example: `/yande/post/popular_recent/1d`
- URL: `yande.re`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `magic-akari, SettingDust, fashioncj, NekoAria`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
| 最近 24 小时 | 最近一周 | 最近一月 | 最近一年 |
| ------------ | -------- | -------- | -------- |
| 1d           | 1w       | 1m       | 1y       |

## Parameters
- `period`: {"default": "1d", "description": "展示时间", "options": [{"label": "最近 24 小时", "value": "1d"}, {"label": "最近一周", "value": "1w"}, {"label": "最近一月", "value": "1m"}, {"label": "最近一年", "value": "1y"}]}


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `yande.re/post`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "| 最近 24 小时 | 最近一周 | 最近一月 | 最近一年 |\n| ------------ | -------- | -------- | -------- |\n| 1d           | 1w       | 1m       | 1y       |",
  "example": "/yande/post/popular_recent/1d",
  "features": {
    "nsfw": true
  },
  "heat": 1168,
  "location": "post.ts",
  "maintainers": [
    "magic-akari",
    "SettingDust",
    "fashioncj",
    "NekoAria"
  ],
  "name": "Popular Recent Posts",
  "parameters": {
    "period": {
      "default": "1d",
      "description": "展示时间",
      "options": [
        {
          "label": "最近 24 小时",
          "value": "1d"
        },
        {
          "label": "最近一周",
          "value": "1w"
        },
        {
          "label": "最近一月",
          "value": "1m"
        },
        {
          "label": "最近一年",
          "value": "1y"
        }
      ]
    }
  },
  "path": "/post/popular_recent/:period?",
  "radar": [
    {
      "source": [
        "yande.re/post"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Last 24 hours - yande.re - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62219645395102720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yande.re/post/popular_recent?period=1d",
      "title": "Last 24 hours - yande.re",
      "type": "feed",
      "url": "rsshub://yande/post/popular_recent/1d"
    },
    {
      "description": "Last week - yande.re - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62219893932021760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yande.re/post/popular_recent?period=1w",
      "title": "Last week - yande.re",
      "type": "feed",
      "url": "rsshub://yande/post/popular_recent/1w"
    }
  ],
  "view": 2
}
```
