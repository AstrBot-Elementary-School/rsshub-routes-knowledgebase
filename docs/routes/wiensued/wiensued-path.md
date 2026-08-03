# Wien-Süd - Objekte

## Coverage
`index-only`

## Route
- Namespace: `wiensued`
- Namespace Name: `Wien-Süd`
- Route Path: `/wiensued/:path{.+}?`
- Route Name: `Objekte`
- Example: `/wiensued/city=Wien&search=&space-from=30&space-to=100&room-from=2&room-to=4&rent=1&property=1&state[]=inplanung&state[]=inbau&state[]=sofort&state[]=bestand`
- URL: `wiensued.at`
- Language: `_None_`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Pass in the parameters (e.g. `city=Wien&state[]=sofort`) and/or the path
leading up to the listing (e.g. `wohnen/sofort-verfuegbar`)

## Parameters
- `path`: Query parameters and/or the path leading up to the listing, see the description below


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
  "description": "Pass in the parameters (e.g. `city=Wien&state[]=sofort`) and/or the path\nleading up to the listing (e.g. `wohnen/sofort-verfuegbar`)",
  "example": "/wiensued/city=Wien&search=&space-from=30&space-to=100&room-from=2&room-to=4&rent=1&property=1&state[]=inplanung&state[]=inbau&state[]=sofort&state[]=bestand",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "sk22"
  ],
  "name": "Objekte",
  "parameters": {
    "path": "Query parameters and/or the path leading up to the listing, see the description below"
  },
  "path": "/:path{.+}?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
