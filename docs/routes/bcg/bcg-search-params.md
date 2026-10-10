# Boston Consulting Group - Search

## Coverage
`index-only`

## Route
- Namespace: `bcg`
- Namespace Name: `Boston Consulting Group`
- Route Path: `/bcg/search/:params?`
- Route Name: `Search`
- Example: `/bcg/search/f5=00000171-f12e-d394-ab73-f3ef7fc10000&f7=00000171-f17b-d394-ab73-f3fbae0d0000&f3=00000172-0efd-d58d-a97a-5eff51730077`
- URL: `www.bcg.com/search`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `DIYgod`
- Source Location: `infrastructure.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `params`: The query string of a www.bcg.com/search URL (`q`, `f3`, `f5`, `f7`, ...). Sort defaults to date (`s=1`).


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bcg.com/search`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/bcg/search/f5=00000171-f12e-d394-ab73-f3ef7fc10000&f7=00000171-f17b-d394-ab73-f3fbae0d0000&f3=00000172-0efd-d58d-a97a-5eff51730077",
  "heat": 0,
  "location": "infrastructure.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Search",
  "parameters": {
    "params": "The query string of a www.bcg.com/search URL (`q`, `f3`, `f5`, `f7`, ...). Sort defaults to date (`s=1`)."
  },
  "path": "/search/:params?",
  "radar": [
    {
      "source": [
        "www.bcg.com/search"
      ]
    }
  ],
  "topFeeds": [],
  "url": "www.bcg.com/search"
}
```
