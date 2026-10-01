# NASA - Astronomy Picture of the Day

## Coverage
`index-only`

## Route
- Namespace: `nasa`
- Namespace Name: `NASA`
- Route Path: `/nasa/apod`
- Route Name: `Astronomy Picture of the Day`
- Example: `/nasa/apod`
- URL: `apod.nasa.govundefined`
- Language: `_None_`
- Categories: `picture, popular`
- Maintainers: `nczitzk, williamgateszhao`
- Source Location: `apod.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `apod.nasa.govundefined`

## Raw JSON
```json
{
  "categories": [
    "picture",
    "popular"
  ],
  "example": "/nasa/apod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 59135,
  "location": "apod.ts",
  "maintainers": [
    "nczitzk",
    "williamgateszhao"
  ],
  "name": "Astronomy Picture of the Day",
  "parameters": {},
  "path": "/apod",
  "radar": [
    {
      "source": [
        "apod.nasa.govundefined"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "NASA Astronomy Picture of the Day - Powered by RSSHub",
      "errorAt": "2026-09-29T22:22:11.968Z",
      "errorMessage": "[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\nFailed to fetch\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\nAuthentication failed. Access denied.\n/nasa/apod\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> ERR_TLS_CERT_ALTNAME_INVALID fetching \"https://apod.nasa.gov/apod/archivepix.html\". For more information, pass `verbose: true` in the second argument to fetch()\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\nAuthentication failed. Access denied.\n/nasa/apod\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\nAuthentication failed. Access denied.\n/nasa/apod\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: apod.nasa.gov. is not in the cert's altnames: DNS:*.go-vip.co, DNS:go-vip.co)\n[GET] \"https://apod.nasa.gov/apod/archivepix.html\": 526 <none>\n",
      "id": "41356263889737728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://apod.nasa.gov/apod/archivepix.html",
      "title": "NASA Astronomy Picture of the Day",
      "type": "feed",
      "url": "rsshub://nasa/apod"
    }
  ],
  "url": "apod.nasa.govundefined",
  "view": 2
}
```
