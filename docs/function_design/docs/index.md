---
title: PSZ ハンズフリーデバイス 機能仕様書
author: Copyright &copy; 2021 NTT TechnoCross Corporation. All rights reserved.
---

# はじめに
## 背景
昨今の新型コロナの影響により、リモートワーク（在宅勤務）が急速に普及、感染症終息後も働き方の一つとして定着する事が予想されており、リモートミーティングの時間が増え、快適なリモートコミュニケーション環境のニーズが高まっている。
そこで、リモートワークのニーズに対応したハンズフリーデバイスを製品化することで、快適・効果的な在宅勤務環境を提供する事が狙いである。

## 課題
前述の通り、昨今のリモートワーク普及により、多くのハンズフリーデバイスがリリースされており、特に小型なデバイスについては価格帯、デザイン、音響的な性能、どれも似たような仕様で差別化が出来ていない。
また、家庭環境等の生活音や環境音が入り込んでしまう事による、プライバシーの侵害や通話品質の低下もハンズフリーデバイス課題の1つである。

## 解決する課題
本デバイスは前述の課題を以下のように解消する。

* 360度広範囲集音以外にエリア限定集音やパーソナルサウンドゾーン技術によるスピーカ音漏れ抑制などを実現し、在宅・パーソナルに特化


* 従来の定常/非定常雑音抑圧の他、キーボード音除去技術を用いた環境音の除去


* 通話と音楽再生の共用など、従来にない使い方を提案し、他社競合品との差別化を図る

![課題解消のコンセプト](img/problem_solving_concept.png)


## 本文書の対象範囲
本文書は製品化を目指すPSZハンズフリーデバイスを取り扱うものとし、デバイスが実現する機能の仕様について取り扱うものとする。

## 本文書で用いる用語について


|用語      |内容                                         |
|:--|:--|
|本デバイス|製品化対象であるPSZハンズフリーデバイスを指す|
|接続先    |USB接続、Bluetooth接続のホスト側を指す       |
|音響信号処理|NTTが開発するソフトウェアの処理の総称|
|指向性制御|マイクの集音、スピーカの再生の指向性を音響信号処理で形成する技術|
|パーソナルサウンドゾーン技術| スピーカを複数個用いてスピーカ再生音の聞こえる特定の範囲に限定する技術                          |
|360度広範囲集音|指向性制御技術で形成するマイクの指向性、全指向性|
|エリア限定集音|指向性制御技術で形成するマイクのマイクの指向性<br>単一指向性の様に特定の方向のみの音を集音する|
|定常/非定常雑音抑圧|環境ノイズやスピーカの再生音等のノイズ音を抑圧する技術|
|キーボード音除去技術|キーボードタイピング音のような、突発的な音を検知し、検知した音を抑圧する技術|
|EQ|イコライザ<br>音声信号の周波数特性を調整する|
|動作モード|利用用途に合わせたモードの総称<br>音楽モード<br>360度通話モード<br>パーソナル通話モード<br>各モードの仕様については機能詳細で明らかにする|
|DSP|本仕様書では音響信号処理が実装される、DSPを指す|
|フレームワーク|本仕様書では音響信号処理が実装されるフレームワークを指す|
[本文書で用いる用語]

## 本文書の対象ユーザー
本文書は、本デバイスの開発、筐体・基板・ソフトウェア設計・製造・開発管理を行う担当者を対象とする。


|ユーザー      |担当領域                               |
|:--|:--|
|MD研          |音響信号処理開発                       |
|NTT－TX       |                                       |
|東北パイオニア|ハードウェア設計・製造                 |
|３NOD         |DSPソフトウェア(音響信号処理を除く)開発|
[対象ユーザー]
