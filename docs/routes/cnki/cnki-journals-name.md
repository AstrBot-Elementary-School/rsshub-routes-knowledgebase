# 中国知网 - 期刊

## Coverage
`index-only`

## Route
- Namespace: `cnki`
- Namespace Name: `中国知网`
- Route Path: `/cnki/journals/:name`
- Route Name: `期刊`
- Example: `/cnki/journals/LKGP`
- URL: `navi.cnki.net`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Fatpandac, Derekmini, pseudoyu`
- Source Location: `journals.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 期刊缩写，可以在网址中得到


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
  - `navi.cnki.net/knavi/journals/:name/detail`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/cnki/journals/LKGP",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 68,
  "location": "journals.ts",
  "maintainers": [
    "Fatpandac",
    "Derekmini",
    "pseudoyu"
  ],
  "name": "期刊",
  "parameters": {
    "name": "期刊缩写，可以在网址中得到"
  },
  "path": "/journals/:name",
  "radar": [
    {
      "source": [
        "navi.cnki.net/knavi/journals/:name/detail"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "微纳电子技术 - Powered by RSSHub",
      "errorAt": "2026-07-28T06:57:33.591Z",
      "errorMessage": "[GET] \"https://rss.cnki.net/kns/rss.aspx?Journal=BDTQ&Virtual=knavi\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: rss.cnki.net. is not in the cert's altnames: DNS:*.cdn.myqcloud.com, DNS:*.2144.cn, DNS:*.2144.com, DNS:*.4399.com, DNS:*.5054399.com, DNS:*.58cdn.com.cn, DNS:*.bldimg.com, DNS:*.cdn-go.cn, DNS:*.cntv.qcloudcdn.com, DNS:*.danmu.com, DNS:*.dd.cdntips.net, DNS:*.dd.qq.com, DNS:*.dianping.com, DNS:*.dl.txcdns.com, DNS:*.dlied1.cdntips.net, DNS:*.dpfile.com, DNS:*.ffnews.cn, DNS:*.file.myqcloud.com, DNS:*.flash.2144.com, DNS:*.flash.cn, DNS:*.geetest.com, DNS:*.gtimg.cn, DNS:*.gtimg.com, DNS:*.hls.cdn.myqcloud.com, DNS:*.image.myqcloud.com, DNS:*.img4399.com, DNS:*.jsbchina.cn, DNS:*.lof3.xyz, DNS:*.meituan.net, DNS:*.myapp.com, DNS:*.mykeeta.net, DNS:*.qcloudcdn.com, DNS:*.qpic.cn, DNS:*.sogoucdn.com, DNS:*.suyinwealth.com, DNS:*.ugdtimg.com, DNS:*.uniqlo.cn, DNS:*.vda.v.qcloudcdn.com, DNS:*.video.myqcloud.com, DNS:*.vip.cdngot.com, DNS:*.vod-qcloud.com, DNS:*.vod.cdn.myqcloud.com, DNS:*.vod.myqcloud.com, DNS:*.vod2.myqcloud.com, DNS:*.wanyabox.com, DNS:*.weishi.qq.com, DNS:*.wx.qq.com, DNS:*.zhongcheng818.com, DNS:*.zservey.net, DNS:cdn.myqcloud.com, DNS:flash.cn, DNS:nitrome.com.4399.com, DNS:www.miniclip.com.4399pk.com, DNS:www.tencentwm.com, DNS:www.txfund.com, DNS:xpdl999.aiwan4399.com)\n",
      "id": "159265390001661952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://navi.cnki.net/knavi/journals/BDTQ/detail?uniplatform=NZKPT",
      "title": "微纳电子技术-CNKI",
      "type": "feed",
      "url": "rsshub://cnki/journals/BDTQ"
    },
    {
      "description": "电子与封装 - Powered by RSSHub",
      "errorAt": "2026-06-24T06:21:45.990Z",
      "errorMessage": "[GET] \"https://rss.cnki.net/kns/rss.aspx?Journal=DYFZ&Virtual=knavi\": <no response> fetch failed (Hostname/IP does not match certificate's altnames: Host: rss.cnki.net. is not in the cert's altnames: DNS:*.cdn.myqcloud.com, DNS:*.2144.cn, DNS:*.2144.com, DNS:*.4399.com, DNS:*.5054399.com, DNS:*.58cdn.com.cn, DNS:*.bldimg.com, DNS:*.cdn-go.cn, DNS:*.cntv.qcloudcdn.com, DNS:*.danmu.com, DNS:*.dd.cdntips.net, DNS:*.dd.qq.com, DNS:*.dianping.com, DNS:*.dl.txcdns.com, DNS:*.dlied1.cdntips.net, DNS:*.dpfile.com, DNS:*.ffnews.cn, DNS:*.file.myqcloud.com, DNS:*.flash.2144.com, DNS:*.flash.cn, DNS:*.geetest.com, DNS:*.gtimg.cn, DNS:*.gtimg.com, DNS:*.hls.cdn.myqcloud.com, DNS:*.image.myqcloud.com, DNS:*.img4399.com, DNS:*.jsbchina.cn, DNS:*.lof3.xyz, DNS:*.meituan.net, DNS:*.myapp.com, DNS:*.mykeeta.net, DNS:*.qcloudcdn.com, DNS:*.qpic.cn, DNS:*.sogoucdn.com, DNS:*.suyinwealth.com, DNS:*.ugdtimg.com, DNS:*.uniqlo.cn, DNS:*.vda.v.qcloudcdn.com, DNS:*.video.myqcloud.com, DNS:*.vip.cdngot.com, DNS:*.vod-qcloud.com, DNS:*.vod.cdn.myqcloud.com, DNS:*.vod.myqcloud.com, DNS:*.vod2.myqcloud.com, DNS:*.wanyabox.com, DNS:*.weishi.qq.com, DNS:*.wx.qq.com, DNS:*.zhongcheng818.com, DNS:*.zservey.net, DNS:cdn.myqcloud.com, DNS:flash.cn, DNS:nitrome.com.4399.com, DNS:www.miniclip.com.4399pk.com, DNS:www.tencentwm.com, DNS:www.txfund.com, DNS:xpdl999.aiwan4399.com)\n",
      "id": "159266714924499968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://navi.cnki.net/knavi/journals/DYFZ/detail?uniplatform=NZKPT",
      "title": "电子与封装-CNKI",
      "type": "feed",
      "url": "rsshub://cnki/journals/DYFZ"
    }
  ]
}
```
