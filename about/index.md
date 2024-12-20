---
layout: page
title: About shoki kishida
tags: [about]
date: 2017-12-24
comments: false
---

## 経歴

* 2015年 私立 麻布高等学校 卒業
* 2019年 国立 電気通信大学総合情報学科 卒業
* 2021年 国立 電気通信大学大学院情報理工学研究科 情報学専攻 卒業

## 活動歴概要

* HackU2016東京会場 最優秀賞&HappyHacking賞 受賞
* HackDay2017学生部門最優秀賞 受賞
  * [無重力体験しました](/ug)
* セキュリティキャンプ全国大会 2017 参加
* セキュリティミニキャンプ東北 2017 チューター参加
* セキュリティキャンプ全国大会 2018 チューター参加
* ROHM OPEN HACK CHALLENGE 2017 特別賞 受賞
* 平成29年度 電気通信大学 学生表彰 (上記HackDayおよびROHCにて表彰)
* IVRC2018 予選大会 参加
* GUGEN2018 共立電子産業賞 受賞
* 2019年度未踏IT人材発掘・育成事業 採択&スーパクリエータ認定
  * 大学内ものづくりコンテスト 大学奨励賞＆協賛企業賞受賞
* UIST2020 [Poster発表](https://dl.acm.org/doi/10.1145/3379350.3416171)
* クマ財団 クリエイター奨学金 採択([4期](https://kuma-foundation.org/student/shoki-kishida/))
* 過去の職歴は[こちら](/workexp/)

## 趣味

### 電子工作

手を動かすの楽しいですよね。

### お絵かき

思い描いているものを実現できるっていいですよね。

### 写真

美しさってなんなのでしょうね。

### CG

想像を実世界で確認・共有可能なものにするという点では絵も工作もCGもよく似ています．

## [業績](/achievements)

<div class="post-list">
  {% for post in site.posts %} 
      {% if post.achievements != null %}
      {% if post.url_force == null %}
      <ul>
          <li class="wow fadeIn" data-wow-duration="1.5s"
              style="background-image: url( {{post.achieve_image}} ); ">
              <a class="zoombtn" href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
              <p>{{ post.excerpt }}</p>
              <p>{{ post.achievements}}</p>
              <a href="{{ site.url }}{{ post.url }}" class="btn zoombtn">Read More</a>
          </li>
      </ul>
      {% else %}
      <ul>
          <li class="wow fadeIn" data-wow-duration="1.5s"
              style="background-image: url( {{post.achieve_image}} ); ">
              <a class="zoombtn" href="{{ post.url_force }}">{{ post.title }}</a>
              <p>{{ post.excerpt }}</p>
              <p>{{ post.achievements}}</p>
              <a href="{{post.url_force }}" class="btn zoombtn" text-align="right">Read More on external
                  link </a>
          </li>
      </ul>

      {% endif %}
      {% endif %}
  {% endfor %}
</div>