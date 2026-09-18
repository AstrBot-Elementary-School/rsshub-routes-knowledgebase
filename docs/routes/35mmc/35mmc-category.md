# 35mmc - Posts

## Coverage
`index-only`

## Route
- Namespace: `35mmc`
- Namespace Name: `35mmc`
- Route Path: `/35mmc/:category?`
- Route Name: `Posts`
- Example: `/35mmc/5-frames-with`
- URL: `35mmc.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `IvanWng97`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
The official feed only carries excerpts; this route returns the full post with all images.

| Category                      | Slug                              |
| ----------------------------- | --------------------------------- |
| 5 frames with...              | `5-frames-with`                   |
| Gear Reviews & Experiences    | `reviews-experinces`              |
| Photos & Projects             | `photos-projects`                 |
| Theory & Reflections          | `theory-reflections`              |
| Philosophy & Reflections      | `philosophy-reflections`          |
| News & Events                 | `news-events`                     |
| One Shot Story                | `one-shot-story`                  |
| Tutorials & Knowhow           | `tutorials-knowhow`               |
| Processes, Tutorials & Guides | `tutorials`                       |
| Learning Journeys             | `learning-journeys`               |
| Film                          | `film`                            |
| Lenses                        | `lenses`                          |
| Gear Theory                   | `gear-theory`                     |
| Compact Cameras               | `compact-cameras`                 |
| Point & Shoot                 | `point-shoot-film-camera-reviews` |
| Rangefinder Cameras           | `rangefinder-cameras`             |
| SLRs                          | `slrs`                            |
| Scale Focus                   | `scale-focus-cameras`             |
| Medium & Large Format         | `medium-format`                   |
| Digital Cameras               | `digital-cameras`                 |
| Accessories & More            | `accessories-more`                |
| Mods, DIY & Lens Adapting     | `lens-adapting-mods`              |

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
  - `www.35mmc.com/category/:category`
  - `www.35mmc.com/category/:parent/:category`
  - `www.35mmc.com/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "The official feed only carries excerpts; this route returns the full post with all images.\n\n| Category                      | Slug                              |\n| ----------------------------- | --------------------------------- |\n| 5 frames with...              | `5-frames-with`                   |\n| Gear Reviews & Experiences    | `reviews-experinces`              |\n| Photos & Projects             | `photos-projects`                 |\n| Theory & Reflections          | `theory-reflections`              |\n| Philosophy & Reflections      | `philosophy-reflections`          |\n| News & Events                 | `news-events`                     |\n| One Shot Story                | `one-shot-story`                  |\n| Tutorials & Knowhow           | `tutorials-knowhow`               |\n| Processes, Tutorials & Guides | `tutorials`                       |\n| Learning Journeys             | `learning-journeys`               |\n| Film                          | `film`                            |\n| Lenses                        | `lenses`                          |\n| Gear Theory                   | `gear-theory`                     |\n| Compact Cameras               | `compact-cameras`                 |\n| Point & Shoot                 | `point-shoot-film-camera-reviews` |\n| Rangefinder Cameras           | `rangefinder-cameras`             |\n| SLRs                          | `slrs`                            |\n| Scale Focus                   | `scale-focus-cameras`             |\n| Medium & Large Format         | `medium-format`                   |\n| Digital Cameras               | `digital-cameras`                 |\n| Accessories & More            | `accessories-more`                |\n| Mods, DIY & Lens Adapting     | `lens-adapting-mods`              |",
  "example": "/35mmc/5-frames-with",
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
        "www.35mmc.com/category/:category",
        "www.35mmc.com/category/:parent/:category",
        "www.35mmc.com/"
      ]
    }
  ],
  "topFeeds": [],
  "view": 0
}
```
