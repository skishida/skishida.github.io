---
layout: post
project: yes
title: 電源基板
excerpt: ブレッドボードで利用できる充電機能付き電源基板
feature: "/assets/img/2017/power.png"
tags: [Hardware, Circuit]
comments: true
---
# 電源基板

ブレッドボードで利用できる充電機能付き電源基板。入力にUSBバスパワーやバッテリを有し、入力切替やバッテリへの充電管理は自動で行われる。

### Gallery

{% capture images %}
  /assets/img/2017/power.png
{% endcapture %}
{% include gallery images=images cols=1 %}

### Description

入力にはUSBバスパワー5Vやリチウムイオンバッテリを設定可能である。この入力は自動でシームレスに切り替わり、ユーザー自身が配線を変更する手間を必要としない。バッテリの他に電源が接続されている場合は自動的に充電が行われる。電源出力には複数の電圧を設定可能である。

ブレッドボードを用いて電子工作を行う際、一般に部品やマイコン等を載せて配線を行う。回路全体に電源を供給するために、外部の電源をブレッドボードに接続したり、マイコン基板に搭載されている定電圧源を利用したりといった方法が取られる。この際、ブレッドボードの形状を活かして電源の配線を行う事が多い。

前者のブレッドボードに直接挿して使う電源は、既存製品として幾つか存在する。6V以上程度の直流電源を接続し、降圧し5Vを供給したり、USBバスパワーなどの5V電源を直に供給したり、あるいは両者において他の電圧も選択できるようにするなどの形式が取られている。これらの既存製品は単なる電源基板としてではなく、ブレッドボードの形状に適した基板サイズと部品配置がなされている。

しかしながら、これら既存の電源の利用においては外部電源との有線接続が基本であり、回路を外部から切り離して動作させる際は新たに乾電池やバッテリを接続し直すなどの回路の変更が必要になる。

ここで、常にバッテリを接続しておくだけで適切に充電管理を行い、回路を独立させたいと考えたときに配線の変更を行う必要がない電源基板を提案する。ユーザーは、例えばUSB電源などを接続しながら回路を設計し、独立動作させようと考えた時はUSBケーブルを取り外すだけで自動的に電源ソースをバッテリに切り替える。この基板を利用することで、ユーザーは配線の変更の手間なく有線接続での開発と独立電源での動作検証を繰り返す事ができる。回路変更という手間は特に回路の経験の浅い電子工作初心者にとっては負荷であり、充電管理も行う本基板は大いにプロトタイピングの助けになると考える。また、本機能はモバイルデバイスによく搭載されている電源管理機能を電子工作に利用しようというアプローチであり、今後ポータビリティが重視されるIoTなどのモバイルデバイスのプロトタイプ開発を行う場合においては特に必要とされると考えている。


### Technique

* LTC3455


### Activity

* UEC ものづくりコンテスト 2017に参加

### Related Links
