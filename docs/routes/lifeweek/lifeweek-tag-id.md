# 三联生活周刊 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `lifeweek`
- Namespace Name: `三联生活周刊`
- Route Path: `/lifeweek/tag/:id`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `lifeweek.com.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `None`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lifeweek.com.cn/articleList/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "heat": 12,
  "location": "tag.ts",
  "maintainers": [],
  "name": "Unknown",
  "path": "/tag/:id",
  "radar": [
    {
      "source": [
        "lifeweek.com.cn/articleList/:tag"
      ],
      "target": "/tag/:tag"
    }
  ],
  "topFeeds": [
    {
      "description": "人物 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "104794039452750848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/articleList/6",
      "title": "人物",
      "type": "feed",
      "url": "rsshub://lifeweek/tag/6"
    },
    {
      "description": "生活方式 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "152614722583832576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/articleList/7",
      "title": "生活方式",
      "type": "feed",
      "url": "rsshub://lifeweek/tag/7"
    }
  ]
}
```
