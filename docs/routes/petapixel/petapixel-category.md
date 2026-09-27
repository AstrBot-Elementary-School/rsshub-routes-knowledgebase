# PetaPixel - Posts

## Coverage
`index-only`

## Route
- Namespace: `petapixel`
- Namespace Name: `PetaPixel`
- Route Path: `/petapixel/:category?`
- Route Name: `Posts`
- Example: `/petapixel/news`
- URL: `petapixel.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `IvanWng97`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
The official feed only carries excerpts; this route returns the full post with all images.

| Category    | Slug           |
| ----------- | -------------- |
| News        | `news`         |
| Equipment   | `equipment`    |
| Culture     | `culture`      |
| Inspiration | `inspiration`  |
| Spotlight   | `spotlight`    |
| Finds       | `finds`        |
| Technology  | `technology-2` |
| Industry    | `industry`     |
| Software    | `software`     |
| Educational | `educational`  |
| Tips        | `tips`         |
| Ideas       | `ideas`        |
| Editorial   | `editorial`    |
| Mobile      | `mobile`       |

## Parameters
- `category`: Category slug, see the table below or the URL of a topic page. All posts by default


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
  - `petapixel.com/topic/:category`
  - `petapixel.com/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "The official feed only carries excerpts; this route returns the full post with all images.\n\n| Category    | Slug           |\n| ----------- | -------------- |\n| News        | `news`         |\n| Equipment   | `equipment`    |\n| Culture     | `culture`      |\n| Inspiration | `inspiration`  |\n| Spotlight   | `spotlight`    |\n| Finds       | `finds`        |\n| Technology  | `technology-2` |\n| Industry    | `industry`     |\n| Software    | `software`     |\n| Educational | `educational`  |\n| Tips        | `tips`         |\n| Ideas       | `ideas`        |\n| Editorial   | `editorial`    |\n| Mobile      | `mobile`       |",
  "example": "/petapixel/news",
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
    "category": "Category slug, see the table below or the URL of a topic page. All posts by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "petapixel.com/topic/:category",
        "petapixel.com/"
      ]
    }
  ],
  "topFeeds": [],
  "view": 0
}
```
