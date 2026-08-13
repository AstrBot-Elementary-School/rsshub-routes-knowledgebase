# The New York Times - Best Seller Books

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/nytimes/book/:category?`
- Route Name: `Best Seller Books`
- Example: `/nytimes/book/combined-print-and-e-book-nonfiction`
- URL: `nytimes.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `melvinto, pseudoyu`
- Source Location: `book.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "combined-print-and-e-book-nonfiction", "description": "Category, can be found on the [official page](https://www.nytimes.com/books/best-sellers/)", "options": [{"label": "Combined Print & E-Book Nonfiction", "value": "combined-print-and-e-book-nonfiction"}, {"label": "Hardcover Nonfiction", "value": "hardcover-nonfiction"}, {"label": "Paperback Nonfiction", "value": "paperback-nonfiction"}, {"label": "Advice, How-To & Miscellaneous", "value": "advice-how-to-and-miscellaneous"}, {"label": "Combined Print & E-Book Fiction", "value": "combined-print-and-e-book-fiction"}, {"label": "Hardcover Fiction", "value": "hardcover-fiction"}, {"label": "Paperback Trade Fiction", "value": "trade-fiction-paperback"}, {"label": "Children's Middle Grade Hardcover", "value": "childrens-middle-grade-hardcover"}, {"label": "Picture Books", "value": "picture-books"}, {"label": "Series Books", "value": "series-books"}, {"label": "Young Adult Hardcover", "value": "young-adult-hardcover"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `nytimes.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/nytimes/book/combined-print-and-e-book-nonfiction",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 659,
  "location": "book.ts",
  "maintainers": [
    "melvinto",
    "pseudoyu"
  ],
  "name": "Best Seller Books",
  "parameters": {
    "category": {
      "default": "combined-print-and-e-book-nonfiction",
      "description": "Category, can be found on the [official page](https://www.nytimes.com/books/best-sellers/)",
      "options": [
        {
          "label": "Combined Print & E-Book Nonfiction",
          "value": "combined-print-and-e-book-nonfiction"
        },
        {
          "label": "Hardcover Nonfiction",
          "value": "hardcover-nonfiction"
        },
        {
          "label": "Paperback Nonfiction",
          "value": "paperback-nonfiction"
        },
        {
          "label": "Advice, How-To & Miscellaneous",
          "value": "advice-how-to-and-miscellaneous"
        },
        {
          "label": "Combined Print & E-Book Fiction",
          "value": "combined-print-and-e-book-fiction"
        },
        {
          "label": "Hardcover Fiction",
          "value": "hardcover-fiction"
        },
        {
          "label": "Paperback Trade Fiction",
          "value": "trade-fiction-paperback"
        },
        {
          "label": "Children's Middle Grade Hardcover",
          "value": "childrens-middle-grade-hardcover"
        },
        {
          "label": "Picture Books",
          "value": "picture-books"
        },
        {
          "label": "Series Books",
          "value": "series-books"
        },
        {
          "label": "Young Adult Hardcover",
          "value": "young-adult-hardcover"
        }
      ]
    }
  },
  "path": "/book/:category?",
  "radar": [
    {
      "source": [
        "nytimes.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The New York Times Best Sellers - Combined Print & E-Book Nonfiction- August 16, 2026 - Powered by RSSHub",
      "errorAt": "2026-08-10T07:17:05.822Z",
      "errorMessage": "[GET] \"https://www.nytimes.com/books/best-sellers/combined-print-and-e-book-nonfiction\": 403 Forbidden\nAuthentication failed. Access denied.\n/nytimes/book/combined-print-and-e-book-nonfiction\n[GET] \"https://www.nytimes.com/books/best-sellers/combined-print-and-e-book-nonfiction\": 403 Forbidden\n",
      "id": "56271356825466880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nytimes.com/books/best-sellers/combined-print-and-e-book-nonfiction",
      "title": "The New York Times Best Sellers - Combined Print & E-Book Nonfiction- August 16, 2026",
      "type": "feed",
      "url": "rsshub://nytimes/book/combined-print-and-e-book-nonfiction"
    },
    {
      "description": "The New York Times Best Sellers - Combined Print & E-Book Fiction- August 16, 2026 - Powered by RSSHub",
      "errorAt": "2026-08-11T15:37:56.961Z",
      "errorMessage": "Authentication failed. Access denied.\n/nytimes/book/combined-print-and-e-book-fiction\n[GET] \"https://www.nytimes.com/books/best-sellers/combined-print-and-e-book-fiction\": 403 Forbidden\n",
      "id": "62036724352164864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nytimes.com/books/best-sellers/combined-print-and-e-book-fiction",
      "title": "The New York Times Best Sellers - Combined Print & E-Book Fiction- August 16, 2026",
      "type": "feed",
      "url": "rsshub://nytimes/book/combined-print-and-e-book-fiction"
    }
  ],
  "url": "nytimes.com/",
  "view": 5
}
```
