# Massachusetts Institute of Technology (MIT) - Office of Graduate Education Blog

## Coverage
`index-only`

## Route
- Namespace: `mit`
- Namespace Name: `Massachusetts Institute of Technology (MIT)`
- Route Path: `/mit/oge/:type?/:name?`
- Route Name: `Office of Graduate Education Blog`
- Example: `/mit/oge/department/electrical-engineering-and-computer-science`
- URL: `oge.mit.edu/news-and-events/blog`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LogicJake`
- Source Location: `oge.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "Filter type", "options": [{"label": "Blog category", "value": "category"}, {"label": "Department", "value": "department"}]}
- `name`: Filter value, can be found in the filter URL of the blog page, e.g. `electrical-engineering-and-computer-science` in `https://oge.mit.edu/news-and-events/blog/?_sft_department=electrical-engineering-and-computer-science`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `oge.mit.edu/news-and-events/blog`
- `target`: `/oge`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/mit/oge/department/electrical-engineering-and-computer-science",
  "heat": 0,
  "location": "oge.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "Office of Graduate Education Blog",
  "parameters": {
    "name": "Filter value, can be found in the filter URL of the blog page, e.g. `electrical-engineering-and-computer-science` in `https://oge.mit.edu/news-and-events/blog/?_sft_department=electrical-engineering-and-computer-science`",
    "type": {
      "description": "Filter type",
      "options": [
        {
          "label": "Blog category",
          "value": "category"
        },
        {
          "label": "Department",
          "value": "department"
        }
      ]
    }
  },
  "path": "/oge/:type?/:name?",
  "radar": [
    {
      "source": [
        "oge.mit.edu/news-and-events/blog"
      ],
      "target": "/oge"
    }
  ],
  "topFeeds": [],
  "url": "oge.mit.edu/news-and-events/blog"
}
```
