# Kosmo Foto - Posts

## Coverage
`index-only`

## Route
- Namespace: `kosmofoto`
- Namespace Name: `Kosmo Foto`
- Route Path: `/kosmofoto/:category?`
- Route Name: `Posts`
- Example: `/kosmofoto/news`
- URL: `kosmofoto.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `IvanWng97`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
The official feed only carries excerpts; this route returns the full post with all images.

| Category           | Slug                   |
| ------------------ | ---------------------- |
| News               | `news`                 |
| Film               | `film-2`               |
| Featured           | `featured`             |
| Analogue lifestyle | `analogue-lifestyle-2` |
| Analogue Culture   | `analogue-culture`     |
| Analogue History   | `analogue-history`     |
| Camera reviews     | `camera-review-2`      |
| Classic cameras    | `classic-cameras`      |
| Vintage cameras    | `vintage-cameras`      |
| Soviet cameras     | `soviet-cameras`       |
| Lomography         | `lomography`           |
| Kosmo Foto Mono    | `kosmo-foto-mono`      |

## Parameters
- `category`: Category slug, see the table below or the URL of a category page. All posts by default


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
  - `kosmofoto.com/category/:category`
  - `kosmofoto.com/category/:parent/:category`
  - `kosmofoto.com/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "The official feed only carries excerpts; this route returns the full post with all images.\n\n| Category           | Slug                   |\n| ------------------ | ---------------------- |\n| News               | `news`                 |\n| Film               | `film-2`               |\n| Featured           | `featured`             |\n| Analogue lifestyle | `analogue-lifestyle-2` |\n| Analogue Culture   | `analogue-culture`     |\n| Analogue History   | `analogue-history`     |\n| Camera reviews     | `camera-review-2`      |\n| Classic cameras    | `classic-cameras`      |\n| Vintage cameras    | `vintage-cameras`      |\n| Soviet cameras     | `soviet-cameras`       |\n| Lomography         | `lomography`           |\n| Kosmo Foto Mono    | `kosmo-foto-mono`      |",
  "example": "/kosmofoto/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.tsx",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "Posts",
  "parameters": {
    "category": "Category slug, see the table below or the URL of a category page. All posts by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "kosmofoto.com/category/:category",
        "kosmofoto.com/category/:parent/:category",
        "kosmofoto.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "view": 0
}
```
