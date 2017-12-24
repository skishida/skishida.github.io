---
layout: page
title: About shoki kishida
tags: [about]
date: 2017-12-24
comments: false
---

## 経歴

* 2015年 私立麻布高等学校 卒業
* 2015年 国立大学法人電気通信大学総合情報学科 入学

## スキル

### 電子工作

* 株式会社スイッチサイエンスにてアルバイト(2015/8~)
  * ブログ執筆 : [kishida - スイッチサイエンス マガジン](http://mag.switch-science.com/author/kishida/)
  * 利用ドキュメントの作成 例 : [ESP-WROOM-02 Wi-Fi シールドの使い方 - スイッチサイエンスのおまけ](http://trac.switch-science.com/wiki/ESP-WROOM-02_AT)
  * Arduino向けサンプルプログラムの作成 例 : [AQM1248A Simple Library](https://github.com/SWITCHSCIENCE/samplecodes/tree/master/AQM1248A_breakout/Arduino/AQM1248A_lib)
  * 他、基板設計など
  

## 趣味

### 電子工作

  ![](./img/board.jpg)

  自分が思った動作を現実世界に落とし込むことができる楽しさを求めて続けています。中高校時代はロボット等を作る部活で部長を務めました。

### お絵かき

  ![](./img/nenga2017.jpg)

  上手い人はいくらでもいますが、自分の頭の中の絵は自分でしか描けないと思っているので、地道にやっています。

### 写真

  ![](./img/photo.jpg)

  色や構図などお絵かきでの表現の幅が広がればいいなぁと夢見て最近はじめました。


## [業績](/achievements)

<div class="post-list">
  {% for post in site.posts %} 
      {% if post.achievements != null %}
  <ul>
      <li>
          <hr>
          <a class="zoombtn" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
          <p>{{ post.excerpt }}</p>
          <p>{{ post.achievements}}</p>
          <a href="{{ site.url }}{{ post.url }}" class="btn zoombtn">Read More</a>
      </li>
  </ul>
      {% endif %}
  {% endfor %}
</div>