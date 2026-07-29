# Metacritic - Movies

## Coverage
`index-only`

## Route
- Namespace: `metacritic`
- Namespace Name: `Metacritic`
- Route Path: `/metacritic/movie/:sort?/:filter?`
- Route Name: `Movies`
- Example: `/metacritic/movie`
- URL: `metacritic.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `movie.ts`
- Source Module: `_None_`

## Description
| Metascore | User Score | Most Popular | Newest Releases |
| --------- | ---------- | ------------ | --------------- |
| metascore | userscore  | popular      | new             |

::: tip
The Filter parameter comes from the corresponding page URL. The following is an example:

The URL of [Action Movies to Watch on Netflix](https://www.metacritic.com/browse/movie/all/all/all-time/new/?network=netflix\&genre=action) is `https://www.metacritic.com/browse/movie/all/all/all-time/new/?network=netflix&genre=action`. The Filter parameter is `network=netflix&genre=action` and the route is [`/metacritic/movie/new/network=netflix&genre=action`](https://rsshub.app/metacritic/movie/new/network=netflix\&genre=action)
:::

## Parameters
- `sort`: Sort, see below, `new` for Newest Releases by default
- `filter`: Filter


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `metacritic.com/browse/movie/*`
- `target`: `/movie`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Metascore | User Score | Most Popular | Newest Releases |\n| --------- | ---------- | ------------ | --------------- |\n| metascore | userscore  | popular      | new             |\n\n::: tip\nThe Filter parameter comes from the corresponding page URL. The following is an example:\n\nThe URL of [Action Movies to Watch on Netflix](https://www.metacritic.com/browse/movie/all/all/all-time/new/?network=netflix\\&genre=action) is `https://www.metacritic.com/browse/movie/all/all/all-time/new/?network=netflix&genre=action`. The Filter parameter is `network=netflix&genre=action` and the route is [`/metacritic/movie/new/network=netflix&genre=action`](https://rsshub.app/metacritic/movie/new/network=netflix\\&genre=action)\n:::",
  "example": "/metacritic/movie",
  "heat": 0,
  "location": "movie.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Movies",
  "parameters": {
    "filter": "Filter",
    "sort": "Sort, see below, `new` for Newest Releases by default"
  },
  "path": "/movie/:sort?/:filter?",
  "radar": [
    {
      "source": [
        "metacritic.com/browse/movie/*"
      ],
      "target": "/movie"
    }
  ],
  "topFeeds": []
}
```
