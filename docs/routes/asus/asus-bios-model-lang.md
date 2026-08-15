# ASUS - BIOS

## Coverage
`index-only`

## Route
- Namespace: `asus`
- Namespace Name: `ASUS`
- Route Path: `/asus/bios/:model/:lang?`
- Route Name: `BIOS`
- Example: `/asus/bios/RT-AX88U/zh`
- URL: `www.asus.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `Fatpandac`
- Source Location: `bios.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `model`: Model, can be found in product page
- `lang`: {"default": "en", "description": "Language, provide access routes for other parts of the world", "options": [{"label": "Chinese", "value": "zh"}, {"label": "Global", "value": "en"}]}


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
  - `www.asus.com/displays-desktops/:productLine/:series/:model`
  - `www.asus.com/laptops/:productLine/:series/:model`
  - `www.asus.com/motherboards-components/:productLine/:series/:model`
  - `www.asus.com/networking-iot-servers/:productLine/:series/:model`
  - `www.asus.com/:region/displays-desktops/:productLine/:series/:model`
  - `www.asus.com/:region/laptops/:productLine/:series/:model`
  - `www.asus.com/:region/motherboards-components/:productLine/:series/:model`
  - `www.asus.com/:region/networking-iot-servers/:productLine/:series/:model`
- `target`: `/bios/:model`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/asus/bios/RT-AX88U/zh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "bios.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "BIOS",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "Language, provide access routes for other parts of the world",
      "options": [
        {
          "label": "Chinese",
          "value": "zh"
        },
        {
          "label": "Global",
          "value": "en"
        }
      ]
    },
    "model": "Model, can be found in product page"
  },
  "path": "/bios/:model/:lang?",
  "radar": [
    {
      "source": [
        "www.asus.com/displays-desktops/:productLine/:series/:model",
        "www.asus.com/laptops/:productLine/:series/:model",
        "www.asus.com/motherboards-components/:productLine/:series/:model",
        "www.asus.com/networking-iot-servers/:productLine/:series/:model",
        "www.asus.com/:region/displays-desktops/:productLine/:series/:model",
        "www.asus.com/:region/laptops/:productLine/:series/:model",
        "www.asus.com/:region/motherboards-components/:productLine/:series/:model",
        "www.asus.com/:region/networking-iot-servers/:productLine/:series/:model"
      ],
      "target": "/bios/:model"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "ROG Strix OLED XG27UCDMG BIOS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "213294544976304128",
      "image": "https://dlcdnwebimgs.asus.com/gain/A1B38038-3616-4BD6-99CD-42025598FECF/w185",
      "ownerUserId": null,
      "siteUrl": "https://rog.asus.com/monitors/27-to-31-5-inches/rog-strix-oled-xg27ucdmg/",
      "title": "ROG Strix OLED XG27UCDMG BIOS",
      "type": "feed",
      "url": "rsshub://asus/bios/XG27UCDMG"
    },
    {
      "description": "ASUS TUF Gaming A14 (2024) BIOS - Powered by RSSHub",
      "errorAt": "2026-07-03T16:36:59.049Z",
      "errorMessage": "Cannot read properties of null (reading 'Obj')\n",
      "id": "190738676600295424",
      "image": "https://dlcdnwebimgs.asus.com/gain/8ef79421-e9c6-4c8b-8529-0e0dc2a09952/w185",
      "ownerUserId": null,
      "siteUrl": "https://www.asus.com/Laptops/For-Gaming/TUF-Gaming/ASUS-TUF-Gaming-A14-2024/",
      "title": "ASUS TUF Gaming A14 (2024) BIOS",
      "type": "feed",
      "url": "rsshub://asus/bios/FA401WV"
    }
  ],
  "url": "www.asus.com"
}
```
