# penpa-editor
万能ペンシルパズルエディタ。
あらゆるペンシルパズルを作図するためのソフトです。ソフト上で問題を解くこともできます。

画像保存とテキスト保存が行えます。「アドレス出力」で出力されたテキストをアドレスバーに入力することでロードされます。

ブラウザで異なりますが、「Ctrl」＋「R」、「Ctrl」＋「F5」、「Shift」＋「F5」などでキャッシュを使わないページの更新ができます。

## 対応ブラウザ
* Google Chrome
* Safari
* Firefox
* Microsoft Edge

## ショートカットキー
* Ctrl + z : 一手戻る
* Ctrl + y : 一手進む
* Ctrl + d : 盤面を複製
* Ctrl + space : 数字と記号を同時に削除
* Shift + space : 半角スペースを入力
* F2 : 問題モード
* F3 : 解答モード

## Tips
* 数字：パネルの「1」タブでBackSpace、「A」タブで半角スペースが入力可能。大・中・小・長文ではShift + spaceでも半角スペースを入力可能。
* 数字>矢印 : マスをドラッグした方向に矢印が入力。
* 記号：数字キーの1-9,0によって入力。パネルをONにすると入力できる記号の一覧を表示、左上から1,2,...と対応。パネルの入力方法は、パネル記号にカーソルを合わせ、盤面をクリック。二回クリックで消去。
* 記号>図形>十字など、いくつかの記号はonoffの入力形式。パネルをクリックすると直接入力される。特殊例：デジタル（枠）で同じキーを二回押せば枠だけ表示される。
* 特殊：入力した記号の１マス目をクリックすることで削除。
* 特殊：入力中に通った道を戻ることで先端の位置を一手前に戻せる。

## 現在の機能
### 黒マス
* 黒マス。スタイルで色を選択。（ぬりかべ、アイスバーン、シャカシャカ etc.）
* 濃灰のみ、二回クリックすると緑マスに。
* 隠灰は、灰色の文字や記号に重ねて隠す時に用いる。
* 右クリックで緑マスを入力。
### 線
* 通常：マスの中央をタテヨコに結ぶ線。（ましゅ、橋をかけろ、回文数独etc.）
* 対角線：マスの中央をナナメに結ぶ線。（Zigzag etc.)
* 自由線：任意のマス同士を結ぶ線。（ナイトツアー etc.)
* 中線：マスの中央と辺の中央を結ぶ線。
* 補助x：辺に置く補助用のバツ記号。
* スタイルで線の色や太さを選択。
### 辺
* 通常：マスの頂点をタテヨコに結ぶ線。（へやわけ、スリザーリンクetc.）
* 対角線：マスの頂点をナナメに結ぶ線。（対角線数独etc.）
* 自由線：任意のマスの頂点同士を結ぶ線。（鋭直鈍ループetc.）
* 補助x：辺に置く補助用のバツ記号。
* 枠消：盤面の枠線の削除。
* スタイルで線の色や太さを選択。
### 壁
* マスの内部にタテヨコで描かれる線。（縦横さん、スラローム etc.）
* スタイルで線の色や太さを選択。
### 数字
* 通常：数字、アルファベット、一部の記号文字をキーボードから入力。パネルを使うと記号のほか、TextタブからUnicode文字列の入力が可能。
* 矢印：矢印付き文字。（ヤジリン、CastleWall etc.）
* Tapa：Tapa用文字。4文字まで。
* 1/4：四隅の文字。（カックロ、ヘヤジリン、キラー数独 etc.）
* ｺﾝﾊﾟ：コンパス用文字。上下左右によった、小さい数字を入力することが可能。
* 大、中、小：小さいサイズの数字。
* 長文：長い文章。シークワーズなどのリストが作成可能。
* 候補：数独など、ラテンスクエア用の候補数字。1-9に対応。onoff入力。
* 白丸、黒丸は数字の裏に丸が書かれる。
* 白背景は、数字の裏に白丸を描画。裏の線に隠れて数字が見えにくい時。
* 辺入力をONにすると、文字を辺上・頂点に配置。
### 記号
* 多数の記号。パネルを開くことで入力可能な記号を閲覧可能。〇や□などの図形、不等号、デジタル数字、その他パズル固有の記号など。
* スタイルで、図形を線の手前側に置くか、奥側に置くかを選択可能。（ましゅの〇は線の奥、ごきげんななめの〇は線の手前）
* 辺入力をONにすると、文字を辺上・頂点に配置。
### 特殊
* 複数マスにまたがる特殊記号。（アロー数独、サーモ数独、移動用矢印、四角のエリア、多角形の塗りつぶし。）
* 入力した最初のマスをクリックすると消去。
* 多角形の塗りつぶし。クリックした順番に頂点が選ばれる。最後にクリックした頂点か、最初にクリックした頂点をもう一度クリックすると選択終了。消去は戻ボタンのみ。
### 枠
* 複数のマスを囲む線。（キラー数独 etc.）
* スタイルは黒色の点線・黒色の実線・灰色の点線、灰色の実線の４種類。
* 正方形と正六角形で使用可能。
### マス
* 盤面の枠を描くマスをクリックで選択。
### 移動
* 数字、記号をドラッグで移動可能。もともと数字or記号のあるマスには移動不可。
* 全は数字と記号を両方動かす。数字、記号のどちらか一方を動かす設定も可能。
### 複合
* 複数の入力方法を同時に使う機能。
* 複合モード一覧
1. 黒・点　　　　黒マス、点をドラッグ入力
2. 白丸黒丸　　　白丸、黒丸をドラッグ入力
3. シャカシャカ　三角形を引っ張り入力
4. 線・ｘ　　　　線と補助x（キャッスルウォール）
5. 線・OX　　　  線とマスに〇×（カントリーロード）
6. 辺・x・内外　辺と、補助ｘと、内外の塗り分け黄色と緑。（スリリン、Cave)
7. ヤジリン　　　黒マス・点と、線
8. 橋をかけろ　　線をもう一度引くと二重線に
9. 辺・補助線　　辺と、マスの連結を表す補助線
10. バトルシップ　戦艦。二回クリックすると周りの船の状態に応じて形が変化。
11. スターバトル　星と×
12. テント　　　　テントと点、辺の補助ｘ、テントと木を結ぶ線。
13. 矢印フリック　矢印をフリック入力。8方向。
14. 数字フリック　数字をフリック入力。左上から右下へ123456789。
15. 英字フリック　アルファベットをフリック入力。左上から右下へABCDEFGH-。右下で-を入力。

### 変形盤面
* 「新規作成・枠変更」メニューから正方形、正六角形、正三角形、ピラミッド、立方体を選択可能。正方形以外では機能制限あり。
* 「マス」モードで盤面形状を調整。「回転・移動」メニューから、「盤面を中央に移動」、「画面サイズを盤面に合わせる」ボタンで盤面の余白を調整。
### グリッド
* 「新規作成・枠変更」メニューから盤面の枠線を変更可能。
* グリッド：枠線の種類
* 格子点：頂点に点を置くかどうか
* 外枠：盤面の周囲に太線を書くかどうか
* 余白：盤面のグリッドの外側に数字を置く場合などに使用。（ビルディングパズルetc.）
* 「作成」ボタンは盤面をリセット。「枠変更」ボタンは盤面をリセットしない代わりに、表示サイズ以下の項目のみ更新。
### 回転・移動
* 「回転・移動」メニューから盤面の回転・反転が可能。正方形、ピラミッドでは90°回転。正六角形、正三角形、立方体盤面では30°回転。
*　「盤面を中央に移動」、「画面サイズを盤面に合わせる」ボタンで盤面の余白を調整。
### 画像保存
* 画質：高にすると画質は良くなるが、画像サイズが大きくなるので用途に応じて
### 解答判定
* 「アドレス」から、「拡張出力」で、出力時の解答盤面に対応した解答チェックつきのアドレスを出力。一覧にのっている一部の記号のみ判定するが、複雑な仕様のため省略。
### 英語
* "English"で英語モードに。ブラウザの言語が英語の場合、最初から英語モードで起動。


## 履歴
* 2023/03/01 ver3.0.1 変形盤面を追加
* 2022/08/03 ver3.0.0 Penpa＋v2.26.21を翻訳
* 2021/07/12 ver2.26 記号バトルシップ追加
* 2021/01/23 ver2.25 記号左右三角,Darts追加
* 2020/09/10 ver2.24 パネルにTextタブを追加。Androidでのバグ修正。記号の表記を修正。
* 2020/09/04 ver2.23　bug fix.　サイズ調整。盤面サイズ上限引き上げ。
* 2020/09/03 ver2.22　bug fix.　戻ボタンの暴走、正解判定時に意図しない黒マスなどが入力されてしまう問題、Ipad対応など。
* 2020/09/01 ver2.21 「画面サイズを盤面に合わせる」など、余白調整の機能を修正。
* 2020/09/01 ver2.20 見た目を調整。青を追加。長文の文字数制限を50に。
* 2020/08/01 ver2.19 英語対応。出題用アドレスで、解答モードでのボタンの選択状態を記録するように変更。
* 2020/07/01 ver2.18 記号追加
* 2020/06/28 ver2.17 記号追加、半角スペースをShift + spaceで入力可能に。
* 2020/06/24 ver2.16 記号追加
* 2020/06/12 ver2.15 記号追加
* 2020/01/05 ver2.12 マウス判定を調整。
* 2019/12/21 ver2.11 複合モードなどを実装。
* 2019/12/07 ver2.10 別アドレスで開発を行っていたver.2を旧アドレスと統合。
* 2019/09/07 ver2.00 変形盤面対応など
* 2019/08/16 ver1.05 Microsoft Edge対応
* 2019/08/04 ver1.04 白フチの仕様変更、記号の入力方法を変更
* 2019/07/29 ver1.03 点線の描画を修正など
* 2019/07/18 ver1.02 iPhone対応
* 2019/07/14 ver1.01
* 2019/07/13 ver1.00
* 2019/07/07 β版

## 免責事項
Copyright (c) 2019 opt-pan
Released under the MIT license
https://github.com/opt-pan/penpa-edit/edit/master/MIT-LICENSE.txt
