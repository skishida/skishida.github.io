---
layout: post
project: yes
title: EnOceanを用いたフリーマガジンのラック内在庫量の把握
excerpt: 電源レスで重量データを飛ばすセンサノードの開発
achievements: "ROHM OPEN HACK CHALLENGE 2017 特別賞受賞"
tags: [Hardware, IoT, EnOcean, Award, "8051", uVision]
achieve_image: /assets/img/2017/rohc_award.jpg
feature: /assets/img/2017/rohc_cj.jpg
comments: true
---
# EnOceanを用いたフリーマガジンのラック内在庫量の把握

フリーマガジンのラック内在庫量をEnOceanに重さセンサを接続することで可視化するというソリューションの提案

### Gallery


{% capture images %}
 /assets/img/2017/rohc_award.jpg
 /assets/img/2017/rohc_cj.jpg
{% endcapture %}
{% include gallery images=images  cols=2%}

※画像一部ローム株式会社様ご提供

### Description

現在、駅や店舗に設置されているフリーマガジンのホスティングラックは、定期的に配達員が補充を行う等の手間をかけて在庫量･流通量の把握を行っている。これにより、マーケティングにより活用可能な｢誰が｣や｢何時頃｣｢ラックのどの位置で｣といった詳細な情報を取得できない、配布量の厳密なコントロールができない等の問題が存在する。

今回提案するシステムは、このラックにホストされているペーパーの量を十分時間単位程度で監視し、遠隔でそのデータを収集するものである。本システムは各ラックのマガジン量を監視するセンサノードと、そのデータを無線で受信しサーバーへ転送するゲートウェイから構成される。

センサノードは｢誰が｣といった高度な情報を処理しない代わりに、外部電源等配線不要で動作する。本システムを利用することで、適切な配本設計や設置場所に沿ったコンテンツを提供可能となる。将来的には天候や時事ニュースと掛け合わせたビッグデータ解析という形で利用可能なデータを蓄積することを狙いとする。

ラックは店舗や施設に依頼して設置していただく形式が多いため、なるべくシステムが大掛かりにならないことを目標としている。具体的には、｢配線や電源を考えなくて良い｣｢予めセットアップされているものを設置すれば終わり｣｢定期的なメンテナンスは不要｣というものを理想として機能の実現を考えた。

例えば電源をラックまで延長すればカメラ等の設置が可能となり、画像処理等の高度な処理が可能ではあるが、設置場所に電源があるとは限らない上、ラックそのものの収納時等の手間も増える。

今回、EnOceanという環境発電でセンサデータを無線送信可能なデバイスを利用し、またこのシステムと同時に利用できる低消費電力な回路を考案することで、｢配線不要で在庫量を把握できるシステム｣というより実用的な設計を目指した。

### Update

現在の仕様は以下の通り。

* 展示用に1秒間隔で送信する必要があるため外部電源は必須である
* 10分毎送信ならボタン電池でも2年前後は持つ計算である
* 構想中の設計では10分毎送信なら電池交換不要になる見込みがある

### Activity

* ROHM OPEN HACK CHALLENGE 2017 特別賞受賞
* CEATEC JAPAN 2017 ロームブースで展示
* 平成28年度 電気通信大学 学生表彰 受賞

### Technique

* [EnOcean](https://www.enocean.com/jp/) STM431J, USB400J, etc
  * 8051, Keil uVision
* load cell

### Related Links

* [ROHM OPEN HACK CHALLENGE 2017](http://open.rohm.com/rohmhack/) 
* [白熱のROHM OPEN HACK CHALLENGE 2017 最終審査イベントレポート - ROHM OPEN SOLUTIONS](http://open.rohm.com/jp/events/171005_article)
* [CEATEC 2017 - センサと無線のコラボで新たなソリューションを創出するローム - エキサイトニュース(3/3) ](http://www.excite.co.jp/News/it_biz/20171003/Cobs_1676261.html)
