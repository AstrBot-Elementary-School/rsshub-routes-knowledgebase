# ManyBooks - Book lists

## Coverage
`index-only`

## Route
- Namespace: `manybooks`
- Namespace Name: `ManyBooks`
- Route Path: `/manybooks/books/:list?`
- Route Name: `Book lists`
- Example: `/manybooks/books/trending`
- URL: `manybooks.net`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `DIYgod`
- Source Location: `books.tsx`
- Source Module: `_None_`

## Description
For the ManyBooks blog, use the native feed at <https://manybooks.net/rss.xml>.

## Parameters
- `list`: {"default": "free", "description": "Homepage book list.", "options": [{"label": "Free ebooks and deals", "value": "free"}, {"label": "Editor's choice", "value": "editor"}, {"label": "Trending books", "value": "trending"}, {"label": "Popular classics", "value": "classics"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `manybooks.net`
- `target`: `/books`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "For the ManyBooks blog, use the native feed at <https://manybooks.net/rss.xml>.",
  "example": "/manybooks/books/trending",
  "heat": 0,
  "location": "books.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Book lists",
  "parameters": {
    "list": {
      "default": "free",
      "description": "Homepage book list.",
      "options": [
        {
          "label": "Free ebooks and deals",
          "value": "free"
        },
        {
          "label": "Editor's choice",
          "value": "editor"
        },
        {
          "label": "Trending books",
          "value": "trending"
        },
        {
          "label": "Popular classics",
          "value": "classics"
        }
      ]
    }
  },
  "path": "/books/:list?",
  "radar": [
    {
      "source": [
        "manybooks.net"
      ],
      "target": "/books"
    }
  ],
  "topFeeds": []
}
```
