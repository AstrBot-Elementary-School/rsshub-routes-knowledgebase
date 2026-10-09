# re3data - Repositories by subject

## Coverage
`index-only`

## Route
- Namespace: `re3data`
- Namespace Name: `re3data`
- Route Path: `/re3data/subject/:subject`
- Route Name: `Repositories by subject`
- Example: `/re3data/subject/223`
- URL: `www.re3data.org`
- Language: `_None_`
- Categories: `study`
- Maintainers: `DIYgod`
- Source Location: `subject.tsx`
- Source Module: `_None_`

## Description
Subscribe to research repository records in a subject, using the registry's last-update dates. Each item represents a repository record, rather than papers or datasets within that repository. Updated records receive a new GUID. Subject codes are listed at [Browse by subject](https://www.re3data.org/browse/by-subject/).

## Parameters
- `subject`: DFG subject code from the subjects[] parameter of a re3data search URL, for example 21 (Biology) or 223 (Neurosciences).


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "Subscribe to research repository records in a subject, using the registry's last-update dates. Each item represents a repository record, rather than papers or datasets within that repository. Updated records receive a new GUID. Subject codes are listed at [Browse by subject](https://www.re3data.org/browse/by-subject/).",
  "example": "/re3data/subject/223",
  "heat": 0,
  "location": "subject.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Repositories by subject",
  "parameters": {
    "subject": "DFG subject code from the subjects[] parameter of a re3data search URL, for example 21 (Biology) or 223 (Neurosciences)."
  },
  "path": "/subject/:subject",
  "topFeeds": []
}
```
