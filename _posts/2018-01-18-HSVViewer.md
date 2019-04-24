---
layout: post
project: yes
title: HSV Viewer
excerpt: 画像のHSVヒストグラムを立体表示
feature: "/assets/img/2018/hsv0.gif"
tags: [Software, Processing, 3DCG]
comments: true
---
# HSV Viewer

画像のHSVヒストグラムを立体表示

### Gallery


{% capture images %}
  /assets/img/2018/hsv0.gif
  /assets/img/2018/hsv1.gif
{% endcapture %}
{% include gallery images=images cols=2 %}

### Description

任意の画像を指定して、画像中の色の登場頻度(ヒストグラム)をHSV次元で立体表示。2Dはたまに見かけるけど、3D表示はない…はず。
処理が重いのでいずれコンピュートシェーダーかなにかで書き直したい。

### Activity

* 2018/1 趣味で作成

### Related Links
 
* [Github Repository](https://github.com/skishida/HSVviewer)