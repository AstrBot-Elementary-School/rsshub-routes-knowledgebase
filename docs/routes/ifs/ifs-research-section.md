# Institute for Fiscal Studies - Research and analysis

## Coverage
`index-only`

## Route
- Namespace: `ifs`
- Namespace Name: `Institute for Fiscal Studies`
- Route Path: `/ifs/research/:section?`
- Route Name: `Research and analysis`
- Example: `/ifs/research/reports`
- URL: `ifs.org.uk`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `research.ts`
- Source Module: `_None_`

## Description
Includes the article content available on the website and a PDF attachment when provided. Some reports publish an executive summary online and the complete report as a PDF.

## Parameters
- `section`: reports (default), press-releases or explainers.


## Features
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `ifs.org.uk/research-and-analysis/reports`
- `target`: `/research/reports`
### Rule 2
- `source`:
  - `ifs.org.uk/research-and-analysis/press-releases`
- `target`: `/research/press-releases`
### Rule 3
- `source`:
  - `ifs.org.uk/explainers`
- `target`: `/research/explainers`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Includes the article content available on the website and a PDF attachment when provided. Some reports publish an executive summary online and the complete report as a PDF.",
  "example": "/ifs/research/reports",
  "features": {
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "research.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Research and analysis",
  "parameters": {
    "section": "reports (default), press-releases or explainers."
  },
  "path": "/research/:section?",
  "radar": [
    {
      "source": [
        "ifs.org.uk/research-and-analysis/reports"
      ],
      "target": "/research/reports"
    },
    {
      "source": [
        "ifs.org.uk/research-and-analysis/press-releases"
      ],
      "target": "/research/press-releases"
    },
    {
      "source": [
        "ifs.org.uk/explainers"
      ],
      "target": "/research/explainers"
    }
  ],
  "topFeeds": []
}
```
