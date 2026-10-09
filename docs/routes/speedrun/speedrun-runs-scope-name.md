# Speedrun.com - Verified runs

## Coverage
`index-only`

## Route
- Namespace: `speedrun`
- Namespace Name: `Speedrun.com`
- Route Path: `/speedrun/runs/:scope?/:name?`
- Route Name: `Verified runs`
- Example: `/speedrun/runs/game/ultrakill`
- URL: `speedrun.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `DIYgod`
- Source Location: `runs.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `scope`: Optional game or user scope; omit both parameters for all verified runs.
- `name`: Game abbreviation or player username. Required when scope is game or user.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `speedrun.com/users/:name`
- `target`: `/runs/user/:name`
### Rule 2
- `source`:
  - `speedrun.com/:name`
- `target`: `/runs/game/:name`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/speedrun/runs/game/ultrakill",
  "heat": 0,
  "location": "runs.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Verified runs",
  "parameters": {
    "name": "Game abbreviation or player username. Required when scope is game or user.",
    "scope": "Optional game or user scope; omit both parameters for all verified runs."
  },
  "path": "/runs/:scope?/:name?",
  "radar": [
    {
      "source": [
        "speedrun.com/users/:name"
      ],
      "target": "/runs/user/:name"
    },
    {
      "source": [
        "speedrun.com/:name"
      ],
      "target": "/runs/game/:name"
    }
  ],
  "topFeeds": []
}
```
