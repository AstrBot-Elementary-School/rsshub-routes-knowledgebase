# Cybercrime Magazine - News

## Coverage
`index-only`

## Route
- Namespace: `cybersecurityventures`
- Namespace Name: `Cybercrime Magazine`
- Route Path: `/cybersecurityventures/news/:category?`
- Route Name: `News`
- Example: `/cybersecurityventures/news`
- URL: `cybersecurityventures.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `KarasuShin`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "today", "description": "news category", "options": [{"label": "Today's News", "value": "today"}, {"label": "Cyberattacks", "value": "intrusion-daily-cyber-threat-alert"}, {"label": "Ransomware", "value": "ransomware-minute"}, {"label": "Cryptocrime", "value": "cryptocrime"}, {"label": "Hack Blotter", "value": "hack-blotter"}, {"label": "VC Deal Flow", "value": "cybersecurity-venture-capital-vc-deals"}, {"label": "M&A Tracker", "value": "mergers-and-acquisitions-report"}]}


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `cybersecurityventures.com/today`
- `target`: `/news/today`
- `title`: `Today's News`
### Rule 2
- `source`:
  - `cybersecurityventures.com/intrusion-daily-cyber-threat-alert`
- `target`: `/news/intrusion-daily-cyber-threat-alert`
- `title`: `Cyberattacks`
### Rule 3
- `source`:
  - `cybersecurityventures.com/ransomware-minute`
- `target`: `/news/ransomware-minute`
- `title`: `Ransomware`
### Rule 4
- `source`:
  - `cybersecurityventures.com/cryptocrime`
- `target`: `/news/cryptocrime`
- `title`: `Cryptocrime`
### Rule 5
- `source`:
  - `cybersecurityventures.com/hack-blotter`
- `target`: `/news/hack-blotter`
- `title`: `Hack Blotter`
### Rule 6
- `source`:
  - `cybersecurityventures.com/cybersecurity-venture-capital-vc-deals`
- `target`: `/news/cybersecurity-venture-capital-vc-deals`
- `title`: `VC Deal Flow`
### Rule 7
- `source`:
  - `cybersecurityventures.com/mergers-and-acquisitions-report`
- `target`: `/news/mergers-and-acquisitions-report`
- `title`: `M&A Tracker`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/cybersecurityventures/news",
  "features": {
    "supportRadar": true
  },
  "heat": 24,
  "location": "news.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "News",
  "parameters": {
    "category": {
      "default": "today",
      "description": "news category",
      "options": [
        {
          "label": "Today's News",
          "value": "today"
        },
        {
          "label": "Cyberattacks",
          "value": "intrusion-daily-cyber-threat-alert"
        },
        {
          "label": "Ransomware",
          "value": "ransomware-minute"
        },
        {
          "label": "Cryptocrime",
          "value": "cryptocrime"
        },
        {
          "label": "Hack Blotter",
          "value": "hack-blotter"
        },
        {
          "label": "VC Deal Flow",
          "value": "cybersecurity-venture-capital-vc-deals"
        },
        {
          "label": "M&A Tracker",
          "value": "mergers-and-acquisitions-report"
        }
      ]
    }
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "cybersecurityventures.com/today"
      ],
      "target": "/news/today",
      "title": "Today's News"
    },
    {
      "source": [
        "cybersecurityventures.com/intrusion-daily-cyber-threat-alert"
      ],
      "target": "/news/intrusion-daily-cyber-threat-alert",
      "title": "Cyberattacks"
    },
    {
      "source": [
        "cybersecurityventures.com/ransomware-minute"
      ],
      "target": "/news/ransomware-minute",
      "title": "Ransomware"
    },
    {
      "source": [
        "cybersecurityventures.com/cryptocrime"
      ],
      "target": "/news/cryptocrime",
      "title": "Cryptocrime"
    },
    {
      "source": [
        "cybersecurityventures.com/hack-blotter"
      ],
      "target": "/news/hack-blotter",
      "title": "Hack Blotter"
    },
    {
      "source": [
        "cybersecurityventures.com/cybersecurity-venture-capital-vc-deals"
      ],
      "target": "/news/cybersecurity-venture-capital-vc-deals",
      "title": "VC Deal Flow"
    },
    {
      "source": [
        "cybersecurityventures.com/mergers-and-acquisitions-report"
      ],
      "target": "/news/mergers-and-acquisitions-report",
      "title": "M&A Tracker"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Today's News - Cybercrime Magazine - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82873456631622656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cybersecurityventures.com//today",
      "title": "Today's News - Cybercrime Magazine",
      "type": "feed",
      "url": "rsshub://cybersecurityventures/news/today"
    },
    {
      "description": "Today's News - Cybercrime Magazine - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "83099263306649600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cybersecurityventures.com//today",
      "title": "Today's News - Cybercrime Magazine",
      "type": "feed",
      "url": "rsshub://cybersecurityventures/news"
    }
  ],
  "view": 0
}
```
