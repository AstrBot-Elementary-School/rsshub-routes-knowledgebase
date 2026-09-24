# 中华人民共和国农业农村部 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `gov/moa`
- Namespace Name: `中华人民共和国农业农村部`
- Route Path: `/gov/moa/suburl/:suburl{.+}`
- Route Name: `新闻`
- Example: `/gov/moa/suburl/gk/zcjd/`
- URL: `moa.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Origami404, lyqluis`
- Source Location: `moa.ts`
- Source Module: `_None_`

## Description
更多例子：

- `农业农村部动态`的网页链接是`http://www.moa.gov.cn/xw/zwdt/`, 对应的`suburl`是`xw/zwdt`
- `财务公开`的网页链接是`http://www.moa.gov.cn/gk/cwgk_1/`, 对应的`suburl`是`gk/cwgk_1`
- 像[政策法规](http://www.moa.gov.cn/gk/zcfg/)这种页面 (`http://www.moa.gov.cn/gk/zcfg/`), 它**不是**一个合法的分类目录，它是`法律`, `行政法规`, `部门规章`等一堆栏目的集合，这时候请点开对应栏目的`更多 >>`进入栏目的最下级目录，再根据上面的规则提取`suburl`
- 特别地，`图片新闻`对应的`suburl`为`xw/tpxw/`, `最新公开`对应的`suburl`为`govpublic`, `数据>最新发布`对应的`suburl`为`sj/zxfb`

## Parameters
- `suburl`: 下级目录，请使用最下级的目录


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `moa.gov.cn/`
- `target`: `/suburl/:suburl`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "更多例子：\n\n- `农业农村部动态`的网页链接是`http://www.moa.gov.cn/xw/zwdt/`, 对应的`suburl`是`xw/zwdt`\n- `财务公开`的网页链接是`http://www.moa.gov.cn/gk/cwgk_1/`, 对应的`suburl`是`gk/cwgk_1`\n- 像[政策法规](http://www.moa.gov.cn/gk/zcfg/)这种页面 (`http://www.moa.gov.cn/gk/zcfg/`), 它**不是**一个合法的分类目录，它是`法律`, `行政法规`, `部门规章`等一堆栏目的集合，这时候请点开对应栏目的`更多 >>`进入栏目的最下级目录，再根据上面的规则提取`suburl`\n- 特别地，`图片新闻`对应的`suburl`为`xw/tpxw/`, `最新公开`对应的`suburl`为`govpublic`, `数据>最新发布`对应的`suburl`为`sj/zxfb`",
  "example": "/gov/moa/suburl/gk/zcjd/",
  "heat": 51,
  "location": "moa.ts",
  "maintainers": [
    "Origami404",
    "lyqluis"
  ],
  "name": "新闻",
  "parameters": {
    "suburl": "下级目录，请使用最下级的目录"
  },
  "path": "/suburl/:suburl{.+}",
  "radar": [
    {
      "source": [
        "moa.gov.cn/"
      ],
      "target": "/suburl/:suburl"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "中华人民共和国农业农村部 - 政策解读 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63817336539566080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.moa.gov.cn/gk/zcjd/",
      "title": "中华人民共和国农业农村部 - 政策解读",
      "type": "feed",
      "url": "rsshub://gov/moa/suburl/gk/zcjd/"
    },
    {
      "description": "中华人民共和国农业农村部 - 全国信息联播 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "110574279350074368",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.moa.gov.cn/xw/qg/",
      "title": "中华人民共和国农业农村部 - 全国信息联播",
      "type": "feed",
      "url": "rsshub://gov/moa/suburl/xw/qg/"
    }
  ],
  "url": "moa.gov.cn/"
}
```
