# 北京市人民政府 - 科学技术委员会、中关村科技园区管理委员会

## Coverage
`index-only`

## Route
- Namespace: `gov/beijing`
- Namespace Name: `北京市人民政府`
- Route Path: `/gov/beijing/kw/:channel{.+}`
- Route Name: `科学技术委员会、中关村科技园区管理委员会`
- Example: `/gov/beijing/kw/zwgk/tzgg`
- URL: `www.beijing.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `kw/index.ts`
- Source Module: `_None_`

## Description
频道参数填写官网栏目 URL 中域名后的路径。如通知公告页面

`https://kw.beijing.gov.cn/zwgk/tzgg/` 对应 `/gov/beijing/kw/zwgk/tzgg`。

旧版 `col736` 等编号仍按原栏目地址请求；官网已移除的旧地址需改用当前栏目路径。

## Parameters
- `channel`: 官网栏目路径，如 zwgk/tzgg；旧 col 编号仍按原地址请求


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `kw.beijing.gov.cn/zwgk/tzgg/`
  - `kw.beijing.gov.cn/zwgk/tzgg/*`
- `target`: `/kw/zwgk/tzgg`
### Rule 2
- `source`:
  - `kw.beijing.gov.cn/col/:channel/index.html`
- `target`: `/kw/:channel`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "频道参数填写官网栏目 URL 中域名后的路径。如通知公告页面\n\n`https://kw.beijing.gov.cn/zwgk/tzgg/` 对应 `/gov/beijing/kw/zwgk/tzgg`。\n\n旧版 `col736` 等编号仍按原栏目地址请求；官网已移除的旧地址需改用当前栏目路径。",
  "example": "/gov/beijing/kw/zwgk/tzgg",
  "heat": 0,
  "location": "kw/index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "科学技术委员会、中关村科技园区管理委员会",
  "parameters": {
    "channel": "官网栏目路径，如 zwgk/tzgg；旧 col 编号仍按原地址请求"
  },
  "path": "/kw/:channel{.+}",
  "radar": [
    {
      "source": [
        "kw.beijing.gov.cn/zwgk/tzgg/",
        "kw.beijing.gov.cn/zwgk/tzgg/*"
      ],
      "target": "/kw/zwgk/tzgg"
    },
    {
      "source": [
        "kw.beijing.gov.cn/col/:channel/index.html"
      ],
      "target": "/kw/:channel"
    }
  ],
  "topFeeds": []
}
```
