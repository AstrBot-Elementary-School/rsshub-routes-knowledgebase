# MCP.so - New submissions

## Coverage
`index-only`

## Route
- Namespace: `mcp`
- Namespace Name: `MCP.so`
- Route Path: `/mcp/feed/:type?`
- Route Name: `New submissions`
- Example: `/mcp/feed`
- URL: `mcp.so`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `DIYgod`
- Source Location: `feed.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"default": "all", "description": "Submission type.", "options": [{"label": "All submissions", "value": "all"}, {"label": "Servers", "value": "servers"}, {"label": "Remote servers", "value": "remote-servers"}, {"label": "Clients", "value": "clients"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mcp.so/feed`
- `target`: `/feed`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/mcp/feed",
  "heat": 0,
  "location": "feed.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "New submissions",
  "parameters": {
    "type": {
      "default": "all",
      "description": "Submission type.",
      "options": [
        {
          "label": "All submissions",
          "value": "all"
        },
        {
          "label": "Servers",
          "value": "servers"
        },
        {
          "label": "Remote servers",
          "value": "remote-servers"
        },
        {
          "label": "Clients",
          "value": "clients"
        }
      ]
    }
  },
  "path": "/feed/:type?",
  "radar": [
    {
      "source": [
        "mcp.so/feed"
      ],
      "target": "/feed"
    }
  ],
  "topFeeds": []
}
```
