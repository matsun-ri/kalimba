# MSX0Stackをカリンバ（もどき）にするプログラム『Kalimba for MSX0』

## Kalimba for MSX0とは
- MSX0 Stack+QWERTYパネルって、カリンバに似てませんか？
- （以下、『MSX0 Stack+QWERTYパネル』を『MSX0』と略します）
- オルゴールのような音色の癒し系楽器・カリンバ（親指ピアノとも）をMSX0で再現するためのプログラムです。
- オールBASICです。

## 画面サンプル
<p>
<img src="/img/kalimba-1.jpg" alt="画面サンプル" width="445" height="299">
</p>

## 実行環境
- すべてのMSX BASICで動作するはずです（が、操作の都合上、MSX0 Stack+QWERTYパネル以外での操作は絶望的です）

## ファイルの説明
- **[bin/KALIMBA.dsk](https://github.com/matsun-ri/kalimba/raw/main/bin/KALIMBA.dsk)** ディスクイメージ
- ディスクイメージ内のファイル
  - **KALIMBA.BAS** プログラム本体
  - **AUTOEXEC.BAS** KALIMBA.BASを自動実行するためのプログラム。

## 実行方法
1. MSX0のmicroSDカードのDSKフォルダ内に[bin/KALIMBA.dsk](https://github.com/matsun-ri/kalimba/raw/main/bin/KALIMBA.dsk)を置きます。
2. MSX0のSetup Utilityにて、上記ディスクイメージを選択します。
3. MSX0をリセットします。
4. MSX BASICが起動すると、自動的にカリンバが立ち上がります。

## 操作方法
- CAPS・かな共に**OFF**の状態で操作します。
- 画面に表示されているキーを押すと音色が流れます。最大3和音まで鳴ります。
- 本物のカリンバに則って、Hキーがド、以下左、右、左、右の順にレ、ミ、ファ、ソ…と続きます。
- 高いレはBSキー、高いミはAキー、高いファはPキー、高いソはQキーを割り当てています。それ以上の音は割り当てていません。
- ESCキーを押す（MSX0Stackではsym→ESC）と終了します。

## あとがき
- Kalimba for MSX0は12音しか出せません。一般的なカリンバは17音に対応していますので、市販のカリンバ用楽譜を見るときはご注意ください。
- QWERTYパネルのキーピッチは一般的なカリンバよりかなり狭いです。Kalimba for MSX0での演奏に慣れた後で本物のカリンバに触れたら、楽できるかもしれません。ぜひ本物に触れてみてください。
- 本当は、Pascalで書いてDOS上で動き、キーマトリクススキャンでキーを拾って無遅延で音を鳴らすつもりでした。ごめんなさい。
