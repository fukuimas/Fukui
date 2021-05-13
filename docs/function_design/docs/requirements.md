# ハードウェア要件とソフトウェア要件

本章では、本デバイスのハードウェア及びソフトウェアの要件を明らかにする。

## ハードウェア要件

　以下に、本デバイスのハードウェア要件を示す。

|**カテゴリ**                |**項目**            |**仕様**                                                                                                                     |
|:--|:--|:--|
|マイク                      |個数                |2個                                                                                                                          |
|                            |集音帯域            |100-20000Hzの帯域が確保されていること<br>(素子単体)<br>サンプリングレートは48kHz                                                                                        |
|                            |SN比                |実際に回路に組み込んだ時に、スペックシートに示された通りの性能が出ていること                                                         |
|スピーカ                    |個数                |2個                                                                                                                          |
|                            |再生帯域            |100-20,000(14,000)Hzの帯域が確保されていること(素子単体)<br>サンプリングレートは48kHz|
|アンプ                      |電力                |MAX：10W（スピーカ1個当たり5W × 2個）                                                                                                          |
|                            |最大音量            |85dBSPL@50cm,45度                                                                                                            |
|DSP                         |演算量              |200MIPS 以上                                                                                                                  |
|                            |メモリ              |RAM 200kByte 以上ROM 256kByte 以上                                                                                           |
|                            |開発環境等          |C言語での開発が可能であり、NTTテクノクロスにて開発環境及び評価治具が調達できる、もしくは提供可能であること                              |
|4極ミニジャック             |極性                |CTIA規格に準ずる                                                                                                             |
|USB                         |プロトコル          |USB2.0準拠Windows/MacOSの標準ドライバ対応                                                                                    |
|                            |形状                |TypeC                                                                                                                        |
|                            |対応OS              |Windows, MacOS, iOS, iPadOS, Android                                                                                                 |
|Bluetooth                   |プロトコル          |HFP1.6以上（Wide band対応）<br>A2DP（SBC, AAC対応）<br>AVRCP（ボリューム操作）<br>（自動切換えできること）                           |
|                            |電波強度            |Class2に準拠                                                                                                                 |
|内臓リチウムイオンバッテリー|容量                |8時間利用可能な容量であること                                                                                                  |
|                            |USB給電             |バッテリー充電 充電時間2時間以内                                                                          |
|対応規格                    |                    |VCCI ClassB<br>RoHS<br>PSE<br>技適（電波）                                                                                              |
|筐体                        |カラーバリエーション|1色ラインナップ                                                                                                              |
|                            |サイズ              |120mmⅹ120mmⅹ30mm程度                                                                                                       |
|                            |その他              |平置き（主に通話時）、58°立てかけ（主に音楽再生時）できる                                                                         |
|ソフトアップデート          |                    |USB経由でソフトウェアのアップデートが可能                                                                                    |
[ハードウェア要件]



## ソフトウェア要件
### 対応OS
　以下に本デバイスの利用対象となるOSを示す。

* オーディオに対応するOS
以下のOSを対象とする。
ただし、ドライバインストール不要であることを条件とする。

  * Windows 8.1
  * Windows 10（32bit）v1909以降
    * Home/Pro/Education / Pro Education/Enterprise/Enterprise LTSB
  * Windows 10（64bit）v1909以降
    * Home/Pro/Education / Pro Education/Enterprise/Enterprise LTSB
  * Mac OS 
    * v11 / v10.15 / v10.14
  * iOS 
    * 14 / 13 / 12
  * iPadOS
    * 14 / 13 / 12
  * Android OS
    * 11.x / 10.x / 9.x / 8.x / 7.x


* ファームウェアアップデート対応OS
以下のOSを対象とする。
ただし、ドライバインストール不要であることを条件とする。

  * Windows 10（32bit）v1909以降
    * Home/Pro/Education　Pro Education/Enterprise/Enterprise LTSB
  * Windows 10（64bit）v1909以降
    * Home/Pro/Education　Pro Education/Enterprise/Enterprise LTSB
  * Mac OS 
    * v11 / v10.15 / v10.14
