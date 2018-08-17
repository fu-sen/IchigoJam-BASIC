## IchigoJam BASIC コマンド一覧
IchigoJam BASIC command reference (Japanese)

IchigoJam BASIC で使用できる命令を一覧しています。

Download ZIP でファイル一覧をダウンロードできます。<br />
GitHub・Git を使っている場合は Clone を使っても良いでしょう。

RAW で参照した場合、またファイルをダウンロードした場合<br />
.txt ファイルは文字コード UTF-8、改行コード CR+LF になります。<br />
（2016年5月14日より文字コードを変更しました）<br />
Windows ではメモ帳を使用する事が可能です。

* IchigoJam (公式) https://ichigojam.net/
* イチゴジャム レシピ (公開元) https://15jamrecipe.jimdo.com/

### PDF 版

西澤 眞人さんが PDF 化した IchigoJam+PanCakeコマンドリファレンス を<br />
Facebook グループ IchigoJam-FAN 内で公開しています。<br />
紙面で一覧したい場合はこちらを印刷し、ご利用下さい。

https://www.facebook.com/groups/ichigojam/626631837476573/

### MixJuice 版

古籏 一浩さんがこの一覧から MixJuice 対応にしたバージョンもあります。

https://www.facebook.com/groups/ichigojam/permalink/718904794915943/<br />
?"MJ GET www.openspc2.org/data/m/(コマンド名大文字).txt<br />
例 ?"MJ GET www.openspc2.org/data/m/ABS.txt

### バージョン表記の注意

対応バージョンは上部コマンド名の下に記載しています。<br />
特にバージョン表記のない「IchigoJam BASIC」などは全バージョン対応です。<br />
「IchigoJam BASIC RPi 非対応」など「非対応」とある場合は対応していません。

0.9.8 および 0.9.9 は正式リリースがなく、RC 版しか存在しません。<br />
0.9.8 または 0.9.9 と記載している場合は、それらの RC 版全般を指します。<br />
また 1.0.0 および 1.1 以降では beta 版を<br />
まとめて表記している場合があります。

1.1 beta（1.1.0 beta1 を含む）は 1.0.2 beta11 までの追加機能を継承しています。<br />
そのため、1.1 beta 表記の一部コマンドは 1.0.2 beta11 までで動作するものがあります。<br />
（...→1.0.2 beta11→1.1.0 beta1→1.1 beta2→1.1 beta3→...<br />
　1.1 beta 2 でモンゴル版を公開した影響で「.0」を外しています）<br />
1.0.2 beta12 は 1.0.1 から継承しなおしているため、動作の違いにご注意下さい。<br />
（1.0.2 beta12 は beta11 までの内容を一部含んでいない機能があります）<br />
ただし、実際には 1.0.2 は正式リリースされず、1.1.1 が正式リリースされています。

IchigoJam BASIC RPi はバージョンとハードウェア仕様の違いによる動作有無があり、<br />
別途対応バージョンを上部に表記しています。<br />
IchigoJam BASIC RPi の正式版バージョン表記は<br />
オリジナル版の IchigoJam BASIC とずれがあります。<br />
IchigoJam BASIC 1.2.0RPi～1.2.4RPi は IchigoJam BASIC 1.2.3 ベース、<br />
IchigoJam BASIC 1.2.5RPi～1.2.6RPi は IchigoJam BASIC 1.2b56・1.2b57 IoT 相当である事にご注意下さい。

IchigoJam PC は独自のバージョン表記になっているため、別途対応バージョンを上部に表記しています。<br />
IchigoJam PC 0.1 beta 1～0.1 beta 12 は IchigoJam BASIC 1.1 がベースですので、<br />
基本的に 1.1 の仕様を継承します。

IchigoJam BIG は通常の IchigoJam BASIC 1.2.0 ベースです。<br />
IchigoJam BIG で動作が異なる場合は記載を行っていますが、<br />
記載がない場合は通常の IchigoJam と同じ動作になります。<br />
1.2.2 より VIDEO コマンドで同等の表示に対応しています。

IchigoJam web は最新ベータ版を反映しています。?VER() で確認できます。<br />
Windows および macOS で動作する Ichigojam ap は配布バージョン連動です。<br />
これらは IchigoJam BASIC と共通のため、特に考慮していませんが、<br />
パソコン動作による入出力非対応、本体ボタンなしなどの制限があります。

### ライセンス

この文章は CC BY で公式に公開されている「IchigoJam BASIC リファレンス」、<br />
および「IchigoJam BASIC RPi ドキュメント」、<br />
Facebook グループ「IchigoJam-FAN」などの情報を元に<br />
志賀 慶一 (ふうせん Fu-sen.) が独自に文章化しているものです。

IchigoJam BASIC リファレンス: CC BY https://ichigojam.net/<br />
ver 1.2<br />
https://ichigojam.net/IchigoJam-1.2.html<br />
ver 1.1<br />
https://ichigojam.net/IchigoJam-1.1.html<br />
ver 1.0.1<br />
https://ichigojam.net/IchigoJam-1.0.1.html<br />
ver 0.9.9<br />
https://ichigojam.net/IchigoJam-0.9.9.html<br />
ver 0.9.7 (PDF)<br />
https://ichigojam.net/IchigoJam-BASIC-reference.pdf

IchigoJam BASIC RPi ドキュメント<br />
https://ichigojam.github.io/RPi/index_ja.html

Facebook グループ IchigoJam-FAN (Japanese)<br />
https://www.facebook.com/groups/ichigojam/<br />
Facebook group IchigoJam-FAN@en (English)<br />
https://www.facebook.com/groups/ichigojamfan/

Maked by 志賀 慶一 (ふうせん Fu-sen.) | Keiichi SHIGA ( BALLOON a.k.a. Fu-sen. ), 2015-2018.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://licensebuttons.net/l/by/4.0/88x31.png" /></a>

この 文章 は <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">クリエイティブ・コモンズ 表示 4.0 国際</a> (CC BY 4.0) ライセンスで提供しています。

<a href="https://ichigojam.net/" target="_blank">IchigoJam</a> は <a href="https://jig.jp/" target="_blank">株式会社jig.jp</a> の登録商標です。
