# BWSG - Angebote

## Coverage
`index-only`

## Route
- Namespace: `bwsg`
- Namespace Name: `BWSG`
- Route Path: `/bwsg/:path{.+}?`
- Route Name: `Angebote`
- Example: `/bwsg/_vermarktungsart=miete&_objektart=wohnung&_zimmer=2,3&_wohnflaeche=45,70&_plz=1210,1220`
- URL: `bwsg.at`
- Language: `_None_`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Copy the query parameters for your <https://www.bwsg.at/immobilien/immobilie-suchen>
search, omitting the leading `?`

::: tip
Since there's no parameter available that sorts by "last added" (and there's no
obvious pattern to the default ordering), and since this RSS feed only fetches
the first page of results, you probably want to specify enough search
parameters to make sure you only get one page of results – because else, your
RSS feed might not get all items.
:::

## Parameters
- `path`: Query parameters of the search, without the leading `?`, see the description below


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
  "description": "Copy the query parameters for your <https://www.bwsg.at/immobilien/immobilie-suchen>\nsearch, omitting the leading `?`\n\n::: tip\nSince there's no parameter available that sorts by \"last added\" (and there's no\nobvious pattern to the default ordering), and since this RSS feed only fetches\nthe first page of results, you probably want to specify enough search\nparameters to make sure you only get one page of results – because else, your\nRSS feed might not get all items.\n:::",
  "example": "/bwsg/_vermarktungsart=miete&_objektart=wohnung&_zimmer=2,3&_wohnflaeche=45,70&_plz=1210,1220",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "sk22"
  ],
  "name": "Angebote",
  "parameters": {
    "path": "Query parameters of the search, without the leading `?`, see the description below"
  },
  "path": "/:path{.+}?",
  "topFeeds": []
}
```
