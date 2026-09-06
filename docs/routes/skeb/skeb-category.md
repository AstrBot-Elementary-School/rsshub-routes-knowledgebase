# Skeb - Skeb

## Coverage
`index-only`

## Route
- Namespace: `skeb`
- Namespace Name: `Skeb`
- Route Path: `/skeb/:category`
- Route Name: `Skeb`
- Example: `/skeb/new_art_works`
- URL: `skeb.jp`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `SnowAgar25`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category, the div id of the section title on the homepage.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `title`: `新着作品 (Illust)`
- `source`:
  - `skeb.jp`
- `target`: `/new_art_works`
### Rule 2
- `title`: `新着作品 (Voice)`
- `source`:
  - `skeb.jp`
- `target`: `/new_voice_works`
### Rule 3
- `title`: `新着作品 (Novel)`
- `source`:
  - `skeb.jp`
- `target`: `/new_novel_works`
### Rule 4
- `title`: `新着作品 (Video)`
- `source`:
  - `skeb.jp`
- `target`: `/new_video_works`
### Rule 5
- `title`: `新着作品 (Music)`
- `source`:
  - `skeb.jp`
- `target`: `/new_music_works`
### Rule 6
- `title`: `新着作品 (Advice)`
- `source`:
  - `skeb.jp`
- `target`: `/new_correction_works`
### Rule 7
- `title`: `新着作品 (Comic)`
- `source`:
  - `skeb.jp`
- `target`: `/new_comic_works`
### Rule 8
- `title`: `人気の作品 (Popular)`
- `source`:
  - `skeb.jp`
- `target`: `/popular_works`
### Rule 9
- `title`: `人気クリエイター`
- `source`:
  - `skeb.jp`
- `target`: `/popular_creators`
### Rule 10
- `title`: `新着クリエイター`
- `source`:
  - `skeb.jp`
- `target`: `/new_creators`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/skeb/new_art_works",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "index.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Skeb",
  "parameters": {
    "category": "Category, the div id of the section title on the homepage."
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/new_art_works",
      "title": "新着作品 (Illust)"
    },
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/new_voice_works",
      "title": "新着作品 (Voice)"
    },
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/new_novel_works",
      "title": "新着作品 (Novel)"
    },
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/new_video_works",
      "title": "新着作品 (Video)"
    },
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/new_music_works",
      "title": "新着作品 (Music)"
    },
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/new_correction_works",
      "title": "新着作品 (Advice)"
    },
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/new_comic_works",
      "title": "新着作品 (Comic)"
    },
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/popular_works",
      "title": "人気の作品 (Popular)"
    },
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/popular_creators",
      "title": "人気クリエイター"
    },
    {
      "source": [
        "skeb.jp"
      ],
      "target": "/new_creators",
      "title": "新着クリエイター"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Skeb - 新着作品 (Illust) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70011876045549568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://skeb.jp/#new_art_works",
      "title": "Skeb - 新着作品 (Illust)",
      "type": "feed",
      "url": "rsshub://skeb/new_art_works"
    }
  ]
}
```
