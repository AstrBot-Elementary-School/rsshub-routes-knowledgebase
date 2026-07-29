# Asian to lick - Category

## Coverage
`index-only`

## Route
- Namespace: `asiantolick`
- Namespace Name: `Asian to lick`
- Route Path: `/asiantolick/category/:id`
- Route Name: `Category`
- Example: `/asiantolick/category/90`
- URL: `asiantolick.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| Category   | id   |
| ---------- | ---- |
| Lolita     | 90   |
| Hot Sister | 91   |
| Cosplay    | 1030 |
| Sexy       | 93   |
| Others     | 94   |
| Thailand   | 99   |
| Magazine   | 100  |
| Hard Sexy  | 103  |

## Parameters
- `id`: Category id, can be found in URL


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `asiantolick.com/category-:id`
- `target`: `/category/:id`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "| Category   | id   |\n| ---------- | ---- |\n| Lolita     | 90   |\n| Hot Sister | 91   |\n| Cosplay    | 1030 |\n| Sexy       | 93   |\n| Others     | 94   |\n| Thailand   | 99   |\n| Magazine   | 100  |\n| Hard Sexy  | 103  |",
  "example": "/asiantolick/category/90",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "id": "Category id, can be found in URL"
  },
  "path": "/category/:id",
  "radar": [
    {
      "source": [
        "asiantolick.com/category-:id"
      ],
      "target": "/category/:id"
    }
  ],
  "topFeeds": [],
  "url": "asiantolick.com/"
}
```
