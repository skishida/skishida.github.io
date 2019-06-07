---
layout: post
project: yes
date: 2018-09-21
title: "回路のお医者さん"
excerpt: "電気に触れてインタラクションできる電子工作プラットフォーム"
feature: /assets/img/2018/cd.jpg
achievements: "IVRC 予選大会 参加, GUGEN 2018 共立電子産業賞受賞"
achieve_image: /assets/img/2018/cd-panel.jpg
tags: [Hardware, Tangible, Interface]
comments: true
---

# 回路のお医者さん

電流とインタラクションできる配線型デバイスと，ブレッドボード型プラットフォームによる直感的・回路学習支援キット

### Gallery

  
  {% capture images %}
  /assets/img/2018/cd.jpg
  {% endcapture %}
  {% include gallery images=images caption="IVRC" cols=1 %}

  {% capture images %}
  /assets/img/2018/cdrev2.jpg
  {% endcapture %}
  {% include gallery images=images caption="rev2" cols=1 %}

  <iframe width="560" height="315" src="https://www.youtube.com/embed/fnSSHp3P29M" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  {% capture images %}
  /assets/img/2018/DSC02703.JPG
  {% endcapture %}
  {% include gallery images=images caption="GUEN 2018" cols=1 %}

### Description

「回路のお医者さん」は，電気やその働きを直感的に感じたり操作できたりといったインタラクティブ要素を盛り込んだ，電気回路の学習支援システムです．実際の電子工作ではよく行う「ブレッドボードやジャンパワイヤで回路を作る」という作業をメタファーし，加えて「配線を握って電流を流しにくくする」といった直感的な操作が行える特別な装置を導入します．回路にふれる体験を豊かなものにすることで，回路に対する興味を深めてもらったり，今後の勉強の足がかりにしてもらったりということを狙っています．

例えば，電気回路をイメージする際，よく「水路とポンプ」のようなメタファーが用いられます．こういったたとえ話を，現実世界のホンモノの回路と重ねて表現できれば，より電気を身近に感じたり，電子工作に興味をもったりといった可能性をもたらすことができるのではないでしょうか．

中核を担うのは，「電気を触れて感じ、触って操作できる配線」デバイスです．これは，内部を通過する電流が多ければ多いほど高い頻度で震えます．配線を握ると，内部を通過する電流をせき止めることができます，力加減を変えることで、通過する電流量を連続的に変化させることもできます．

この「回路のお医者さん」では，メタファーとリアルを重ねることで，より多くの人に電気や回路制作の楽しさを感じてもらうことを目標としています．

### System

  {% capture images %}
  /assets/img/2018/cd-wire.jpg
  /assets/img/2018/cd-comp.jpg
  /assets/img/2018/cd-led.jpg
  {% endcapture %}
  {% include gallery images=images caption="部品たち" cols=3 %}

  {% capture images %}
  /assets/img/2018/cd-arc1.jpg
  /assets/img/2018/cd-arc2.jpg
  /assets/img/2018/cd-arc3.jpg
  {% endcapture %}
  {% include gallery images=images caption="製作中の様子" cols=3 %}

#### 配線デバイス

内部を通る電流が多ければ多いほど震えるようになっています．最大で5V・1A程度，直流交流問わず流すことができます．

握ると内部を通過可能な電流量，すなわち抵抗値が変わるようになっています．本体のチューブ内部に気圧センサを封じ込めることで，どこを握っても圧力検知ができるようになっています．

### Usage

実際に数百mAの直流・交流を流すことができるので，用意された電源・配線デバイスだけではなく，自分で作成した回路もこのプラットフォームで同じように動かすことができます．

### Target

電気回路の中で何が起きているのか，回路の中で部品がどういう働きをしているのかを学んだり感じたりしたいすべての人

### Value

電圧や電流といった回路の様子を画面上のシミュレーション結果や測定器の数値ではなく現実の物体の挙動・様子に反映させることで，より馴染みやすい体験を提供します．回路にふれる体験を豊かなものにすることで，回路に対する興味を深めてもらったり，今後の勉強の足がかりにしてもらったりということを狙っています．

### Future subject

握ることで抵抗値が変わる，つまり可変抵抗を実現しました．回路の受動部品には他にコンデンサとコイルが存在します．これらの値をインタラクティブに操作できるデバイスを開発予定です．

### Activity

* IVRC2018 予選参加(書類審査通過)
* GUGEN 2018 共立電子産業賞受賞

### Related Links

* [IVRC 2018](http://ivrc.net/2018/)
* [回路のお医者さん IVRC Archive](http://ivrc.net/archive/%E5%9B%9E%E8%B7%AF%E3%81%AE%E3%81%8A%E5%8C%BB%E8%80%85%E3%81%95%E3%82%932018/)
* [回路のお医者さん - GUGEN2018](https://gugen.jp/?p=5328)
  * [GUGEN2018 受賞作品一覧](https://gugen.jp/2018contest-result)
  * [電気通信大学 受賞・表彰報告ページ](https://www.uec.ac.jp/news/prize/2018/20181207_1489.html)
* [2019年度未踏IT人材発掘・育成事業公募結果について：IPA 独立行政法人 情報処理推進機構](https://www.ipa.go.jp/jinzai/mitou/2019/koubokekka_index.html)
  * 本作のコンセプトをよりブラッシュアップしたプロジェクト｢電気の様子が手に取るようにわかる回路学習ツールの開発｣が未踏事業に採択されました．
