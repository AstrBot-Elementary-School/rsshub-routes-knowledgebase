# Maven - Central Feed

## Coverage
`index-only`

## Route
- Namespace: `maven`
- Namespace Name: `Maven`
- Route Path: `/maven/central/:group/:artifact`
- Route Name: `Central Feed`
- Example: `/maven/central/org.springframework/spring-core`
- URL: `central.sonatype.com/`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `chrisis58`
- Source Location: `central.ts`
- Source Module: `_None_`

## Description
Get the latest versions of a Maven artifact from Maven Central Repository.

## Parameters
- `group`: {"description": "The group ID of the Maven artifact (e.g., org.springframework)"}
- `artifact`: {"description": "The artifact ID of the Maven artifact (e.g., spring-core)"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: false

## Radar
### Rule 1
- `source`:
  - `central.sonatype.com/artifact/:group/:artifact/:suffix`
  - `central.sonatype.com/artifact/:group/:artifact`
- `target`: `/central/:group/:artifact`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Get the latest versions of a Maven artifact from Maven Central Repository.",
  "example": "/maven/central/org.springframework/spring-core",
  "features": {
    "antiCrawler": false,
    "nsfw": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "central.ts",
  "maintainers": [
    "chrisis58"
  ],
  "name": "Central Feed",
  "parameters": {
    "artifact": {
      "description": "The artifact ID of the Maven artifact (e.g., spring-core)"
    },
    "group": {
      "description": "The group ID of the Maven artifact (e.g., org.springframework)"
    }
  },
  "path": "/central/:group/:artifact",
  "radar": [
    {
      "source": [
        "central.sonatype.com/artifact/:group/:artifact/:suffix",
        "central.sonatype.com/artifact/:group/:artifact"
      ],
      "target": "/central/:group/:artifact"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "central.sonatype.com/"
}
```
