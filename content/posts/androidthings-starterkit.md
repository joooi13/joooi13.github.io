+++
title = "Android Things Starter Kitを試す"
description = "Android Things Starter Kitを試す"
date = "2019-09-08"
+++

引っ越しをしたら
[Android Things Starter Kit](http://d.hatena.ne.jp/keyword/Android) が発掘されたので  
今更作ってみることにした。(ごめんなさい)

## [Android](http://d.hatena.ne.jp/keyword/Android) Things とは

Google 提供の IoT のプラットフォーム。
現在の位置付けは、下記のようなお知らせの通り。

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fdevelopers-jp.googleblog.com%2F2019%2F02%2Fan-update-on-android-things.html" title="Android Things についてのお知らせ" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://developers-jp.googleblog.com/2019/02/an-update-on-android-things.html">developers-jp.googleblog.com</a></cite>

## [Android](http://d.hatena.ne.jp/keyword/Android) Things Starter kit とは

[Android Things](http://d.hatena.ne.jp/keyword/Android)を体験できる。  
必要なものは全て入っていて、何か買い足したりする必要なく入門ができる。
電子工作未経験でもお手軽に実施できて嬉しい。

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fdeveloper.android.com%2Fthings%2Fget-started%2Fkits" title="Get started with kits  |  Android Things  |  Android Developers" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://developer.android.com/things/get-started/kits">developer.android.com</a></cite>

開封するとこんな感じ

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190825202149p:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190825/20190825202149.png "f:id:joooi13:20190825202149p:plain")</span>

## 組み立て

tutorial を元に通りに組み立て。30-40 分くらいあればできる。  
サポートアプリもある。

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fandroidthings.withgoogle.com%2F%23!%2Fkits%2Fstarter-kit" title="Build with Android Things" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://androidthings.withgoogle.com/#!/kits/starter-kit">androidthings.withgoogle.com</a></cite>

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dcom.google.android.things.companion%26hl%3Den" title="Android Things Toolkit - Apps on Google Play" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://play.google.com/store/apps/details?id=com.google.android.things.companion&amp;hl=en">play.google.com</a></cite>

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190825202327p:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190825/20190825202327.png "f:id:joooi13:20190825202327p:plain")</span>

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190825202423p:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190825/20190825202423.png "f:id:joooi13:20190825202423p:plain")</span>

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190825202450p:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190825/20190825202450.png "f:id:joooi13:20190825202450p:plain")</span>

## CodeLab

日本語版の CodeLab が理解しやすそうだったので、こちらにチャレンジ。  
作成した Kit と PC を接続して、AndroidStudio で build することができる。

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fcodelabs.developers.google.com%2Fcodelabs%2Fandroidthings-playground-jp%2F%230" title="Android Things であそぼう！" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://codelabs.developers.google.com/codelabs/androidthings-playground-jp/#0">codelabs.developers.google.com</a></cite>

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fgithub.com%2Fandroidthings%2Fdrivers-samples" title="androidthings/drivers-samples" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://github.com/androidthings/drivers-samples">github.com</a></cite>

ディスプレイに任意の文字を表示してみたり、ブザーを鳴らしたり。

[Android](http://d.hatena.ne.jp/keyword/Android)センサーを使って温度や湿度を感知できるので、
晴れだったら SUNNY...と表示させたりすることもできそう。

<span itemscope="" itemtype="http://schema.org/Photograph">![f:id:joooi13:20190908173939j:plain](https://cdn-ak.f.st-hatena.com/images/fotolife/j/joooi13/20190908/20190908173939.jpg "f:id:joooi13:20190908173939j:plain")</span>

<iframe src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fgithub.com%2Fandroidthings%2Fsample-tensorflow-imageclassifier" title="androidthings/sample-tensorflow-imageclassifier" class="embed-card embed-webcard" scrolling="no" frameborder="0" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;"></iframe>
<cite class="hatena-citation"><a href="https://github.com/androidthings/sample-tensorflow-imageclassifier">github.com</a></cite>

やってみるとかなりお手軽にできた！
