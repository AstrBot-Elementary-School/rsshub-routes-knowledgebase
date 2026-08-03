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
      "description": "RT-BE88U BIOS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126962011544488963",
      "image": "https://dlcdnwebimgs.asus.com/gain/e1b78b1a-0011-4ec7-bd84-bcbaa489ecbf/w185",
      "ownerUserId": null,
      "siteUrl": "https://www.asus.com/Networking-IoT-Servers/WiFi-Routers/ASUS-Gaming-Routers/RT-BE88U/",
      "title": "RT-BE88U BIOS",
      "type": "feed",
      "url": "rsshub://asus/bios/rt-be88u"
    },
    {
      "description": "ROG Zephyrus G16 (2024) GA605 BIOS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84439902528045056",
      "image": "https://dlcdnwebimgs.asus.com/gain/9A966AAE-B61A-41C5-AA2F-5B0B35E189A2/w185",
      "ownerUserId": null,
      "siteUrl": "https://rog.asus.com/laptops/rog-zephyrus/rog-zephyrus-g16-2024-ga605/",
      "title": "ROG Zephyrus G16 (2024) GA605 BIOS",
      "type": "feed",
      "url": "rsshub://asus/bios/GA605WV"
    }
  ],
  "url": "www.asus.com"
}
```
