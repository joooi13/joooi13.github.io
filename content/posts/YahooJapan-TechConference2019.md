+++
title = "Yahoo Japan Tech Conference 2019に参加しました"
description = "Yahoo Japan Tech Conference 2019に参加しました"
date = "2019-01-27"
+++

## YJTC

初参加！

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Ftechconference.yahoo.co.jp%2F2019%2F" title="Yahoo! JAPAN Tech Conference 2019" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://techconference.yahoo.co.jp/2019/">techconference.yahoo.co.jp</a></cite>

以下、印象に残った部分のメモ。

## 基調講演

- ヤフーが大切にしていること。  
   ユーザのアクションを最大化しよう！
- AI に特化した[スパコン](http://d.hatena.ne.jp/keyword/%A5%B9%A5%D1%A5%B3%A5%F3)kukai（2015 年〜）のお話。
  水分に弱いのが一般的なデータセンターだが、 kukai は液体で冷やしているいて、壁に穴を開けて設置している。

> kukai とは
>
> <iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fabout.yahoo.co.jp%2Fpr%2Frelease%2F2017%2F06%2F19b%2F" title="ヤフー株式会社 - プレスルーム - Yahoo! JAPAN、ディープラーニングに特化したスパコンを開発 スパコンの省エネランキング「GREEN500」にて世界第2位を獲得" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
> <cite class="hatena-citation"><a href="https://about.yahoo.co.jp/pr/release/2017/06/19b/">about.yahoo.co.jp</a></cite>

- 簡単なことは一つもないけど、未来を作るのは楽しい。
- セキュア通信レベル向上  
   201806 TLS1.2 に切り替え  
   [SSL](http://d.hatena.ne.jp/keyword/SSL)/TLS1.0,1.1 は利用停止  
   他社の動きの影響は割と大きい。  
   [Apple](http://d.hatena.ne.jp/keyword/Apple)の[HTTPS](http://d.hatena.ne.jp/keyword/HTTPS)の話や[Google](http://d.hatena.ne.jp/keyword/Google)の話。  
   売上への影響より安全を優先し、全サービス以降を決意。
- 一般の人への告知は難しい・・判定結果のページを表示
    <iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fsecurity.yahoo.co.jp%2Fnews%2Ftls12.html" title="Yahoo!セキュリティセンター - セキュリティ強化のお知らせ" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
    <cite class="hatena-citation"><a href="https://security.yahoo.co.jp/news/tls12.html">security.yahoo.co.jp</a></cite>
    201806に決済系サービスが完了
    古い技術を捨てる旗を振ってくれると助かる！という存在
    これからはTLS1.3が待っている、
- 世界標準 CVSS に沿って取り組んでいく。
    <iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fwww.ipa.go.jp%2Fsecurity%2Fvuln%2FCVSS.html" title="共通脆弱性評価システムCVSS概説：IPA 独立行政法人 情報処理推進機構" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
    <cite class="hatena-citation"><a href="https://www.ipa.go.jp/security/vuln/CVSS.html">www.ipa.go.jp</a></cite>

<iframe src="https://www.slideshare.net/slideshow/embed_code/key/F6ooTzOMDdMWKR" width="427" height="356" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen=""></iframe>

<cite class="hatena-citation"><a href="https://www.slideshare.net/techblogyahoo/yahoo-japan-tech-conference-2019-yjtc">www.slideshare.net</a></cite>

## もう道に迷わない！ [Yahoo!](http://d.hatena.ne.jp/keyword/Yahoo%21) MAP における AR 体験

[iOS](http://d.hatena.ne.jp/keyword/iOS)限定の ARKit を使った道案内機能のお話。

- 技術面
- AR モードの開発チームは３人で、  
   開発は名古屋とデザイナーは東京という体制。
- ARKit
    <iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fgithub.com%2FProjectDent%2FARKit-CoreLocation" title="ProjectDent/ARKit-CoreLocation" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
    <cite class="hatena-citation"><a href="https://github.com/ProjectDent/ARKit-CoreLocation">github.com</a></cite>
- オブジェクトの種類の説明
- ゴールは、常にユーザの方をみるように実装している
- GeoMetry と Texture を適切に設定すると
  AR の世界に様々なものを配置できる。  
   → 少人数でもナビゲーションを使うことができる！
- AR 特有の[ユースケース](http://d.hatena.ne.jp/keyword/%A5%E6%A1%BC%A5%B9%A5%B1%A1%BC%A5%B9)について  
   2D ：  
   ルート確認や俯瞰できる  
   3D：  
   いまこの瞬間に向かうべき方向の案内
  現在地周辺にフォーカスできる
- 日本はまだまだ AR 体験に慣れている人が少ないので、  
   ルートから外れた場合のフィードバックも大切にしている。  
   ユーザにとって危ないシーンでは使えないようにする。  
   （暗闇など
- 新しいものを取り入れる場合は、  
   あらゆる可能性を想定しなければならない。
- ゴール時の癒やしにより、何度も遊びたくなる。  
   （目的地でけんさくくんが手を振って迎えてくれるのは本当にかわいい。。すこ。。

<iframe src="https://www.slideshare.net/slideshow/embed_code/key/rcE8MJMxFtdwwk" width="427" height="356" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen=""></iframe>

<cite class="hatena-citation"><a href="https://www.slideshare.net/techblogyahoo/a1-yahoo-mapar-yjtc">www.slideshare.net</a></cite>

## ライブクイズ「ワイキュー」を生み出した"内因的モチベーションドリブン"／ワイキューが目指した"楽しい時間を作るデザイン"

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Ftwitter.com%2Fwaiq_yahoojp" title="ワイキュー🎉 毎日21時〜配信中 (@waiq_yahoojp) | Twitter" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://twitter.com/waiq_yahoojp">twitter.com</a></cite>

- いままでにない利用想起への挑戦。
  戦いの場は単体から全体へ変わっている。
- 惰性的な日常にドキドキする瞬間を
- 小さくても成功体験はモチベーションあがる。  
   社内での検証。社内がワイワイするかんじ。成功体験！  
   （大きな会社の強みを感じたそう  
   仮説検証をによる成功体験をチームビルディングにつなげる！  
   どうメンバーのモチベーションが上がるかまで設計する。

<iframe src="https://www.slideshare.net/slideshow/embed_code/key/yRefPl3I5sHB43" width="427" height="356" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen=""></iframe>

<cite class="hatena-citation"><a href="https://t.co/k3BGkQn6YO">t.co</a></cite>

## ライブ動画配信サービス「ワイキュー」の作り方〜優れた社内技術で実現する、少人数のサービス開発〜

- yUI→React
- 瞬間的に回答が集中する。
  T ポイントはユーザさんの資産に関わる。
  堅牢に。

（ワイキューでやっていることとやっていないことの切り分けを
明確にした説明だった。）

- 社内に PF が揃っているから三人でも素早い開発ができる！

### 豊かなスポーツライフの実現を目指す、[スポーツナビ](http://d.hatena.ne.jp/keyword/%A5%B9%A5%DD%A1%BC%A5%C4%A5%CA%A5%D3)のシステム[アーキテクチャ](http://d.hatena.ne.jp/keyword/%A5%A2%A1%BC%A5%AD%A5%C6%A5%AF%A5%C1%A5%E3)

- 広さと深さを兼ねた豊富なデータを扱うシステム  
   広さ：幅広い競技。スポーツ全体に貢献  
   深さ：競技に特価した詳細なデータを扱っている。
- DB は競技ごとに用意されていて、  
   競技に合わせた情報を提供しやすくなっている！  
   → 段階的な対応を行うことが可能。
- 運用の話。  
   競技の盛り上がりに応じて大量のアクセスが発生する。  
   盛り上がった状態を逃さないって大変。

<iframe src="https://www.slideshare.net/slideshow/embed_code/key/wCmDKJ64GsXu7F" width="427" height="356" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen=""></iframe>

<cite class="hatena-citation"><a href="https://www.slideshare.net/techblogyahoo/b4-129181633">www.slideshare.net</a></cite>

## 拡張性あるデザインシステム構築から挑む、[GYAO!](http://d.hatena.ne.jp/keyword/GYAO%21)のウェブリニューアル

- [GYAO!](http://d.hatena.ne.jp/keyword/GYAO%21)は刷新を進めている
- ミッション：  
   レガシー WEB システムからの脱却  
   既存プロダクトの維持して事業目標を達成
- 敵を知る：  
   ヤフーで検索しているのに[GYAO!](http://d.hatena.ne.jp/keyword/GYAO%21)が上がってこない！（辛い
- SpeedIndex の指標が悪い

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fdevelopers.google.com%2Fweb%2Ftools%2Flighthouse%2Faudits%2Fspeed-index%3Fhl%3Dja" title="Speed Index  |  Tools for Web Developers
|  Google Developers" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://developers.google.com/web/tools/lighthouse/audits/speed-index?hl=ja">developers.google.com</a></cite>

段階移行でどんどんユーザさんに新しいものを届けていくことを選択した。

- パフォーマンス改善。  
   まず測る。計測できる環境を整えた。
- 初期表示の改善。
  クリティカル[レンダリング](http://d.hatena.ne.jp/keyword/%A5%EC%A5%F3%A5%C0%A5%EA%A5%F3%A5%B0)パスを撲滅。  
   AMP の恩恵でいい感じになってきている
- ピュアみ（重要）  
   同じデータを入れたら、必ず同じ表示となる[コンポーネント](http://d.hatena.ne.jp/keyword/%A5%B3%A5%F3%A5%DD%A1%BC%A5%CD%A5%F3%A5%C8)を作成すること（スナップショットテストの実現ができる）
- 組織を替えていくのは難しい
- [コンポーネント](http://d.hatena.ne.jp/keyword/%A5%B3%A5%F3%A5%DD%A1%BC%A5%CD%A5%F3%A5%C8)の仕様を体験するため、練習問題を用意。
  それを実践につなげる。新しく join した人に効果的かも

<iframe src="https://www.slideshare.net/slideshow/embed_code/key/Lt1qTWul5UCW4G" width="427" height="356" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen=""></iframe>

<cite class="hatena-citation"><a href="https://www.slideshare.net/techblogyahoo/a5-gyao-yjtc">www.slideshare.net</a></cite>

## CtoC 配信サービスのバックエンドから[iOS](http://d.hatena.ne.jp/keyword/iOS)アプリまで ～[ヤフオク](http://d.hatena.ne.jp/keyword/%A5%E4%A5%D5%A5%AA%A5%AF)!ライブの全貌と XP 開発～

- [ヤフオク](http://d.hatena.ne.jp/keyword/%A5%E4%A5%D5%A5%AA%A5%AF)！ライブの話。  
   双方向の通信機能  
   落札や出品などの一方的な通信機能
- Redis

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fredis.io%2F" title="Redis" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://redis.io/">redis.io</a></cite>

- オンメモリキャッスストレージ
  リアルタイム処理の中心となる高機能な通信経路
- [ヤフオク](http://d.hatena.ne.jp/keyword/%A5%E4%A5%D5%A5%AA%A5%AF)！は 40 機能ある
  そこにライブ機能を追加
  依存性の複雑化が課題。
- [ペアプロ](http://d.hatena.ne.jp/keyword/%A5%DA%A5%A2%A5%D7%A5%ED)楽しそうだったｗ

<iframe src="https://www.slideshare.net/slideshow/embed_code/key/dCZWWbh2MNpwlC" width="427" height="356" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen=""></iframe>

<cite class="hatena-citation"><a href="https://www.slideshare.net/techblogyahoo/a6-ctocios-xp-yjtc">www.slideshare.net</a></cite>
