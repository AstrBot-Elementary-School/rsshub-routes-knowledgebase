# JAVLibrary - Videos by categories

## Coverage
`index-only`

## Route
- Namespace: `javlibrary`
- Namespace Name: `JAVLibrary`
- Route Path: `/javlibrary/videos/genre/:genre?/:language?/:mode?`
- Route Name: `Videos by categories`
- Example: `/javlibrary/genre/amjq/en`
- URL: `javlibrary.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `genre.ts`
- Source Module: `_None_`

## Description
| videos with comments (by date) | everything (by date) |
| ------------------------------ | -------------------- |
| 1                              | 2                    |

::: tip
See [Categories](https://www.javlibrary.com/en/genres.php) to view all categories.
:::

## Parameters
- `genre`: Category, Acme · Orgasm by default, as `amjq`
- `language`: Language, see below, Japanese by default, as `ja`
- `mode`: Mode, see below, videos with comments (by date) by default, as `1`


## Features
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| videos with comments (by date) | everything (by date) |\n| ------------------------------ | -------------------- |\n| 1                              | 2                    |\n\n::: tip\nSee [Categories](https://www.javlibrary.com/en/genres.php) to view all categories.\n:::",
  "example": "/javlibrary/genre/amjq/en",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "genre.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Videos by categories",
  "parameters": {
    "genre": "Category, Acme · Orgasm by default, as `amjq`",
    "language": "Language, see below, Japanese by default, as `ja`",
    "mode": "Mode, see below, videos with comments (by date) by default, as `1`"
  },
  "path": [
    "/videos/genre/:genre?/:language?/:mode?",
    "/genre/:genre?/:language?/:mode?"
  ],
  "topFeeds": []
}
```
