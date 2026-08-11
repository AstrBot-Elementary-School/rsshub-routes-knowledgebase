# Letterboxd - User Watchlist

## Coverage
`index-only`

## Route
- Namespace: `letterboxd`
- Namespace Name: `Letterboxd`
- Route Path: `/letterboxd/:username/watchlist`
- Route Name: `User Watchlist`
- Example: `/letterboxd/matthew/watchlist`
- URL: `letterboxd.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `johan456789`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Letterboxd username


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `letterboxd.com/:username/watchlist/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/letterboxd/matthew/watchlist",
  "heat": 2,
  "location": "index.ts",
  "maintainers": [
    "johan456789"
  ],
  "name": "User Watchlist",
  "parameters": {
    "username": "Letterboxd username"
  },
  "path": "/:username/watchlist",
  "radar": [
    {
      "source": [
        "letterboxd.com/:username/watchlist/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Matthew Buchanan’s Watchlist • Letterboxd - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "190962429918554112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://letterboxd.com/matthew/watchlist/",
      "title": "Matthew Buchanan’s Watchlist • Letterboxd",
      "type": "feed",
      "url": "rsshub://letterboxd/matthew/watchlist"
    },
    {
      "description": "Emre Kayık’s Watchlist • Letterboxd - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "196345919019816960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://letterboxd.com/emrekayik/watchlist/",
      "title": "Emre Kayık’s Watchlist • Letterboxd",
      "type": "feed",
      "url": "rsshub://letterboxd/emrekayik/watchlist"
    }
  ],
  "url": "letterboxd.com"
}
```
