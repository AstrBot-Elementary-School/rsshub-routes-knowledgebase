# Arena (formerly LMSYS Chatbot Arena) - Text leaderboard updates

## Coverage
`index-only`

## Route
- Namespace: `arena`
- Namespace Name: `Arena (formerly LMSYS Chatbot Arena)`
- Route Path: `/arena/leaderboard/:category?`
- Route Name: `Text leaderboard updates`
- Example: `/arena/leaderboard`
- URL: `arena.ai`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `DIYgod`
- Source Location: `leaderboard.tsx`
- Source Module: `_None_`

## Description
Each feed contains one complete leaderboard snapshot. The GUID changes when the rankings or scores change, so readers can notify on leaderboard updates. Uses the current Arena website, which replaced chat.lmsys.org.

## Parameters
- `category`: {"default": "overall", "description": "Text leaderboard category.", "options": [{"label": "Overall", "value": "overall"}, {"label": "Coding", "value": "coding"}, {"label": "Longer Query", "value": "longer-query"}, {"label": "English", "value": "english"}, {"label": "Chinese", "value": "chinese"}, {"label": "Hard Prompts", "value": "hard-prompts"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `arena.ai/leaderboard/text`
- `target`: `/leaderboard`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Each feed contains one complete leaderboard snapshot. The GUID changes when the rankings or scores change, so readers can notify on leaderboard updates. Uses the current Arena website, which replaced chat.lmsys.org.",
  "example": "/arena/leaderboard",
  "heat": 0,
  "location": "leaderboard.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Text leaderboard updates",
  "parameters": {
    "category": {
      "default": "overall",
      "description": "Text leaderboard category.",
      "options": [
        {
          "label": "Overall",
          "value": "overall"
        },
        {
          "label": "Coding",
          "value": "coding"
        },
        {
          "label": "Longer Query",
          "value": "longer-query"
        },
        {
          "label": "English",
          "value": "english"
        },
        {
          "label": "Chinese",
          "value": "chinese"
        },
        {
          "label": "Hard Prompts",
          "value": "hard-prompts"
        }
      ]
    }
  },
  "path": "/leaderboard/:category?",
  "radar": [
    {
      "source": [
        "arena.ai/leaderboard/text"
      ],
      "target": "/leaderboard"
    }
  ],
  "topFeeds": []
}
```
