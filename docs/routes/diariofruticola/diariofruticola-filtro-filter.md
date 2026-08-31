# Diario Frutícola - Filtro

## Coverage
`index-only`

## Route
- Namespace: `diariofruticola`
- Namespace Name: `Diario Frutícola`
- Route Path: `/diariofruticola/filtro/:filter{.+}`
- Route Name: `Filtro`
- Example: `/diariofruticola/filtro/cerezas/71`
- URL: `diariofruticola.cl`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `filtro.ts`
- Source Module: `_None_`

## Description
::: tip
If you subscribe to [Cerezas](https://www.diariofruticola.cl/filtro/cerezas/71/)，where the URL is `https://www.diariofruticola.cl/filtro/cerezas/71/`, extract the part `https://diariofruticola.cl/filtro` to the end, which is `/`, and use it as the parameter to fill in. Therefore, the route will be [`/diariofruticola/filtro/cerezas/71`](https://rsshub.app/diariofruticola/filtro/cerezas/71).
:::

## Parameters
- `filter`: {"description": "Filter"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `diariofruticola.cl/filtro/:filter`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nIf you subscribe to [Cerezas](https://www.diariofruticola.cl/filtro/cerezas/71/)，where the URL is `https://www.diariofruticola.cl/filtro/cerezas/71/`, extract the part `https://diariofruticola.cl/filtro` to the end, which is `/`, and use it as the parameter to fill in. Therefore, the route will be [`/diariofruticola/filtro/cerezas/71`](https://rsshub.app/diariofruticola/filtro/cerezas/71).\n:::",
  "example": "/diariofruticola/filtro/cerezas/71",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "filtro.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Filtro",
  "parameters": {
    "filter": {
      "description": "Filter"
    }
  },
  "path": "/filtro/:filter{.+}",
  "radar": [
    {
      "source": [
        "diariofruticola.cl/filtro/:filter"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "diariofruticola.cl",
  "view": 0
}
```
