# Genossenschaften.immo - Immobiliensuche

## Coverage
`index-only`

## Route
- Namespace: `genossenschaften`
- Namespace Name: `Genossenschaften.immo`
- Route Path: `/genossenschaften/:path{.+}?`
- Route Name: `Immobiliensuche`
- Example: `/genossenschaften/district=wien-1-innere-stadt&district=wien-2-leopoldstadt&district=wien-3-landstrasse&district=wien-4-wieden&district=wien-5-margareten&district=wien-6-mariahilf&district=wien-7-neubau&district=wien-8-josefstadt&district=wien-9-alsergrund&district=wien-10-favoriten&district=wien-11-simmering&district=wien-12-meidling&district=wien-13-hietzing&district=wien-14-penzing&district=wien-15-rudolfsheim-fuenfhaus&district=wien-16-ottakring&district=wien-17-hernals&district=wien-18-waehring&district=wien-19-doebling&district=wien-20-brigittenau&district=wien-21-floridsdorf&district=wien-22-donaustadt&district=wien-23-liesing&has_rent=on&has_rent_option=on&status=available&status=construction&cost=1000&room=2&size=50&has_property=off&has_rent=on&has_rent_option=on&status=available&status=construction&status=planned&type=residence&type=project`
- URL: `genossenschaften.immo`
- Language: `_None_`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Note that all parameters are optional and many can be specified multiple times
(e.g. `district=wien-1-innere-stadt&district=wien-2-leopoldstadt`).

Only returns the first page of search results, allowing you to keep track of
newly added apartments. If you're looking for an apartment, make sure to also
look through the other pages on the website.

::: tip
To get your query URL, go to <https://genossenschaften.immo> and apply all
desired filters. If you want to filter by (all districts of a) federal state
(e.g. `/immobilien/regionen/wien/`), please open the district selector and
de- and re-select any district, so that the region in the URL gets replaced
with a number of `district` parameters. Once you've set up all desired
filters, copy the part of the URL after the `?`.
:::

## Parameters
- `path`: Query parameters copied from the search URL, without the leading `?`, composed of the parameters below
- `cost`: Miete bis (in €, number)
- `district`: Bezirk (string, multiple)
- `size`: Größe ab (in m², number)
- `room`: Zimmer ab (number)
- `genossenschaft`: Bauvereinigung (string, multiple)
- `own_funds`: Eigenkapital bis
- `has_property`: Eigentum (`on` | `off`)
- `has_rent`: Miete (`on` | `off`)
- `has_rent_option`: Miete mit Kaufoption (`on` | `off`)
- `status`: multiple, `available` | `construction` | `planned`
- `type`: multiple, `residence` | `project`
- `keywords`: Keyword search


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
    "other"
  ],
  "description": "Note that all parameters are optional and many can be specified multiple times\n(e.g. `district=wien-1-innere-stadt&district=wien-2-leopoldstadt`).\n\nOnly returns the first page of search results, allowing you to keep track of\nnewly added apartments. If you're looking for an apartment, make sure to also\nlook through the other pages on the website.\n\n::: tip\nTo get your query URL, go to <https://genossenschaften.immo> and apply all\ndesired filters. If you want to filter by (all districts of a) federal state\n(e.g. `/immobilien/regionen/wien/`), please open the district selector and\nde- and re-select any district, so that the region in the URL gets replaced\nwith a number of `district` parameters. Once you've set up all desired\nfilters, copy the part of the URL after the `?`.\n:::",
  "example": "/genossenschaften/district=wien-1-innere-stadt&district=wien-2-leopoldstadt&district=wien-3-landstrasse&district=wien-4-wieden&district=wien-5-margareten&district=wien-6-mariahilf&district=wien-7-neubau&district=wien-8-josefstadt&district=wien-9-alsergrund&district=wien-10-favoriten&district=wien-11-simmering&district=wien-12-meidling&district=wien-13-hietzing&district=wien-14-penzing&district=wien-15-rudolfsheim-fuenfhaus&district=wien-16-ottakring&district=wien-17-hernals&district=wien-18-waehring&district=wien-19-doebling&district=wien-20-brigittenau&district=wien-21-floridsdorf&district=wien-22-donaustadt&district=wien-23-liesing&has_rent=on&has_rent_option=on&status=available&status=construction&cost=1000&room=2&size=50&has_property=off&has_rent=on&has_rent_option=on&status=available&status=construction&status=planned&type=residence&type=project",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "sk22"
  ],
  "name": "Immobiliensuche",
  "parameters": {
    "cost": "Miete bis (in €, number)",
    "district": "Bezirk (string, multiple)",
    "genossenschaft": "Bauvereinigung (string, multiple)",
    "has_property": "Eigentum (`on` | `off`)",
    "has_rent": "Miete (`on` | `off`)",
    "has_rent_option": "Miete mit Kaufoption (`on` | `off`)",
    "keywords": "Keyword search",
    "own_funds": "Eigenkapital bis",
    "path": "Query parameters copied from the search URL, without the leading `?`, composed of the parameters below",
    "room": "Zimmer ab (number)",
    "size": "Größe ab (in m², number)",
    "status": "multiple, `available` | `construction` | `planned`",
    "type": "multiple, `residence` | `project`"
  },
  "path": "/:path{.+}?",
  "topFeeds": []
}
```
