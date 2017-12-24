---
layout: post
project: yes
date: 2010-01-01
title: "ロジックICを利用したゲーム"
excerpt: "LEDマトリックス上で実行されるゲーム"
feature: /assets/img/2014/logicgame.jpg
tags: [Hardware, Circuit, LogicIC]
comments: true
---
# ロジックICを利用したゲーム

  AND、OR、シフトレジスタ、10進カウンタなどの74ロジックICを組み合わせて、簡単なミニゲームを設計・実装するという部活の伝統。

### Gallery

{% capture images %}
  /assets/img/2014/logicgame.jpg
{% endcapture %}
{% include gallery images=images caption="画像はイメージです" cols=1%}


### Description

  LEDのマトリクス上で行われるゲーム。論理回路でゲームを作成しており、具体的には自機LEDと敵機LEDの信号をANDに入れると｢敵機と自機の当たり判定｣ができたり、シフトレジスタの入力に自機LEDとボタン入力の信号のANDを入れることで｢ボタンを押すと自機がいる地点から弾が発射｣などの機能をもたせている。マイコンなどでプログラミングを行わずにゲームを作成するという試みで、2009年はゲームの仕様を部活の先輩と相談し、回路を作成してもらい、はんだ付け。2011年は後輩の考えたゲームの仕様を満たすように回路設計。

### Technique

* 7400 series Logic IC * 60~100 pcs


### Activity

  * 2010年5月 文化祭にて展示
  * 2011年 後輩の回路設計


### Related Links

* [麻布学園物理部無線班](http://butumu.com/)