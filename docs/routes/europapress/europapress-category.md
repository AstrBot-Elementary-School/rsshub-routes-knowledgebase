# Europa Press - Category

## Coverage
`index-only`

## Route
- Namespace: `europapress`
- Namespace Name: `Europa Press`
- Route Path: `/europapress/:category?`
- Route Name: `Category`
- Example: `/europapress`
- URL: `www.europapress.es`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Categories

| España   | Internacional | Economía | Deportes |
| -------- | ------------- | -------- | -------- |
| nacional | internacional | economía | deportes |

| Cultura | Sociedad | Ciencia | Salud |
| ------- | -------- | ------- | ----- |
| cultura | sociedad | ciencia | salud |

| Tecnología | Comunicados | Estar donde estés |
| ---------- | ----------- | ----------------- |
| tecnología | comunicados | estar-donde-estes |

| Andalucía | Aragón | Cantabria | Castilla-La Mancha |
| --------- | ------ | --------- | ------------------ |
| andalucia | aragon | cantabria | castilla-lamancha  |

| Castilla y León | Cataluña  | Extremadura | Galicia |
| --------------- | --------- | ----------- | ------- |
| castilla-y-leon | catalunya | extremadura | galicia |

| Islas Canarias | Islas Baleares | Madrid | País Vasco |
| -------------- | -------------- | ------ | ---------- |
| islas-canarias | illes-balears  | madrid | euskadi    |

| La Rioja | C. Valenciana        | Navarra | Asturias |
| -------- | -------------------- | ------- | -------- |
| la-rioja | comunitat-valenciana | navarra | asturias |

| Murcia | Ceuta y Melilla |
| ------ | --------------- |
| murcia | ceuta-y-melilla |

## Parameters
- `category`: Category, see below, Home by default
- `limit`: {"default": "10", "description": "Number of articles, 10 by default"}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Categories\n\n| España   | Internacional | Economía | Deportes |\n| -------- | ------------- | -------- | -------- |\n| nacional | internacional | economía | deportes |\n\n| Cultura | Sociedad | Ciencia | Salud |\n| ------- | -------- | ------- | ----- |\n| cultura | sociedad | ciencia | salud |\n\n| Tecnología | Comunicados | Estar donde estés |\n| ---------- | ----------- | ----------------- |\n| tecnología | comunicados | estar-donde-estes |\n\n| Andalucía | Aragón | Cantabria | Castilla-La Mancha |\n| --------- | ------ | --------- | ------------------ |\n| andalucia | aragon | cantabria | castilla-lamancha  |\n\n| Castilla y León | Cataluña  | Extremadura | Galicia |\n| --------------- | --------- | ----------- | ------- |\n| castilla-y-leon | catalunya | extremadura | galicia |\n\n| Islas Canarias | Islas Baleares | Madrid | País Vasco |\n| -------------- | -------------- | ------ | ---------- |\n| islas-canarias | illes-balears  | madrid | euskadi    |\n\n| La Rioja | C. Valenciana        | Navarra | Asturias |\n| -------- | -------------------- | ------- | -------- |\n| la-rioja | comunitat-valenciana | navarra | asturias |\n\n| Murcia | Ceuta y Melilla |\n| ------ | --------------- |\n| murcia | ceuta-y-melilla |",
  "example": "/europapress",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category, see below, Home by default",
    "limit": {
      "default": "10",
      "description": "Number of articles, 10 by default"
    }
  },
  "path": "/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
