IM@S CG Helper(仮)
======================
アイドルマスターシンデレラガールズを多少快適にするスクリプト。

髭山髭人氏の無課金タイマーCGをAndroidでも使いたかったのが事の始まりです。  
ソースコードの流用はしていませんが、機能やUI等は影響を受けています。  
シンプルという名の劣化版。

念のためですが、本スクリプトは髭山髭人氏とは一切関係ありませんので、  
本スクリプトに関する問い合わせ等は絶対に行わないでください。


最近の更新 (2013.10.28.121)
----------------
* アイドル一覧の表示が崩れる場合があった問題を修正
* アイドル画像表示機能を追加  
  アイドル画像をクリックすると、アイドル画像(大)を表示します。  
  SR以上のアイドルの場合、画像上部の切り替えリンクで枠の有無を切り替え出来ます。  
* ローディングキャラ表示機能を追加  
  肩書画像をクリックすると、ローディングキャラを表示します。  
  (ローディングキャラがいない場合は当然ならがら表示出来ません)
* 全体的に少し見直し


動作環境
----------------
Adobe Flash Player をインストールしていない、又は未対応の場合、  
一部機能が正常に動作しない可能性があります。

### Windows PC ###
* Google Chrome

### Android (1.6以上) ###
* Angel Browser

### Android (2.1以上) ###
* Sleipnir Mobile

### Android (4.0.3以上) ###
* Angel Browser
* Sleipnir Mobile
* Habit Browser
* Habit Browser classic

---------------
### ※Androidの動作確認は以下の機器で確認しています。 ###
* au Xperia acro IS11S
* docomo Xperia SX SO-05D
* Google Nexus 7


動作環境？ （未確認）
----------------
### iOS ###
有料アプリですが、WebHub Browserというブラウザでユーザースクリプトが実行可能な様です。（動作しなくても責任は一切負いません）  
※ 動作しないとの報告を頂きました。実機が無いため現状は非対応となります。

### その他 ###
上記以外の環境でも、アイドルマスターシンデレラガールズをプレイ可能で、かつユーザースクリプトが使用出来るブラウザであれば動作する可能性はあります。


インストール方法
----------------
### Windows PC (Google Chrome) ###
1. imascghelpser.user.js をPCの任意の場所に保存する。
2. Google Chromeを起動する。
3. [メニュー > ツール > 拡張機能] を選択する。
4. 拡張機能の画面上に、保存したimascghelper.user.jsをドラッグ&ドロップする。

### Android 1.6以上 ([Angel Browser](https://play.google.com/store/apps/details?id=net.adgjm.angel))

1. Angel Browserを起動する。
2. このページを開く。
3. mobile用のページになっている場合は、ページ下部の「Desktop version」を押す。
4. 「imascghelper.user.js」のリンクを押す。  
   （ファイル名に注意）
5. 「Raw」ボタンを押す。
6. ダイアログが表示されるので「OK」を押す。

### Android 2.1以上 ([Sleipnir Mobile](https://play.google.com/store/apps/details?id=jp.co.fenrir.android.sleipnir))

スクリプト（エクステンション）インストール後、一度アプリケーションを終了しないと、ページ読み込みに時間がかかる様です。

1. Sleipnir Mobileを起動する。
2. このページを開く。
3. mobile用のページになっている場合は、ページ下部の「Desktop version」を押す。
4. 「imascghelper.slex.js」のリンクを押す。  
   （ファイル名に注意）
5. 「Raw」ボタンを押す。
6. ダイアログが表示されるので「インストール」を押す。
7. [メニュー > その他 > アプリケーションを終了]を押す。
8. ダイアログが表示されるので「OK」を押す。

### Android 4.0.3以上 ([Habit Browser](https://play.google.com/store/apps/details?id=jp.ddo.pigsty.HabitBrowser) / [Habit Browser classic](https://play.google.com/store/apps/details?id=jp.ddo.pigsty.Habit_Browser)) ###
無印の方が新しいのですが、2013/10/16時点ではまだ不安定な感じです。  
比較的安定しているclassicを使用する方が個人的にはお勧めです。

1. Habit Browserを起動する。
2. このページを開く。
3. mobile用のページになっている場合は、ページ下部の「Desktop version」を押す。
4. 「imascghelper.user.js」のリンクを押す。  
   （ファイル名に注意）
5. 「Raw」ボタンがあるので、長押してメニューを開く。
6. 「名前をつけて保存」を押し、任意のディレクトリに保存する。  
   （ファイル名はimascghelper.user.jsで保存）
7. [メニュー > 設定 > 詳細 > ユーザースクリプト > 新規スクリプト(＋) > ファイルから追加する] を選択する。
8. 先程保存したimascghelper.user.jsを選択する。

### その他ブラウザ ###
ブラウザによって操作は異なりますが、imascghelper.user.jsをユーザースクリプトとして設定して下さい。


機能概要
----------------
* 標準メニュー内のバナー非表示 :  
  標準メニュー内にあるイベントバナーを非表示にする。

* カスタムメニューを追加 :  
  標準メニューの下に任意のメニューを追加で表示する。

* 贈り物画面の初期状態をチェックなしにする :  
  そのまま。誤受け取り防止。

* ポイント振り分けページでフィルタ機能 :  
  メニュー下部に任意の追加メニューを表示する。

* 所属アイドル一覧画面にリーダー設定用のボタンを追加 :  
  所属アイドル一覧画面にの各アイドルに「リーダーにする」ボタンを表示する。

* 所属アイドル一覧、編成画面に編成リンクを追加 :  
  所属アイドル一覧、編成画面上部にフロントメンバー編成用のリンクを表示する。

* 各種アイドル一覧画面に追加情報を表示 :  
  各発揮値のコスト比を表示、特技レベルを☆で表示する。

* 各種アイドル一覧画面にアイドル相場リンクを追加 :  
  追加情報の領域をクリックすると、アイドル相場のページへジャンプする。

* 所属アイドル詳細画面に親愛度MAX演出ボタンを追加 :  
  所属アイドル詳細画面でアイドルの親愛度がMAXの場合、親愛度MAX演出ボタンを表示する。

* 一部画面で移籍リンクを非表示 :  
  所属アイドル詳細画面とかの移籍ボタンを非表示にする。

* 女子寮の一括で入寮させる/呼びボタンを画面上部に追加 :  
  そのまま。

* LIVEバトル確認画面に操作リンクを追加 :  
  LIVEバトル確認画面に対戦相手への応援リンクと閉じる。

* LIVEバトル時の消費攻コストの上限値設定  
  LIVEバトル準備画面で設定したコスト以上の攻コストが使用される場合、LIVEバトルのボタンを非表示にする。

* LIVEバトル画面に操作リンクを追加 :  
  LIVEバトル時のFlash画面に道場や戻るリンクを追加する。

* レッスン画面に操作リンクを追加 :  
  レッスン時のFlash画面に所属アイドル一覧や戻るリンクを追加する。

* お仕事画面に経験値計算情報を表示 :  
  お仕事画面に次のレベルアップまでに必要なアイテムや時間を表示する。  
  アイテムをクリックすると、そのアイテムを計算に含めたり除外する事が可能。  

* イベントランキング画面にリンクを追加 :  
  各種ボーダー用のリンクを追加する。

* アイドル画像表示機能を追加  
  アイドル画像をクリックすると、アイドル画像(大)を表示します。  
  SR以上のアイドルの場合、画像上部の切り替えリンクで枠の有無を切り替え出来ます。  

* ローディングキャラ表示機能を追加  
  肩書画像をクリックすると、ローディングキャラを表示します。  
  (ローディングキャラがいない場合は当然ならがら表示出来ません)

* 一部機能について、設定画面を追加 :  
  メニュー > 設定画面に「IM@S CG Helper(仮)設定」リンクを追加。  
  カスタムメニュー等の一部機能の設定はここから行える。


既知の問題
----------------
* お仕事時の経験値計算機能で、まれに値が取得出来ない。  
  → 画面を更新すると正常に表示される。現状は仕様となります。
* 所属アイドル一覧画面に追加されたリーダー設定用のボタンを押した時に、そのアイドルがフロントメンバーに設定されているとエラーになる。  
  → 現状は仕様となります。
* Android (Sleipnir Mobile）で、タブを閉じるリンクやボタンを押してもタブが閉じない。


注意事項
----------------
* 本スクリプトでは、画面にリンクを追加したり非表示したりするだけのもので、いわゆるマクロやbotの類ではありませんが、全て自己責任の元で利用してください。  
* 本スクリプトを使用したことにより生じたいかなる損害、不利益等に対してはいかなる責任も負いません。


謝辞
----------------
スクリプト内で、以下のサイトを利用させて頂いてます。

* カスタムメニューアイコン： http://fortawesome.github.com/Font-Awesome/
* 道場リンク初期値： http://saasan.github.io/mobamas-dojo/lv.html
* アイドル相場リンク： http://mobile-trade.jp/fun/idolmaster/bazaar.php
