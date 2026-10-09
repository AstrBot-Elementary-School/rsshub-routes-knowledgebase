# Fruit Data Kings - Product news

## Coverage
`index-only`

## Route
- Namespace: `fruitdatakings`
- Namespace Name: `Fruit Data Kings`
- Route Path: `/fruitdatakings/news/:product?`
- Route Name: `Product news`
- Example: `/fruitdatakings/news/cherry`
- URL: `www.fruitdatakings.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `DIYgod`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Includes news headlines and links from the public product-news form. Source headlines may be shortened; full articles are hosted by external publishers. Paid market charts are not part of this feed.

## Parameters
- `product`: Product selected in the website’s news form, defaults to cherry. For example: cherry or kiwi.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.fruitdatakings.com/rss_category/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Includes news headlines and links from the public product-news form. Source headlines may be shortened; full articles are hosted by external publishers. Paid market charts are not part of this feed.",
  "example": "/fruitdatakings/news/cherry",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Product news",
  "parameters": {
    "product": "Product selected in the website’s news form, defaults to cherry. For example: cherry or kiwi."
  },
  "path": "/news/:product?",
  "radar": [
    {
      "source": [
        "www.fruitdatakings.com/rss_category/"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": []
}
```
