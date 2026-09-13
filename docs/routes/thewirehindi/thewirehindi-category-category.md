# The Wire Hindi - Category

## Coverage
`index-only`

## Route
- Namespace: `thewirehindi`
- Namespace Name: `The Wire Hindi`
- Route Path: `/thewirehindi/category/:category`
- Route Name: `Category`
- Example: `/thewirehindi/category/bharat`
- URL: `thewirehindi.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Rjnishant530`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"description": "Category name", "options": [{"label": "इंटरव्यू", "value": "interview"}, {"label": "ऑडियो", "value": "audio"}, {"label": "कला-साहित्य", "value": "kala-sahitya"}, {"label": "कैंपस", "value": "campus"}, {"label": "कोविड-19", "value": "covid-19"}, {"label": "जन की बात", "value": "jan-ki-baat"}, {"label": "दुनिया", "value": "duniya"}, {"label": "नॉर्थ ईस्ट", "value": "north-east"}, {"label": "प्रासंगिक", "value": "prasangik"}, {"label": "भारत", "value": "bharat"}, {"label": "मीडिया", "value": "media"}, {"label": "मीडिया बोल", "value": "media-bol"}, {"label": "राजनीति", "value": "rajneeti"}, {"label": "विचार", "value": "vichar"}, {"label": "विज्ञान", "value": "vigyan"}, {"label": "विशेष", "value": "vishesh"}, {"label": "वीडियो", "value": "video"}, {"label": "समाज", "value": "samaj"}, {"label": "हम भी भारत", "value": "ham-bhi-bharat"}, {"label": "हमारे बारे में", "value": "hamare-bare-mein"}]}


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
  - `thewirehindi.com/category/*`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thewirehindi/category/bharat",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Category",
  "parameters": {
    "category": {
      "description": "Category name",
      "options": [
        {
          "label": "इंटरव्यू",
          "value": "interview"
        },
        {
          "label": "ऑडियो",
          "value": "audio"
        },
        {
          "label": "कला-साहित्य",
          "value": "kala-sahitya"
        },
        {
          "label": "कैंपस",
          "value": "campus"
        },
        {
          "label": "कोविड-19",
          "value": "covid-19"
        },
        {
          "label": "जन की बात",
          "value": "jan-ki-baat"
        },
        {
          "label": "दुनिया",
          "value": "duniya"
        },
        {
          "label": "नॉर्थ ईस्ट",
          "value": "north-east"
        },
        {
          "label": "प्रासंगिक",
          "value": "prasangik"
        },
        {
          "label": "भारत",
          "value": "bharat"
        },
        {
          "label": "मीडिया",
          "value": "media"
        },
        {
          "label": "मीडिया बोल",
          "value": "media-bol"
        },
        {
          "label": "राजनीति",
          "value": "rajneeti"
        },
        {
          "label": "विचार",
          "value": "vichar"
        },
        {
          "label": "विज्ञान",
          "value": "vigyan"
        },
        {
          "label": "विशेष",
          "value": "vishesh"
        },
        {
          "label": "वीडियो",
          "value": "video"
        },
        {
          "label": "समाज",
          "value": "samaj"
        },
        {
          "label": "हम भी भारत",
          "value": "ham-bhi-bharat"
        },
        {
          "label": "हमारे बारे में",
          "value": "hamare-bare-mein"
        }
      ]
    }
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "thewirehindi.com/category/*"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "thewirehindi.com/"
}
```
