# Syosetu - Novel Updates

## Coverage
`index-only`

## Route
- Namespace: `syosetu`
- Namespace Name: `Syosetu`
- Route Path: `/syosetu/:ncode`
- Route Name: `Novel Updates`
- Example: `/syosetu/n9292ii`
- URL: `syosetu.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `eternasuno, SnowAgar25`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `ncode`: Novel code, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `Novel Updates`
- `source`:
  - `ncode.syosetu.com/:ncode`
  - `ncode.syosetu.com/:ncode/:chapter`
- `target`: `/:ncode`
### Rule 2
- `title`: `Novel Updates`
- `source`:
  - `novel18.syosetu.com/:ncode`
  - `novel18.syosetu.com/:ncode/:chapter`
- `target`: `/:ncode`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/syosetu/n9292ii",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "index.ts",
  "maintainers": [
    "eternasuno",
    "SnowAgar25"
  ],
  "name": "Novel Updates",
  "parameters": {
    "ncode": "Novel code, can be found in URL"
  },
  "path": "/:ncode",
  "radar": [
    {
      "source": [
        "ncode.syosetu.com/:ncode",
        "ncode.syosetu.com/:ncode/:chapter"
      ],
      "target": "/:ncode",
      "title": "Novel Updates"
    },
    {
      "source": [
        "novel18.syosetu.com/:ncode",
        "novel18.syosetu.com/:ncode/:chapter"
      ],
      "target": "/:ncode",
      "title": "Novel Updates"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "★アニメ第二クール、放送されました！ 各動画サイトで視聴できるので未視聴の方は是非ご確認ください！ とてもいいよ！<br><br>書籍版十四巻、コミック十一巻、発売中です。そちらもよろしくお願いします！<br><br>世界各地に存在する宝物殿とそこに眠る特殊な力の宿る宝具。富と名誉、そして力。栄光を求め、危険を顧みず宝物殿を探索するトレジャーハンター達が大暴れする時代。<br>幼馴染達と共に積年の夢であるハンターとなったクライは、最初の探索で六人の中で唯一自分だけ何の才能も持っていないことに気付く。<br>しかし、それは冒険の始まりに過ぎなかった。<br>「もう無理。こんな危険な仕事やめたい。ゲロ吐きそう」<br>「おう、わかった。つまり俺達が強くなってお前の分まで戦えばいいんだな、いいハンデだ」<br>「安心してね、クライちゃん。ちゃんと私達が守ってあげるから」<br>「あ、ストップ。そこ踏むと塵一つ残さず消滅しますよ。気をつけて、リーダー？」<br>強すぎる幼馴染に守られ、後輩や他のハンターからは頼られ、目指すは英雄と強力な宝具。<br>果たしてクライは円満にハンターをやめる事ができるのか！？<br>※勘違い系コメディです。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "193125624529934336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ncode.syosetu.com/n6093en",
      "title": "嘆きの亡霊は引退したい 〜最弱ハンターは英雄の夢を見る〜【Web版】",
      "type": "feed",
      "url": "rsshub://syosetu/n6093en"
    },
    {
      "description": "突如、コンビニ帰りに異世界へ召喚されたひきこもり学生の菜月昴。知識も技術も武力もコミュ能力もない、ないない尽くしの凡人が、チートボーナスを与えられることもなく放り込まれた異世界で必死こいて生き抜く。彼に与えられたたった一個の祝福は、『死んだら巻き戻ります』という痛みを伴う『死に戻り』のみ！ 頼れるもののいない異世界で、いったい彼は何度死に、なにを掴み取るのか。 ※血も死体も出る予定ですが、そんな派手なことにはなりません。<br><br>※当作品は2014年1月24日、ＭＦ文庫Ｊ様の方から同タイトルで書籍化させていただいております。皆様の応援のおかげです、ありがとうございます。また、ＷＥＢ版の削除・ダイジェスト化・更新停止といったことは今後も予定されておりません。書籍・ＷＥＢ共によろしくお願いします。<br><br>【祝！ アニメ化決定いたしました！】<br>皆様の応援のおかげです！ 今後もよろしくお願いします！<br><br>≪アニメ公式サイト≫<br>http://re-zero-anime.jp/ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1126165295249883136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ncode.syosetu.com/n2267be",
      "title": "Ｒｅ：ゼロから始める異世界生活",
      "type": "feed",
      "url": "rsshub://syosetu/n2267be"
    }
  ]
}
```
