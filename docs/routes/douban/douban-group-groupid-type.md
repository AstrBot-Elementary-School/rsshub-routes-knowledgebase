# 豆瓣 - 豆瓣小组

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/group/:groupid/:type?`
- Route Name: `豆瓣小组`
- Example: `/douban/group/648102`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod`
- Source Location: `other/group.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `groupid`: 豆瓣小组的 id
- `type`: {"default": "latest", "description": "类型", "options": [{"label": "最新", "value": "latest"}, {"label": "最热", "value": "essence"}, {"label": "精华", "value": "elite"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.douban.com/group/:groupid`
- `target`: `/group/:groupid`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/douban/group/648102",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6057,
  "location": "other/group.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "豆瓣小组",
  "parameters": {
    "groupid": "豆瓣小组的 id",
    "type": {
      "default": "latest",
      "description": "类型",
      "options": [
        {
          "label": "最新",
          "value": "latest"
        },
        {
          "label": "最热",
          "value": "essence"
        },
        {
          "label": "精华",
          "value": "elite"
        }
      ]
    }
  },
  "path": "/group/:groupid/:type?",
  "radar": [
    {
      "source": [
        "www.douban.com/group/:groupid"
      ],
      "target": "/group/:groupid"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "豆瓣小组-无用美学 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805268337664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/group/699356/?type=essence",
      "title": "豆瓣小组-无用美学",
      "type": "feed",
      "url": "rsshub://douban/group/699356/essence"
    },
    {
      "description": "豆瓣小组-可爱事物分享 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805268337667",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/group/648102/?type=essence",
      "title": "豆瓣小组-可爱事物分享",
      "type": "feed",
      "url": "rsshub://douban/group/648102/essence"
    }
  ],
  "view": 1
}
```
