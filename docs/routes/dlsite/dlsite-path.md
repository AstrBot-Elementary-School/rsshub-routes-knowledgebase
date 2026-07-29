# DLsite - General

## Coverage
`index-only`

## Route
- Namespace: `dlsite`
- Namespace Name: `DLsite`
- Route Path: `/dlsite/:path{.+}?`
- Route Name: `General`
- Example: `/dlsite/home/new`
- URL: `dlsite.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `z-index/index.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to this route, you can first visit the site and specify filters, and then fill in the field after `https://www.dlsite.com/` in the URL of the corresponding page at the path of the route. Here are 2 examples.

If you subscribe to [Voice / ASMR works Release date - New to Old](https://www.dlsite.com/home/works/type/=/work_type_category/audio/order/release_d), at the URL of the corresponding page `https://www.dlsite.com/home/works/type/=/work_type_category/audio/order/release_d` and after `https://www.dlsite.com/` is `home/works/type/=/work_type_category/audio/order/release_d`, which can be seen as the path. In this case the route is [`/dlsite/home/works/type/=/work_type_category/audio/order/release_d`](https://rsshub.app/dlsite/home/works/type/=/work_type_category/audio/order/release_d)

If you subscribe to [Discounted works Latest Discounts - Newest to Oldest](https://www.dlsite.com/home/works/discount/=/order/cstart_d), at the URL of the corresponding page `https://www.dlsite.com/home/works/discount/=/order/cstart_d` and after `https://www.dlsite.com/` is `home/works/discount/=/order/cstart_d`, which can be seen as the path. In this case the route is [`/dlsite/home/works/discount/=/order/cstart_d`](https://rsshub.app/dlsite/home/works/discount/=/order/cstart_d)
:::

## Parameters
- `path`: Path, `/home/new` by default, as Release Calendar


## Features
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\nTo subscribe to this route, you can first visit the site and specify filters, and then fill in the field after `https://www.dlsite.com/` in the URL of the corresponding page at the path of the route. Here are 2 examples.\n\nIf you subscribe to [Voice / ASMR works Release date - New to Old](https://www.dlsite.com/home/works/type/=/work_type_category/audio/order/release_d), at the URL of the corresponding page `https://www.dlsite.com/home/works/type/=/work_type_category/audio/order/release_d` and after `https://www.dlsite.com/` is `home/works/type/=/work_type_category/audio/order/release_d`, which can be seen as the path. In this case the route is [`/dlsite/home/works/type/=/work_type_category/audio/order/release_d`](https://rsshub.app/dlsite/home/works/type/=/work_type_category/audio/order/release_d)\n\nIf you subscribe to [Discounted works Latest Discounts - Newest to Oldest](https://www.dlsite.com/home/works/discount/=/order/cstart_d), at the URL of the corresponding page `https://www.dlsite.com/home/works/discount/=/order/cstart_d` and after `https://www.dlsite.com/` is `home/works/discount/=/order/cstart_d`, which can be seen as the path. In this case the route is [`/dlsite/home/works/discount/=/order/cstart_d`](https://rsshub.app/dlsite/home/works/discount/=/order/cstart_d)\n:::",
  "example": "/dlsite/home/new",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "z-index/index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "General",
  "parameters": {
    "path": "Path, `/home/new` by default, as Release Calendar"
  },
  "path": "/:path{.+}?",
  "topFeeds": []
}
```
