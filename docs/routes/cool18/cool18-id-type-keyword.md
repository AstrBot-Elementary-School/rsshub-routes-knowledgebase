# 禁忌书屋 - 帖子

## Coverage
`index-only`

## Route
- Namespace: `cool18`
- Namespace Name: `禁忌书屋`
- Route Path: `/cool18/:id?/:type?/:keyword?`
- Route Name: `帖子`
- Example: `/cool18/bbs4`
- URL: `cool18.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk, Gabrlie`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: the name of the bbs, use `global` for site-wide search
- `type`: the type of the post. Can be `home`, `gold`, `threadsearch`. Default: `home`
- `keyword`: the keyword to search.


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `cool18.com/bbs/`
  - `cool18.com/bbs/index.php`
- `target`: `/bbs`
### Rule 2
- `source`:
  - `cool18.com/bbs2/`
  - `cool18.com/bbs2/index.php`
- `target`: `/bbs2`
### Rule 3
- `source`:
  - `cool18.com/bbs3/`
  - `cool18.com/bbs3/index.php`
- `target`: `/bbs3`
### Rule 4
- `source`:
  - `cool18.com/bbs4/`
  - `cool18.com/bbs4/index.php`
- `target`: `/bbs4`
### Rule 5
- `source`:
  - `cool18.com/bbs5/`
  - `cool18.com/bbs5/index.php`
- `target`: `/bbs5`
### Rule 6
- `source`:
  - `cool18.com/bbs6/`
  - `cool18.com/bbs6/index.php`
- `target`: `/bbs6`
### Rule 7
- `source`:
  - `cool18.com/bbs7/`
  - `cool18.com/bbs7/index.php`
- `target`: `/bbs7`
### Rule 8
- `source`:
  - `cool18.com/bj/`
  - `cool18.com/bj/index.php`
- `target`: `/bj`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/cool18/bbs4",
  "features": {
    "nsfw": true
  },
  "heat": 1223,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "Gabrlie"
  ],
  "name": "帖子",
  "parameters": {
    "id": "the name of the bbs, use `global` for site-wide search",
    "keyword": "the keyword to search.",
    "type": "the type of the post. Can be `home`, `gold`, `threadsearch`. Default: `home`"
  },
  "path": "/:id?/:type?/:keyword?",
  "radar": [
    {
      "source": [
        "cool18.com/bbs/",
        "cool18.com/bbs/index.php"
      ],
      "target": "/bbs"
    },
    {
      "source": [
        "cool18.com/bbs2/",
        "cool18.com/bbs2/index.php"
      ],
      "target": "/bbs2"
    },
    {
      "source": [
        "cool18.com/bbs3/",
        "cool18.com/bbs3/index.php"
      ],
      "target": "/bbs3"
    },
    {
      "source": [
        "cool18.com/bbs4/",
        "cool18.com/bbs4/index.php"
      ],
      "target": "/bbs4"
    },
    {
      "source": [
        "cool18.com/bbs5/",
        "cool18.com/bbs5/index.php"
      ],
      "target": "/bbs5"
    },
    {
      "source": [
        "cool18.com/bbs6/",
        "cool18.com/bbs6/index.php"
      ],
      "target": "/bbs6"
    },
    {
      "source": [
        "cool18.com/bbs7/",
        "cool18.com/bbs7/index.php"
      ],
      "target": "/bbs7"
    },
    {
      "source": [
        "cool18.com/bj/",
        "cool18.com/bj/index.php"
      ],
      "target": "/bj"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "性趣贴图 cool18 酷18 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154611732391264308",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cool18.com/bbs/index.php",
      "title": "性趣贴图 cool18 酷18",
      "type": "feed",
      "url": "rsshub://cool18/bbs"
    },
    {
      "description": "禁忌书屋 cool18 酷18 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "149578173744708608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cool18.com/bbs4/index.php",
      "title": "禁忌书屋 cool18 酷18",
      "type": "feed",
      "url": "rsshub://cool18"
    }
  ],
  "url": "cool18.com"
}
```
