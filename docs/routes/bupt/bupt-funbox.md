# 北京邮电大学 - BTBYR 趣味盒

## Coverage
`index-only`

## Route
- Namespace: `bupt`
- Namespace Name: `北京邮电大学`
- Route Path: `/bupt/funbox`
- Route Name: `BTBYR 趣味盒`
- Example: `/bupt/funbox`
- URL: `bupt.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `prnake`
- Source Location: `funbox.ts`
- Source Module: `_None_`

## Description
由于需要登陆 BTBYR 后的 Cookie 值，所以只能自建，并且部署和订阅端均需支持 IPV6 网络或使用镜像站点。

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "镜像站地址，默认为 `https://bt.byr.cn/`", "name": "BTBYR_HOST"}, {"description": "登陆 BTBYR 后的 Cookie 值", "name": "BTBYR_COOKIE"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "由于需要登陆 BTBYR 后的 Cookie 值，所以只能自建，并且部署和订阅端均需支持 IPV6 网络或使用镜像站点。",
  "example": "/bupt/funbox",
  "features": {
    "requireConfig": [
      {
        "description": "镜像站地址，默认为 `https://bt.byr.cn/`",
        "name": "BTBYR_HOST"
      },
      {
        "description": "登陆 BTBYR 后的 Cookie 值",
        "name": "BTBYR_COOKIE"
      }
    ]
  },
  "heat": 0,
  "location": "funbox.ts",
  "maintainers": [
    "prnake"
  ],
  "name": "BTBYR 趣味盒",
  "path": "/funbox",
  "topFeeds": []
}
```
