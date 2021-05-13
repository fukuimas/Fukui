## USBオーディオ接続

  本節ではUSBオーディオ接続の機能仕様を示す。
  PCへUSB接続した際、本デバイスはオーディオデバイスとして認識される。

- パソコンとの接続はWindows及びMac OSの標準ドライバを使用する
- USB Audio Class 1.0を用いる事とする
- USBはバス給電と兼用とする
- モバイル端末もバス給電の兼用を可能とする

USB接続時のデバイス情報を以下に示す。

|種別|情報|
|:--|:--|
|ベンダID||
|プロダクトID||
|デバイスバージョン番号||
|会社名(iManufacturer)||
|製品名(iProduct)||
|デバイス製造番号(iSerialNumber)||
|入力デバイス種別</br>(Audio Control Input Terminal Descriptor)|	Echo-canceling　speakerphone,USB streaming|
|出力デバイス種別<br>(Audio Control Output Terminal Descriptor)|Echo-canceling speakerphone,USB streaming|

[USB接続時のデバイス情報]
