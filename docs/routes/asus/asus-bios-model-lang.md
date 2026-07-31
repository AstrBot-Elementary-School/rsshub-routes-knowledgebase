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
      "description": "TUF GAMING B550M-PLUS WIFI II BIOS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73745650488758272",
      "image": "https://dlcdnwebimgs.asus.com/gain/22bd771c-1a57-439b-97d2-ef75363fe11a/w185",
      "ownerUserId": null,
      "siteUrl": "https://www.asus.com.cn/Motherboards-Components/Motherboards/TUF-Gaming/TUF-GAMING-B550M-PLUS-WIFI-II/",
      "title": "TUF GAMING B550M-PLUS WIFI II BIOS",
      "type": "feed",
      "url": "rsshub://asus/bios/TUF-GAMING-B550M-PLUS-WIFI-II/zh"
    }
  ],
  "url": "www.asus.com"
}
```
