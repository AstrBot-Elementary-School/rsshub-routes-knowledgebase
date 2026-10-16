# Bandcamp - Artist Releases

## Coverage
`index-only`

## Route
- Namespace: `bandcamp`
- Namespace Name: `Bandcamp`
- Route Path: `/bandcamp/artist/:artist`
- Route Name: `Artist Releases`
- Example: `/bandcamp/artist/radiohead`
- URL: `bandcamp.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `pseudoyu`
- Source Location: `artist.tsx`
- Source Module: `_None_`

## Description
Releases on the music page of an artist or label, in the order the page shows them (newest first unless the artist reorders them). Returns the latest 10 by default, use `limit` for more. Artists on a custom domain still have a bandcamp.com subdomain.

## Parameters
- `artist`: Subdomain of the artist or label, such as `radiohead` in `https://radiohead.bandcamp.com`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Releases on the music page of an artist or label, in the order the page shows them (newest first unless the artist reorders them). Returns the latest 10 by default, use `limit` for more. Artists on a custom domain still have a bandcamp.com subdomain.",
  "example": "/bandcamp/artist/radiohead",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "artist.tsx",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "Artist Releases",
  "parameters": {
    "artist": "Subdomain of the artist or label, such as `radiohead` in `https://radiohead.bandcamp.com`"
  },
  "path": "/artist/:artist",
  "topFeeds": []
}
```
