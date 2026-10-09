# Treccani - Magazine articles

## Coverage
`index-only`

## Route
- Namespace: `treccani`
- Namespace Name: `Treccani`
- Route Path: `/treccani/magazine/:section?`
- Route Name: `Magazine articles`
- Example: `/treccani/magazine/atlante`
- URL: `www.treccani.it`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `DIYgod`
- Source Location: `magazine.tsx`
- Source Module: `_None_`

## Description
Includes public article summaries. Il Tascabile has its own native feed at <https://www.iltascabile.com/feed/>.

## Parameters
- `section`: {"description": "Magazine section. Omit for the homepage.", "options": [{"label": "agenda", "value": "agenda"}, {"label": "atlante", "value": "atlante"}, {"label": "faro", "value": "faro"}, {"label": "chiasmo", "value": "chiasmo"}, {"label": "diritto", "value": "diritto"}, {"label": "lingua_italiana", "value": "lingua_italiana"}, {"label": "parolevalgono", "value": "parolevalgono"}, {"label": "webtv", "value": "webtv"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `treccani.it/magazine/:section`
- `target`: `/magazine/:section`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Includes public article summaries. Il Tascabile has its own native feed at <https://www.iltascabile.com/feed/>.",
  "example": "/treccani/magazine/atlante",
  "heat": 0,
  "location": "magazine.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Magazine articles",
  "parameters": {
    "section": {
      "description": "Magazine section. Omit for the homepage.",
      "options": [
        {
          "label": "agenda",
          "value": "agenda"
        },
        {
          "label": "atlante",
          "value": "atlante"
        },
        {
          "label": "faro",
          "value": "faro"
        },
        {
          "label": "chiasmo",
          "value": "chiasmo"
        },
        {
          "label": "diritto",
          "value": "diritto"
        },
        {
          "label": "lingua_italiana",
          "value": "lingua_italiana"
        },
        {
          "label": "parolevalgono",
          "value": "parolevalgono"
        },
        {
          "label": "webtv",
          "value": "webtv"
        }
      ]
    }
  },
  "path": "/magazine/:section?",
  "radar": [
    {
      "source": [
        "treccani.it/magazine/:section"
      ],
      "target": "/magazine/:section"
    }
  ],
  "topFeeds": []
}
```
