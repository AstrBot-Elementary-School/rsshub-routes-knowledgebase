# 搜狐号 - 最新

## Coverage
`index-only`

## Route
- Namespace: `sohu`
- Namespace Name: `搜狐号`
- Route Path: `/sohu/mp/:xpt`
- Route Name: `最新`
- Example: `/sohu/mp/c29odXptdGhnbjZ3NEBzb2h1LmNvbQ==`
- URL: `sohu.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `HenryQW`
- Source Location: `mp.tsx`
- Source Module: `_None_`

## Description
搜狐号 ID 可以通过以下方式获取：

1. 通过浏览器搜索相关搜狐号 `果壳 site: mp.sohu.com`。
2. 通过浏览器控制台执行 `window.globalConst.mkeyConst_mkey`，返回的即为搜狐号 ID。

## Parameters
- `xpt`: 搜狐号 xpt ，可在URL中找到或搜狐号 ID


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mp.sohu.com/profile`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "搜狐号 ID 可以通过以下方式获取：\n\n1. 通过浏览器搜索相关搜狐号 `果壳 site: mp.sohu.com`。\n2. 通过浏览器控制台执行 `window.globalConst.mkeyConst_mkey`，返回的即为搜狐号 ID。",
  "example": "/sohu/mp/c29odXptdGhnbjZ3NEBzb2h1LmNvbQ==",
  "heat": 122,
  "location": "mp.tsx",
  "maintainers": [
    "HenryQW"
  ],
  "name": "最新",
  "parameters": {
    "xpt": "搜狐号 xpt ，可在URL中找到或搜狐号 ID"
  },
  "path": "/mp/:xpt",
  "radar": [
    {
      "source": [
        "mp.sohu.com/profile"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "为坚持严肃阅读的人群提供选项。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71077918646278144",
      "image": "https://5b0988e595225.cdn.sohucs.com/a_auto,c_cut,x_21,y_36,w_295,h_295/images/20190430/4d25b8b62da3483db8c7b676b03e948e.png",
      "ownerUserId": null,
      "siteUrl": "http://mp.sohu.com/profile?xpt=MWJmNTdjZjYtMTRiMi00NWI2LWE2ZDMtY2I1NmRhNTNmNDQ0",
      "title": "搜狐号 - 极昼的个人主页",
      "type": "feed",
      "url": "rsshub://sohu/mp/MWJmNTdjZjYtMTRiMi00NWI2LWE2ZDMtY2I1NmRhNTNmNDQ0"
    },
    {
      "description": "搜狐号 - 120146415 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55135298544042012",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "搜狐号 - 120146415",
      "type": "feed",
      "url": "rsshub://sohu/mp/120146415"
    }
  ]
}
```
