# at home - 貸店舗

## Coverage
`index-only`

## Route
- Namespace: `athome`
- Namespace Name: `at home`
- Route Path: `/athome/rent-store/:pref/:city`
- Route Name: `貸店舗`
- Example: `/athome/rent-store/tokyo/shinjuku-city`
- URL: `www.athome.co.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `rent-store.ts`
- Source Module: `_None_`

## Description
貸店舗 listings on アットホーム for one 市区町村，newest first.

This route needs a browser, and the browser is not a convenience. The page is Angular Universal SSR behind a JavaScript interstitial, and only the settled page carries the `#serverApp-state` payload the route reads. A plain HTTP client is served normally for about four requests and then gets the 「認証中」 interstitial on everything afterwards, and pacing the requests 3s apart does not lift it. A browser gets a far larger allowance — dozens of navigations — but **is not exempt**: push hard enough and it is refused too, so this is a matter of cadence rather than of using the right client. The interstitial reloads itself, which stops a `domcontentloaded` navigation from ever settling, so the page is opened with `commit` and every wait is bounded here, against a deadline measured from the start of the request rather than from the navigation.

Being refused and being served slowly are told apart rather than guessed at: one check watches for `#serverApp-state` and for the 認証中 title at the same time, so a refused client is reported in about a second while a slow one keeps the full window. That window is wide (26s for the list page) because `#serverApp-state` sits roughly 62% of the way into a 2.4MB document — a throttled client has to receive about 1.5MB before it can appear — and the width costs a refused client nothing. For the same reason the page's images, fonts, stylesheets and media are not fetched at all, leaving the connection to the one response that matters; scripts are left alone, since the interstitial needs one to clear itself. **Being blocked is a volume problem, not a retry problem** — poll less often rather than retrying, and keep the cache warm. The route waits for `#serverApp-state` on the **list** page and **throws if it never appears**, so an unsettled page surfaces as an error rather than as a silently empty feed.

情報公開日，the coordinates and the fee detail exist only on each listing's own page, so the route visits them — reusing one browser tab rather than opening a browser per listing, and caching per listing so a repeated poll only pays for listings it has not seen before.

Each of those visits is a full browser navigation, and on a modest VPS one can take several seconds, so at the default `limit` a cold cache can outrun RSSHub's own 30s request timeout. Enrichment therefore runs on a 20s budget: listings reached within it are enriched, the rest are returned with their list-page fields and a warning is logged. A cache hit needs no navigation and so never draws on the budget, which means a warm poll still returns everything fully enriched. A listing whose own page fails is logged and returned with list-page fields too — only the list page failing is fatal.

**Everything the listing itself states — 所在地 down to the 丁目，階，面積，賃料 and the ward — is already on the list page.** If that is all you need, `detail=0` skips the per-listing visits entirely and makes this an ordinary fast route; `listed_at`，`pubDate`, the coordinates and the fee detail are then `null`.

**The site's own ordering is not chronological**, so the feed is re-sorted by 情報公開日，newest first. Without that a newly published listing could sit well down the list and never reach a monitor watching the first page.

`_extra` follows the shared listing shape: `listed_at` and `pubDate` from 情報公開日，`heavy_food_ok` and `business_limit` from the published notice flags (「飲食店不可」 etc.), `fixtures_transfer_jpy` from 造作譲渡，`tags` from the site's 特徴 list, and `condition` / `prev_business` from the 店舗プラス block (`isInuki` / `isSkeleton` / `lastTenanto`) rather than guessed from prose — though most listings leave those two unset. `deposit_months` prefers 保証金 and falls back to 敷金.

`raw` additionally carries what the shared contract has no field for: `lat` / `lng`, the full 所在地 including its 都道府県，建物名 + 部屋番号，設備，築年月，敷引，償却，その他一時金 and the 定期借家 flag.

| Query    | Description                                                               | Default |
| -------- | ------------------------------------------------------------------------- | ------- |
| `limit`  | Listings to return, max 30                                                | 10      |
| `detail` | `0` skips the per-listing detail visits and returns list-page fields only | `1`     |

## Parameters
- `pref`: {"description": "都道府県 slug, e.g. `tokyo`, `kanagawa`"}
- `city`: {"description": "市区町村 slug as the site spells it — `shinjuku-city`, `minato-city`, `yokohama_naka-city`. Note the underscore in 政令指定都市 slugs; a hyphen there 404s."}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.athome.co.jp/rent_store/:pref/:city/list`
- `target`: `/rent-store/:pref/:city`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "貸店舗 listings on アットホーム for one 市区町村，newest first.\n\nThis route needs a browser, and the browser is not a convenience. The page is Angular Universal SSR behind a JavaScript interstitial, and only the settled page carries the `#serverApp-state` payload the route reads. A plain HTTP client is served normally for about four requests and then gets the 「認証中」 interstitial on everything afterwards, and pacing the requests 3s apart does not lift it. A browser gets a far larger allowance — dozens of navigations — but **is not exempt**: push hard enough and it is refused too, so this is a matter of cadence rather than of using the right client. The interstitial reloads itself, which stops a `domcontentloaded` navigation from ever settling, so the page is opened with `commit` and every wait is bounded here, against a deadline measured from the start of the request rather than from the navigation.\n\nBeing refused and being served slowly are told apart rather than guessed at: one check watches for `#serverApp-state` and for the 認証中 title at the same time, so a refused client is reported in about a second while a slow one keeps the full window. That window is wide (26s for the list page) because `#serverApp-state` sits roughly 62% of the way into a 2.4MB document — a throttled client has to receive about 1.5MB before it can appear — and the width costs a refused client nothing. For the same reason the page's images, fonts, stylesheets and media are not fetched at all, leaving the connection to the one response that matters; scripts are left alone, since the interstitial needs one to clear itself. **Being blocked is a volume problem, not a retry problem** — poll less often rather than retrying, and keep the cache warm. The route waits for `#serverApp-state` on the **list** page and **throws if it never appears**, so an unsettled page surfaces as an error rather than as a silently empty feed.\n\n情報公開日，the coordinates and the fee detail exist only on each listing's own page, so the route visits them — reusing one browser tab rather than opening a browser per listing, and caching per listing so a repeated poll only pays for listings it has not seen before.\n\nEach of those visits is a full browser navigation, and on a modest VPS one can take several seconds, so at the default `limit` a cold cache can outrun RSSHub's own 30s request timeout. Enrichment therefore runs on a 20s budget: listings reached within it are enriched, the rest are returned with their list-page fields and a warning is logged. A cache hit needs no navigation and so never draws on the budget, which means a warm poll still returns everything fully enriched. A listing whose own page fails is logged and returned with list-page fields too — only the list page failing is fatal.\n\n**Everything the listing itself states — 所在地 down to the 丁目，階，面積，賃料 and the ward — is already on the list page.** If that is all you need, `detail=0` skips the per-listing visits entirely and makes this an ordinary fast route; `listed_at`，`pubDate`, the coordinates and the fee detail are then `null`.\n\n**The site's own ordering is not chronological**, so the feed is re-sorted by 情報公開日，newest first. Without that a newly published listing could sit well down the list and never reach a monitor watching the first page.\n\n`_extra` follows the shared listing shape: `listed_at` and `pubDate` from 情報公開日，`heavy_food_ok` and `business_limit` from the published notice flags (「飲食店不可」 etc.), `fixtures_transfer_jpy` from 造作譲渡，`tags` from the site's 特徴 list, and `condition` / `prev_business` from the 店舗プラス block (`isInuki` / `isSkeleton` / `lastTenanto`) rather than guessed from prose — though most listings leave those two unset. `deposit_months` prefers 保証金 and falls back to 敷金.\n\n`raw` additionally carries what the shared contract has no field for: `lat` / `lng`, the full 所在地 including its 都道府県，建物名 + 部屋番号，設備，築年月，敷引，償却，その他一時金 and the 定期借家 flag.\n\n| Query    | Description                                                               | Default |\n| -------- | ------------------------------------------------------------------------- | ------- |\n| `limit`  | Listings to return, max 30                                                | 10      |\n| `detail` | `0` skips the per-listing detail visits and returns list-page fields only | `1`     |",
  "example": "/athome/rent-store/tokyo/shinjuku-city",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportRadar": true
  },
  "heat": 0,
  "location": "rent-store.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "貸店舗",
  "parameters": {
    "city": {
      "description": "市区町村 slug as the site spells it — `shinjuku-city`, `minato-city`, `yokohama_naka-city`. Note the underscore in 政令指定都市 slugs; a hyphen there 404s."
    },
    "pref": {
      "description": "都道府県 slug, e.g. `tokyo`, `kanagawa`"
    }
  },
  "path": "/rent-store/:pref/:city",
  "radar": [
    {
      "source": [
        "www.athome.co.jp/rent_store/:pref/:city/list"
      ],
      "target": "/rent-store/:pref/:city"
    }
  ],
  "topFeeds": [],
  "url": "www.athome.co.jp"
}
```
