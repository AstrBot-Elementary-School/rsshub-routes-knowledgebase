# Email - Inbox

## Coverage
`index-only`

## Route
- Namespace: `mail`
- Namespace Name: `Email`
- Route Path: `/mail/imap/:email/:folder{.+}?`
- Route Name: `Inbox`
- Example: `/mail/imap/rss@rsshub.app`
- URL: `_None_`
- Language: `_None_`
- Categories: `other`
- Maintainers: `kt286`
- Source Location: `imap.ts`
- Source Module: `_None_`

## Description
Only support IMAP protocol, email password and other settings refer to [Route-specific Configurations](https://docs.rsshub.app/deploy/config#route-specific-configurations)

## Parameters
- `email`: Email account
- `folder`: Inbox name, `INBOX` by default


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Only support IMAP protocol, email password and other settings refer to [Route-specific Configurations](https://docs.rsshub.app/deploy/config#route-specific-configurations)",
  "example": "/mail/imap/rss@rsshub.app",
  "heat": 0,
  "location": "imap.ts",
  "maintainers": [
    "kt286"
  ],
  "name": "Inbox",
  "parameters": {
    "email": "Email account",
    "folder": "Inbox name, `INBOX` by default"
  },
  "path": "/imap/:email/:folder{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
