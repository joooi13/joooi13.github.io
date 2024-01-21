+++
title = "CameraX"
description = "CameraX"
date = "2019-09-16"
+++

## CameraX

CameraX は、カメラアプリの開発を簡単に行うための [Jetpack](http://d.hatena.ne.jp/keyword/Jetpack) サポート ライブラリです。
Camera2 API の機能を簡単に利用することができます。  
Android5.0 以上で動作するので、幅広いデバイスで安定して動作させることができます。

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fdeveloper.android.com%2Ftraining%2Fcamerax" title="CameraX overview  |  Android Developers" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://developer.android.com/training/camerax">developer.android.com</a></cite>

## CodeLab

例によって CodeLab やりましょう。

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fcodelabs.developers.google.com%2Fcodelabs%2Fcamerax-getting-started%2F%230" title="Getting Started with CameraX" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://codelabs.developers.google.com/codelabs/camerax-getting-started/#0">codelabs.developers.google.com</a></cite>

- まずは build.gradle の dependencies に CamelaX を追加(alpha 版)
- View を用意。TextureView(高速描画の view component)

  \*端末で Camera の使用を許可するため、AndroidManifest.[xml](http://d.hatena.ne.jp/keyword/xml)に[パーミッション](http://d.hatena.ne.jp/keyword/%A5%D1%A1%BC%A5%DF%A5%C3%A5%B7%A5%E7%A5%F3)を追加

- [preview](http://d.hatena.ne.jp/keyword/preview)を実装。撮影する枠の大きさなど指定
  \*ImageCapture 実装。この時、撮影のトリガーとなるボタンも view に追加
- ImageAnalysis クラス実装

  （Firebase や MLKit などの[機械学習](http://d.hatena.ne.jp/keyword/%B5%A1%B3%A3%B3%D8%BD%AC)で使えるようです ）

- [preview](http://d.hatena.ne.jp/keyword/preview)

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190916120414p:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190916/20190916120414.png "f:id:joooi13:20190916120414p:plain")</span>

- ImageCapture

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190916120428p:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190916/20190916120428.png "f:id:joooi13:20190916120428p:plain")</span>

- ImageAnalysis

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190916120457p:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190916/20190916120457.png "f:id:joooi13:20190916120457p:plain")</span>

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190916121338p:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190916/20190916121338.png "f:id:joooi13:20190916121338p:plain")</span>

それぞれ bindToLifecycle で読み込ませる。

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190916120509p:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190916/20190916120509.png "f:id:joooi13:20190916120509p:plain")</span>

ImageAnalysis ってなんぞや？と思い質問させていただたところ、  
画像の平均輝度を数値で計ることができるとのことでした。

- 検証 1：明るい壁を撮影

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190916121811p:plain:w250](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190916/20190916121811.png "f:id:joooi13:20190916121811p:plain:w250")</span>

- 検証 2：真っ暗にして撮影

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190916121831p:plain:w250](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190916/20190916121831.png "f:id:joooi13:20190916121831p:plain:w250")</span>

## まとめ

Camera2 API を使うと、プレビューを表示させることすら大変らしい・・  
ですが、CameraX を使うと、簡単なカメラアプリを作る程度ならとても良さそう！
