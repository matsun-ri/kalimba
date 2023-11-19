# MSX0Stackをカリンバにするプログラム『Kalimba for MSX0』

## Kalimba for MSX0とは
- MSX0って、カリンバに似てませんか？
- 一部で有名なカリンバ（親指ピアノとも）をMSX0で再現するためのプログラムです。
- オールBASICです。

## 画面サンプル
<p>
<img src="/img/kalimba-1.jpg" alt="画面サンプル" width="445" height="299">
</p>

## 実行環境
- すべてのMSX BASICで動作するはずです（が、操作の都合上、MSX0 Stack+QWERTYパネル以外での操作は絶望的です）

## ファイルの説明
- **[bin\kalimba.dsk](https://github.com/matsun-ri/kalimba/raw/main/bin/kalimba.dsk)** ディスクイメージ
- ディスクイメージ内のファイル
  - **KALIMBA.BAS** プログラム本体
  - **AUTOEXEC.BAS** KALIMBA.BASを自動実行するためのプログラム。

## 実行方法
1. MSX0のmicroSDカードのDSKフォルダ内に[bin\kalimba.dsk](https://github.com/matsun-ri/kalimba/raw/main/bin/kalimba.dsk)を置きます。
2. MSX0のSetup Utilityにて、上記ディスクイメージを選択します。
3. MSX0をリセットします。
4. CAPSがOFFの状態で、画面に表示されているキーを押すと音色が流れます。最大3和音まで鳴ります。
5. ESCキーで終了します。

## あとがき
- 本当は、Pascalでキーマトリクススキャンでキーを拾って無遅延で音を鳴らすつもりでした。ごめんなさい。
