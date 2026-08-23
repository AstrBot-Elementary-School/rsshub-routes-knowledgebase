# Massachusetts Institute of Technology (MIT) - Scratch User Projects

## Coverage
`index-only`

## Route
- Namespace: `mit`
- Namespace Name: `Massachusetts Institute of Technology (MIT)`
- Route Path: `/mit/scratch/user-projects/:username`
- Route Name: `Scratch User Projects`
- Example: `/mit/scratch/user-projects/abee`
- URL: `mit.edu`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Skota11`
- Source Location: `scratch/user-projects.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Scratch username


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
  - `scratch.mit.edu/users/:username/projects/`
- `target`: `/scratch/user-projects/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/mit/scratch/user-projects/abee",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "scratch/user-projects.ts",
  "maintainers": [
    "Skota11"
  ],
  "name": "Scratch User Projects",
  "parameters": {
    "username": "Scratch username"
  },
  "path": "/scratch/user-projects/:username",
  "radar": [
    {
      "source": [
        "scratch.mit.edu/users/:username/projects/"
      ],
      "target": "/scratch/user-projects/:username"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
