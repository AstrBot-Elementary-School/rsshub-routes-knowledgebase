# Google - Scholar Author Citations

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/citations/:id`
- Route Name: `Scholar Author Citations`
- Example: `/google/citations/mlmE4JMAAAAJ`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `KellyHwong, const7`
- Source Location: `citations.ts`
- Source Module: `_None_`

## Description
The parameter id in the route is the id in the URL of the user's Google Scholar reference page, for example `https://scholar.google.com/citations?user=mlmE4JMAAAAJ` to `mlmE4JMAAAAJ`.

Query parameters are also supported here, for example `https://scholar.google.com/citations?user=mlmE4JMAAAAJ&sortby=pubdate` to `mlmE4JMAAAAJ&sortby=pubdate`. Please make sure that the user id (`mlmE4JMAAAAJ` in this case) should be the first parameter in the query string.

## Parameters
- `id`: N


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "The parameter id in the route is the id in the URL of the user's Google Scholar reference page, for example `https://scholar.google.com/citations?user=mlmE4JMAAAAJ` to `mlmE4JMAAAAJ`.\n\nQuery parameters are also supported here, for example `https://scholar.google.com/citations?user=mlmE4JMAAAAJ&sortby=pubdate` to `mlmE4JMAAAAJ&sortby=pubdate`. Please make sure that the user id (`mlmE4JMAAAAJ` in this case) should be the first parameter in the query string.",
  "example": "/google/citations/mlmE4JMAAAAJ",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 718,
  "location": "citations.ts",
  "maintainers": [
    "KellyHwong",
    "const7"
  ],
  "name": "Scholar Author Citations",
  "parameters": {
    "id": "N"
  },
  "path": "/citations/:id",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Google Scholar Citation Monitor: Li Fei-Fei; Profile: Professor of Computer Science, Stanford University; HomePage: http://vision.stanford.edu/ - Powered by RSSHub",
      "errorAt": "2026-07-20T23:45:50.395Z",
      "errorMessage": "502 \n[GET] \"https://scholar.google.com/citations?user=rDfyQnIAAAAJ\": 403 Forbidden\n",
      "id": "62830172236416000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://scholar.google.com/citations?user=rDfyQnIAAAAJ",
      "title": "Google Scholar: Li Fei-Fei",
      "type": "feed",
      "url": "rsshub://google/citations/rDfyQnIAAAAJ"
    },
    {
      "description": "Google Scholar Citation Monitor: Yan Meng; Profile: School of Computer Science; HomePage: http://yan4meng.github.io/ - Powered by RSSHub",
      "errorAt": "2026-01-20T08:57:27.374Z",
      "errorMessage": "[GET] \"https://scholar.google.com/citations?user=mlmE4JMAAAAJ\": 403 Forbidden\n",
      "id": "65416235395226624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://scholar.google.com/citations?user=mlmE4JMAAAAJ",
      "title": "Google Scholar: Yan Meng",
      "type": "feed",
      "url": "rsshub://google/citations/mlmE4JMAAAAJ"
    }
  ]
}
```
