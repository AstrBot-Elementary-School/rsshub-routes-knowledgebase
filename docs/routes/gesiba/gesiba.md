# Gesiba - Angebote

## Coverage
`index-only`

## Route
- Namespace: `gesiba`
- Namespace Name: `Gesiba`
- Route Path: `/gesiba*`
- Route Name: `Angebote`
- Example: `/gesiba/verfuegbar=alle&plz[]=1100&plz[]=1120&size-from=45&size-to=80&rooms-from=2&rooms-to=3&betreuung=0`
- URL: `gesiba.at`
- Language: `_None_`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Note that, on <https://www.gesiba.at/immobilien/wohnungen>, filters are added to
the URL like `&filter[plz]=1100,1120`, but the endpoint used here expects it
like `&plz[]=1100&plz[]=1120`, if multiple values are passed to one parameter

## Parameters
_None_


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
  "description": "Note that, on <https://www.gesiba.at/immobilien/wohnungen>, filters are added to\nthe URL like `&filter[plz]=1100,1120`, but the endpoint used here expects it\nlike `&plz[]=1100&plz[]=1120`, if multiple values are passed to one parameter",
  "example": "/gesiba/verfuegbar=alle&plz[]=1100&plz[]=1120&size-from=45&size-to=80&rooms-from=2&rooms-to=3&betreuung=0",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "sk22"
  ],
  "name": "Angebote",
  "path": "*",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
