# ÖSW - Immobilienangebot

## Coverage
`index-only`

## Route
- Namespace: `oesw`
- Namespace Name: `ÖSW`
- Route Path: `/oesw/:path{.+}?`
- Route Name: `Immobilienangebot`
- Example: `/oesw/sofort-verfuegbar/objectType=1&financingType=2&region=1020`
- URL: `oesw.at`
- Language: `_None_`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Get your parameters on https://www.oesw.at under "Immobilienangebot".
Make sure to remove the `?` at the beginning from the query parameters!

## Parameters
- `path`: Listing page (`immobiliensuche` by default), optionally followed by the query parameters, see the description below


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Get your parameters on https://www.oesw.at under \"Immobilienangebot\".\nMake sure to remove the `?` at the beginning from the query parameters!",
  "example": "/oesw/sofort-verfuegbar/objectType=1&financingType=2&region=1020",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "sk22"
  ],
  "name": "Immobilienangebot",
  "parameters": {
    "path": "Listing page (`immobiliensuche` by default), optionally followed by the query parameters, see the description below"
  },
  "path": "/:path{.+}?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
