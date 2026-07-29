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
  "topFeeds": []
}
```
