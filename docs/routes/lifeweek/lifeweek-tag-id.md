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
      "errorAt": "2026-07-24T04:35:07.878Z",
      "errorMessage": "[GET] \"https://www.lifeweek.com.cn/api/userWebFollow/getFollowTagContentList?type=4&sort=2&tagId=6\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 211.162.165.43:443, 211.162.165.44:443, 211.162.165.45:443, 211.162.165.46:443, 211.162.165.39:443, 211.162.165.40:443, 211.162.165.41:443, 211.162.165.42:443, timeout: 10000ms))\n",
      "id": "104794039452750848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/articleList/6",
      "title": "人物",
      "type": "feed",
      "url": "rsshub://lifeweek/tag/6"
    },
    {
      "description": "文学 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "152614384793012224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lifeweek.com.cn/articleList/4",
      "title": "文学",
      "type": "feed",
      "url": "rsshub://lifeweek/tag/4"
    }
  ]
}
```
