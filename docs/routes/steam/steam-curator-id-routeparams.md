# Steam - Latest Curator Reviews

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/steam/curator/:id/:routeParams?`
- Route Name: `Latest Curator Reviews`
- Example: `/steam/curator/34646096-80-Days`
- URL: `store.steampowered.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `naremloa, fenxer`
- Source Location: `curator.tsx`
- Source Module: `_None_`

## Description
The Latest reviews from a Steam Curator.

## Parameters
- `id`: Steam curator id. It usually consists of a series of numbers and the curator's name.
- `routeParams`: {"description": "Extra parameters to filter the reviews. The following parameters are supported:\n| Key             | Description                                                                                   | Accepts                                    | Defaults to |\n| --------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------ | ----------- |\n| `curations`   | Review type to filter by. `0`: Recommended, `1`: Not Recommended, `2`: Informational    | `0`/`1`/`2`/`0,1`/`0,2`/`1,2`  |             |\n| `tagids`      | Tag to filter by. Details are provided below.                                                 | use comma to separate multiple tagid       |             |\n\nNote: There is a [‘Popular Tags’](https://store.steampowered.com/tag/browse) page where you can find many but not all of the tags. The tag’s ID is in the `data-tagid` attribute of the element.Steam does not currently provide a page that comprehensively lists all tags, and you may need to explore alternative ways to find them.\n\nExamples:\n* `/steam/curator/34646096-80-Days/curations=&tagids=`\n* `/steam/curator/34646096-80-Days/curations=0&tagids=19`\n* `/steam/curator/34646096-80-Days/curations=0,2&tagids=19,21`\n"}


## Features
_None_

## Radar
### Rule 1
- `title`: `Latest Curator Reviews`
- `source`:
  - `store.steampowered.com/curator/:id`
- `target`: `/curator/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "The Latest reviews from a Steam Curator.",
  "example": "/steam/curator/34646096-80-Days",
  "heat": 18,
  "location": "curator.tsx",
  "maintainers": [
    "naremloa",
    "fenxer"
  ],
  "name": "Latest Curator Reviews",
  "parameters": {
    "id": "Steam curator id. It usually consists of a series of numbers and the curator's name.",
    "routeParams": {
      "description": "Extra parameters to filter the reviews. The following parameters are supported:\n| Key             | Description                                                                                   | Accepts                                    | Defaults to |\n| --------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------ | ----------- |\n| `curations`   | Review type to filter by. `0`: Recommended, `1`: Not Recommended, `2`: Informational    | `0`/`1`/`2`/`0,1`/`0,2`/`1,2`  |             |\n| `tagids`      | Tag to filter by. Details are provided below.                                                 | use comma to separate multiple tagid       |             |\n\nNote: There is a [‘Popular Tags’](https://store.steampowered.com/tag/browse) page where you can find many but not all of the tags. The tag’s ID is in the `data-tagid` attribute of the element.Steam does not currently provide a page that comprehensively lists all tags, and you may need to explore alternative ways to find them.\n\nExamples:\n* `/steam/curator/34646096-80-Days/curations=&tagids=`\n* `/steam/curator/34646096-80-Days/curations=0&tagids=19`\n* `/steam/curator/34646096-80-Days/curations=0,2&tagids=19,21`\n"
    }
  },
  "path": "/curator/:id/:routeParams?",
  "radar": [
    {
      "source": [
        "store.steampowered.com/curator/:id"
      ],
      "target": "/curator/:id",
      "title": "Latest Curator Reviews"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Steam Curator 34646096-80-Days Reviews - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "99268471009976320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://store.steampowered.com/curator/34646096-80-Days/ajaxgetfilteredrecommendations/?query&start=0&count=10&dynamic_data=&sort=recent&app_types=&reset=false&curations=&tagids=",
      "title": "Steam Curator 34646096-80-Days Reviews",
      "type": "feed",
      "url": "rsshub://steam/curator/34646096-80-Days"
    },
    {
      "description": "Steam Curator 32686107-Ѕtеам-250 Reviews - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "99407355545093120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://store.steampowered.com/curator/32686107-%D0%85t%D0%B5%D0%B0%D0%BC-250/ajaxgetfilteredrecommendations/?query&start=0&count=10&dynamic_data=&sort=recent&app_types=&reset=false&curations=&tagids=",
      "title": "Steam Curator 32686107-Ѕtеам-250 Reviews",
      "type": "feed",
      "url": "rsshub://steam/curator/32686107-%D0%85t%D0%B5%D0%B0%D0%BC-250"
    }
  ]
}
```
