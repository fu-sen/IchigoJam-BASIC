## IchigoJam BASIC コマンド一覧
IchigoJam BASIC command reference (Japanese)

IchigoJam BASIC で使用できる命令を一覧しています。

Download ZIP でファイル一覧をダウンロードできます。\
GitHub・Git を使っている場合は Clone を使っても良いでしょう。

RAW で参照した場合、またファイルをダウンロードした場合\
.txt ファイルは文字コード UTF-8、改行コード CR+LF になります。\
Windows ではメモ帳を使用する事が可能です。

* IchigoJam (公式) https://ichigojam.net/
* イチゴジャム レシピ (公開元) https://15jamrecipe.jimdofree.com/

### PDF 版

西澤 眞人さんが PDF 化した IchigoJam+PanCakeコマンドリファレンス を\
Facebook グループ IchigoJam-FAN 内で公開しています。\
紙面で一覧したい場合はこちらを印刷し、ご利用下さい。

* IchigoJam BASIC 1.1.0 beta / PanCake 1.0<br />https://www.facebook.com/groups/ichigojam/permalink/626383150834775/<br />
* IchigoJam BASIC 1.0.2 / PanCake 1.0<br />https://www.facebook.com/groups/ichigojam/permalink/626631844143239/

### MixJuice 版

MixJuice（互換の MicJack）を接続している IchigoJam より\
イチゴジャム レシピ MixJuice コンテンツ 内で\
コマンド一覧を直接参照できます。

https://github.com/fu-sen/15j.run
```
?"MJ GET 15j.run/basic/command/

?"MJ GET 15j.run/basic/command/(コマンド名)
例 ?"MJ GET 15j.run/basic/command/VER
```

また、古籏 一浩さん変換・公開による MixJuice バージョンもあります。

https://www.facebook.com/groups/ichigojam/permalink/718904794915943/

```
?"MJ GET www.openspc2.org/data/m/(コマンド名大文字).txt
例 ?"MJ GET www.openspc2.org/data/m/CLS.txt
```

### English books

Juergen Pintaske has converted this reference to English books.\
You can now learn more about IchigoJam BASIC in English.

- IchigoJam - My Reference (Kindle Edition)\
https://www.amazon.com/dp/B07VRSFPBW/
- IchigoJam - BASIC: My Reference - Preliminary Version\
https://www.amazon.com/dp/1079519238/

These exist in Amazon in different countries.\
Please search: *Juergen Pintaske IchigoJam*

### English version

This IchigoJam BASIC reference has been translated in English.\
translated by Paul Wratt (@paulwratt).

https://github.com/paulwratt/IchigoJam-BASIC-english

### バージョン表記の注意

対応バージョンは上部コマンド名の下に記載しています。\
特にバージョン表記のない「IchigoJam BASIC」などは全バージョン対応です。\
「IchigoJam BASIC RPi 非対応」など「非対応」とある場合は対応していません。

0.9.8 および 0.9.9 は正式リリースがなく、RC 版しか存在しません。\
0.9.8 または 0.9.9 と記載している場合は、それらの RC 版全般を指します。\
また 1.0.0 および 1.1 以降では beta 版を\
まとめて表記している場合があります。

1.1 beta（1.1.0 beta1 を含む）は 1.0.2 beta11 までの追加機能を継承しています。\
そのため、1.1 beta 表記の一部コマンドは 1.0.2 beta11 までで動作するものがあります。\
（...→1.0.2 beta11→1.1.0 beta1→1.1 beta2→1.1 beta3→...\
　1.1 beta 2 でモンゴル版を公開した影響で「.0」を外しています）\
1.0.2 beta12 は 1.0.1 から継承しなおしているため、動作の違いにご注意下さい。\
（1.0.2 beta12 は beta11 までの内容を一部含んでいない機能があります）\
ただし、実際には 1.0.2 は正式リリースされず、1.1.1 が正式リリースされています。

IchigoJam BASIC RPi はバージョンとハードウェア仕様の違いによる動作有無があり、\
別途対応バージョンを上部に表記しています。\
IchigoJam BASIC RPi の正式版バージョン表記は\
オリジナル版の IchigoJam BASIC とずれがあります。\
IchigoJam BASIC 1.2.0RPi～1.2.4RPi は IchigoJam BASIC 1.2.3 ベース、\
IchigoJam BASIC 1.2.5RPi～1.2.6RPi は IchigoJam BASIC 1.2b56・1.2b57 IoT 相当である事にご注意下さい。

IchigoJam PC は独自のバージョン表記になっているため、別途対応バージョンを上部に表記しています。\
IchigoJam PC 0.1 beta 1～0.1 beta 12 は IchigoJam BASIC 1.1 がベースですので、\
基本的に 1.1 の仕様を継承します。

IchigoJam BIG は通常の IchigoJam BASIC 1.2.0 ベースです。\
IchigoJam BIG で動作が異なる場合は記載を行っていますが、\
記載がない場合は通常の IchigoJam と同じ動作になります。\
1.2.2 より VIDEO コマンドで同等の表示に対応しています。

IchigoJam web は最新ベータ版を反映しています。?VER() で確認できます。\
Windows および macOS で動作する Ichigojam ap は配布バージョン連動です。\
これらは IchigoJam BASIC と共通のため、特に考慮していませんが、\
パソコン動作による入出力非対応、本体ボタンなしなどの制限があります。

IchigoCake BASIC は PanCake の機能が拡張されています。\
PanCake コマンド一覧もご参照下さい。

https://github.com/fu-sen/PanCake-COMMAND

### ライセンス

この文章は CC BY で公式に公開されている「IchigoJam BASIC リファレンス」、\
および「IchigoJam BASIC RPi ドキュメント」、\
Facebook グループ「IchigoJam-FAN」などの情報を元に\
志賀 慶一 (ふうせん Fu-sen.) が独自に文章化しているものです。

* IchigoJam BASIC リファレンス: CC BY https://ichigojam.net/ \
オンライン https://fukuno.jig.jp/app/csv/ichigojam-cmd.html \
ver 1.4 https://ichigojam.net/IchigoJam-1.4.html \
ver 1.3 https://ichigojam.net/IchigoJam-1.3.html \
ver 1.2 https://ichigojam.net/IchigoJam-1.2.html \
ver 1.1 https://ichigojam.net/IchigoJam-1.1.html \
ver 1.0.1 https://ichigojam.net/IchigoJam-1.0.1.html \
ver 0.9.9 https://ichigojam.net/IchigoJam-0.9.9.html \
ver 0.9.7 (PDF) https://ichigojam.net/IchigoJam-BASIC-reference.pdf

* IchigoJam BASIC RPi ドキュメント<br />https://ichigojam.github.io/RPi/index_ja.html

* Facebook グループ IchigoJam-FAN (Japanese)<br />https://www.facebook.com/groups/ichigojam/
* Facebook group IchigoJam-FAN@en (English)<br />https://www.facebook.com/groups/ichigojamfan/

Maked by 志賀 慶一 (ふうせん Fu-sen.) | Keiichi SHIGA ( BALLOON a.k.a. Fu-sen. ), 2015-2019.

<a rel="license" href="https://creativecommons.org/licenses/by/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://licensebuttons.net/l/by/4.0/88x31.png" /></a>

この 文章 は <a rel="license" href="https://creativecommons.org/licenses/by/4.0/">クリエイティブ・コモンズ 表示 4.0 国際</a> (CC BY 4.0) ライセンスで提供しています。

[IchigoJam](https://ichigojam.net/) は [株式会社jig.jp](https://jig.jp/) の登録商標です。
