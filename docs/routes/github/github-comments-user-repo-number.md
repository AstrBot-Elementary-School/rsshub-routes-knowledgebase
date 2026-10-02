# GitHub - Issue / Pull Request comments

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/comments/:user/:repo/:number?`
- Route Name: `Issue / Pull Request comments`
- Example: `/github/comments/DIYgod/RSSHub/8116`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL, FliegendeWurst`
- Source Location: `comments.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User / Org name
- `repo`: Repo name
- `number`: Issue or pull number (if omitted: all)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `github.com/:user/:repo/:type`
  - `github.com/:user/:repo/:type/:number`
- `target`: `/comments/:user/:repo/:number?`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/comments/DIYgod/RSSHub/8116",
  "heat": 291,
  "location": "comments.ts",
  "maintainers": [
    "TonyRL",
    "FliegendeWurst"
  ],
  "name": "Issue / Pull Request comments",
  "parameters": {
    "number": "Issue or pull number (if omitted: all)",
    "repo": "Repo name",
    "user": "User / Org name"
  },
  "path": "/comments/:user/:repo/:number?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/:type",
        "github.com/:user/:repo/:type/:number"
      ],
      "target": "/comments/:user/:repo/:number?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "RSSNext/Folo: Issue & Pull request comments - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "128737368338530304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/RSSNext/Folo",
      "title": "RSSNext/Folo: Issue & Pull request comments",
      "type": "feed",
      "url": "rsshub://github/comments/RSSNext/Folo"
    },
    {
      "description": "521xueweihan/HelloGitHub: Issue & Pull request comments - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73345605774977024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/521xueweihan/HelloGitHub",
      "title": "521xueweihan/HelloGitHub: Issue & Pull request comments",
      "type": "feed",
      "url": "rsshub://github/comments/521xueweihan/HelloGitHub"
    }
  ]
}
```
