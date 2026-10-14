# New Museum - Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `newmuseum`
- Namespace Name: `New Museum`
- Route Path: `/newmuseum/exhibitions/:state?`
- Route Name: `Exhibitions`
- Example: `/newmuseum/exhibitions`
- URL: `www.newmuseum.org`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `chazeon`
- Source Location: `exhibitions.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `state`: {"default": "current", "description": "Exhibition status from the exhibition overview", "options": [{"label": "Current exhibitions and long-term commissions", "value": "current"}, {"label": "Upcoming exhibitions", "value": "upcoming"}, {"label": "Past exhibitions", "value": "past"}, {"label": "Online exhibitions", "value": "online"}]}


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
    "travel"
  ],
  "example": "/newmuseum/exhibitions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "exhibitions.ts",
  "maintainers": [
    "chazeon"
  ],
  "name": "Exhibitions",
  "parameters": {
    "state": {
      "default": "current",
      "description": "Exhibition status from the exhibition overview",
      "options": [
        {
          "label": "Current exhibitions and long-term commissions",
          "value": "current"
        },
        {
          "label": "Upcoming exhibitions",
          "value": "upcoming"
        },
        {
          "label": "Past exhibitions",
          "value": "past"
        },
        {
          "label": "Online exhibitions",
          "value": "online"
        }
      ]
    }
  },
  "path": "/exhibitions/:state?",
  "topFeeds": []
}
```
