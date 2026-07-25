# Google - Scholar Keywords Monitoring

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/scholar/:query`
- Route Name: `Scholar Keywords Monitoring`
- Example: `/google/scholar/data+visualization`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `HenryQW`
- Source Location: `scholar.ts`
- Source Module: `_None_`

## Description
::: warning
Google Scholar has strict anti-crawling mechanism implemented, the demo below doesn't guarantee availability. Please deploy your own instance as it might increase the stability.
:::

1. Basic mode, sample query is the keywords desired, eg.「data visualization」, <https://rsshub.app/google/scholar/data+visualization>.

2. Advanced mode, visit [Google Scholar](https://scholar.google.com/schhp?hl=en\&as_sdt=0,5), click the top left corner and select「Advanced Search」, fill in your conditions and submit the search. The URL should look like this: <https://scholar.google.com/scholar?as_q=data+visualization&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=&as_publication=&as_ylo=2018&as_yhi=&hl=en&as_sdt=0%2C5>, copy everything after `https://scholar.google.com/scholar?` from the URL and use it as the query for this route. The complete URL for the above example should look like this: <https://rsshub.app/google/scholar/as_q=data+visualization&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=&as_publication=&as_ylo=2018&as_yhi=&hl=en&as_sdt=0%2C5>.

## Parameters
- `query`: query statement which supports「Basic」and「Advanced」modes


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
  "description": "::: warning\nGoogle Scholar has strict anti-crawling mechanism implemented, the demo below doesn't guarantee availability. Please deploy your own instance as it might increase the stability.\n:::\n\n1. Basic mode, sample query is the keywords desired, eg.「data visualization」, <https://rsshub.app/google/scholar/data+visualization>.\n\n2. Advanced mode, visit [Google Scholar](https://scholar.google.com/schhp?hl=en\\&as_sdt=0,5), click the top left corner and select「Advanced Search」, fill in your conditions and submit the search. The URL should look like this: <https://scholar.google.com/scholar?as_q=data+visualization&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=&as_publication=&as_ylo=2018&as_yhi=&hl=en&as_sdt=0%2C5>, copy everything after `https://scholar.google.com/scholar?` from the URL and use it as the query for this route. The complete URL for the above example should look like this: <https://rsshub.app/google/scholar/as_q=data+visualization&as_epq=&as_oq=&as_eq=&as_occt=any&as_sauthors=&as_publication=&as_ylo=2018&as_yhi=&hl=en&as_sdt=0%2C5>.",
  "example": "/google/scholar/data+visualization",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 311,
  "location": "scholar.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "Scholar Keywords Monitoring",
  "parameters": {
    "query": "query statement which supports「Basic」and「Advanced」modes"
  },
  "path": "/scholar/:query",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Google Scholar Monitor Query: data+visualization - Powered by RSSHub",
      "errorAt": "2026-01-18T23:04:09.995Z",
      "errorMessage": "[GET] \"https://scholar.google.com/scholar?q=data+visualization\": 403 Forbidden\n",
      "id": "71387723438538752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://scholar.google.com/scholar?q=data+visualization",
      "title": "Google Scholar Monitor: data+visualization",
      "type": "feed",
      "url": "rsshub://google/scholar/data%2Bvisualization"
    },
    {
      "description": "Google Scholar Monitor Query: data+visualization - Powered by RSSHub",
      "errorAt": "2026-07-20T02:36:22.925Z",
      "errorMessage": "502 \n[GET] \"https://scholar.google.com/scholar?q=data+visualization\": 403 Forbidden\n",
      "id": "62187667735435337",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://scholar.google.com/scholar?q=data+visualization",
      "title": "Google Scholar Monitor: data+visualization",
      "type": "feed",
      "url": "rsshub://google/scholar/data+visualization"
    }
  ]
}
```
