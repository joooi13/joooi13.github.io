+++
title = "DevFest Tokyo 2018"
description = "DevFest Tokyo 2018"
date = "2018-09-08"
+++

## DevFest Tokyo 2018

DevFest Tokyo に今年も参加してきた。  
自分が聞いたセッションと自分の発表のメモです。

### Flutter アニメーションの実装方法

<iframe id="talk_frame_461999" src="//speakerdeck.com/player/d499c1f6185e49b8ac043c35701e61b3" width="710" height="596" style="border:0; padding:0; margin:0; background:transparent;" frameborder="0" allowtransparency="true" allowfullscreen="allowfullscreen" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
<cite class="hatena-citation"><a href="https://speakerdeck.com/konifar/flutter-animations-first-step">speakerdeck.com</a></cite>

アニメーションを実装する基本の流れを見せていただいた。

手順を順に見せていただき、  
毎回こにふぁーさんのセッションは非常に聞きやすくたのしい。

## PWA now feature

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fslides.com%2Ftakanorip%2Fpwa-now-and-future" title="PWA - Now and Future -" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://slides.com/takanorip/pwa-now-and-future">slides.com</a></cite>

FIRE というのを初めて知った。  
ユーザ体験を向上させる要素である。

- Fast  
  サイトの表示を早くする
- Integrated  
  他のネイティブアプリと変わらないユーザ体験を摩擦なく
- Reliable  
  どんな状況でも動く。信頼できる
- Engaging  
  魅力的な  
  一番大事なこと。

- オフラインのプッッシュ
- バックグラウンドでも ok
- ブラウザのサポート

- Polymer

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fgithub.com%2FPolymer%2Fpwa-starter-kit" title="Polymer/pwa-starter-kit" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://github.com/Polymer/pwa-starter-kit">github.com</a></cite>

- push について  
  ページをロードしたときにプッシュ通知の許可を求めるのはやめる。  
  これはアンチパターン。 → 　許可を求めるストーリーを考える

- デザインについて  
  ネイティブアプリに近いので、ネイティブアプリっぽいデザインは必要になってくる。  
  普通のアプリはオフライン時のデザインがないが必要である。  
  web に加えて考える必要があるデザインが多い。

## Firebase Overview for native application

firebase 入門

- firebase いれたい
- Prediction
- firestore

とりあえずいれとけってやつ。

- clashlitics
  おなじみのやーつ。  
  会場ではあまり入れている人はいなかった。

- Paformans
  アプリのパフォーマンスを測定  
  起動にかかる時間や滞在時間やスクリーンの描画にかかる時間などなど

- GA for Firebase

- AppIndexing

- Prediction について  
  → これ知らなかった。  
  7 日間のデータを元にユーザの次の行動を予測する  
  離脱しそう・・課金しそう・・など。  
  GA が入っているのが前提  
  push 通知にも使えて、離脱しそうなユーザだけ push 送ったりできる。  
  すごい！

## 新しい [Material Design](http://d.hatena.ne.jp/keyword/Material%20Design) と[Material Design](http://d.hatena.ne.jp/keyword/Material%20Design) Components

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fdocs.google.com%2Fpresentation%2Fd%2Fe%2F2PACX-1vQ1HaDylSIga_pthzacJOgG_Ju5GTnZyYgfOx6gZd4w6hSqWNnnre2ZW3Mrr9QNhD5kIp-iGU6ob5m2%2Fpub%3Fstart%3Dfalse%26loop%3Dfalse%26delayms%3D3000%26slide%3Did.p" title="DevFestTokyo 2018" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://docs.google.com/presentation/d/e/2PACX-1vQ1HaDylSIga_pthzacJOgG_Ju5GTnZyYgfOx6gZd4w6hSqWNnnre2ZW3Mrr9QNhD5kIp-iGU6ob5m2/pub?start=false&amp;loop=false&amp;delayms=3000&amp;slide=id.p">docs.google.com</a></cite>

yanzm さんと namiki さんと共に発表させてもらった。

一人 10 分ずつの発表で、  
資料は Google スライドを使用して共有しながらそれぞれ作成した。  
個人的には I/O のスピーカーの方達みたいに格好よい感じで  
入れ替わりつつやるのを妄想。（伝わってほしい）

自分の担当部分は、Compornent の紹介。  
ガイドラインに目を通しつつ、catalog-app をビルドして動作をいじってみて、それをまとめた。

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fmaterial.io%2Fdesign%2Fguidelines-overview%2F" title="Guidelines" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://material.io/design/guidelines-overview/">material.io</a></cite>

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fgithub.com%2Fmaterial-components%2Fmaterial-components-android%2Fblob%2Fmaster%2Fdocs%2Fcatalog-app.md" title="material-components/material-components-android" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://github.com/material-components/material-components-android/blob/master/docs/catalog-app.md">github.com</a></cite>

yanzm さん効果でたくさんの人に来ていただき、珍しく緊張したｗ

> [\#DevFest18](https://twitter.com/hashtag/DevFest18?src=hash&ref_src=twsrc%5Etfw)  
> 緊張した 😇 [pic.twitter.com/zOm4UhTl13](https://t.co/zOm4UhTl13)— じょいお (@joooi13) [September 1, 2018](https://twitter.com/joooi13/status/1035766777077059585?ref_src=twsrc%5Etfw)

登壇駆動で時間をとって触れたので、満足。 やってよかった。

## 感想

DevFest は Android だけでなく、いろんな技術の話が聞けて楽しい。 どれも勉強になった。

2 年前の DevFest に参加したことがきっかけで勉強会やコミュニティに  
参加し始めたので、毎年それを思い出すなあ・・
