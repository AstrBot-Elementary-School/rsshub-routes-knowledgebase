# wohnnet.at - Immobiliensuche

## Coverage
`index-only`

## Route
- Namespace: `wohnnet`
- Namespace Name: `wohnnet.at`
- Route Path: `/wohnnet/:category/:region/*`
- Route Name: `Immobiliensuche`
- Example: `/wohnnet/mietwohnungen/wien/unterregionen=g90101--g90201--g90301--g90401--g90501&flaeche=40&preis=-1000`
- URL: `wohnnet.at`
- Language: `_None_`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Only returns the first page of search results, allowing you to keep track of
newly added apartments. If you're looking for an apartment, make sure to also
look through the other pages on the website.

::: tip
Note that the parameter `&sortierung=neueste-zuerst` for chronological order
is automatically appended.
:::

::: tip
To get your query URL, go to https://www.wohnnet.at/immobilien/suche, apply
all desired filters (but at least a category and a region!) and click the
"… Treffer anzeigen" link. From the resulting URL, cut off the
`https://www.wohnnet.at/immobilien/` part at the beginning and replace only
the `?` (the `&`s stay as is!) after the region name with a `/`.

Search options in the wildcard path after the region:

| Option | Meaning |
| --- | --- |
| `unterregionen` | Unterregionen (e.g. `g90101--g90201--g90301`) |
| `intention` | Intention (`kauf` \| `miete`) |
| `zimmer` | Zimmer (at least number, e.g. `2`) |
| `flaeche` | Fläche (m², `40-` = at least 40 m², `40-60` = between 40 m² and 60 m²) |
| `preis` | Preis (€, `-1000` = at most 1,000 €, `500-1000` = between 500 € and 1,000 €) |
| `merkmale` | Merkmale (multiple, delimited by `--`, e.g. `balkon--garten--kurzzeitmiete--moebliert--parkplatz--provisionsfrei--sofort-beziehbar`) |

Examples:

* `https://www.wohnnet.at/immobilien/mietwohnungen/wien`
    - → `/wohnnet/mietwohnungen/wien`
* `https://www.wohnnet.at/immobilien/mietwohnungen/wien?unterregionen=g90101`
    - → `/wohnnet/mietwohnungen/wien/unterregionen=g90101`
* `https://www.wohnnet.at/immobilien/mietwohnungen/wien?unterregionen=g90101&merkmale=balkon`
    - → `/wohnnet/mietwohnungen/wien/unterregionen=g90101&merkmale=balkon`
:::

## Parameters
- `category`: Category (`mietwohnungen`, `eigentumswohnungen`, `grundstuecke`, …)
- `region`: Region (`wien`, `oesterreich`, …)


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
  "description": "\nOnly returns the first page of search results, allowing you to keep track of\nnewly added apartments. If you're looking for an apartment, make sure to also\nlook through the other pages on the website.\n\n::: tip\nNote that the parameter `&sortierung=neueste-zuerst` for chronological order\nis automatically appended.\n:::\n\n::: tip\nTo get your query URL, go to https://www.wohnnet.at/immobilien/suche, apply\nall desired filters (but at least a category and a region!) and click the\n\"… Treffer anzeigen\" link. From the resulting URL, cut off the\n`https://www.wohnnet.at/immobilien/` part at the beginning and replace only\nthe `?` (the `&`s stay as is!) after the region name with a `/`.\n\nSearch options in the wildcard path after the region:\n\n| Option | Meaning |\n| --- | --- |\n| `unterregionen` | Unterregionen (e.g. `g90101--g90201--g90301`) |\n| `intention` | Intention (`kauf` \\| `miete`) |\n| `zimmer` | Zimmer (at least number, e.g. `2`) |\n| `flaeche` | Fläche (m², `40-` = at least 40 m², `40-60` = between 40 m² and 60 m²) |\n| `preis` | Preis (€, `-1000` = at most 1,000 €, `500-1000` = between 500 € and 1,000 €) |\n| `merkmale` | Merkmale (multiple, delimited by `--`, e.g. `balkon--garten--kurzzeitmiete--moebliert--parkplatz--provisionsfrei--sofort-beziehbar`) |\n\nExamples:\n\n* `https://www.wohnnet.at/immobilien/mietwohnungen/wien`\n    - → `/wohnnet/mietwohnungen/wien`\n* `https://www.wohnnet.at/immobilien/mietwohnungen/wien?unterregionen=g90101`\n    - → `/wohnnet/mietwohnungen/wien/unterregionen=g90101`\n* `https://www.wohnnet.at/immobilien/mietwohnungen/wien?unterregionen=g90101&merkmale=balkon`\n    - → `/wohnnet/mietwohnungen/wien/unterregionen=g90101&merkmale=balkon`\n:::\n",
  "example": "/wohnnet/mietwohnungen/wien/unterregionen=g90101--g90201--g90301--g90401--g90501&flaeche=40&preis=-1000",
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
    "category": "Category (`mietwohnungen`, `eigentumswohnungen`, `grundstuecke`, …)",
    "region": "Region (`wien`, `oesterreich`, …)"
  },
  "path": "/:category/:region/*",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
