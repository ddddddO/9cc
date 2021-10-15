# 9cc
https://www.sigbus.info/compilerbook


<ul>
<li><a href="https://www.sigbus.info/compilerbook#はじめに">はじめに</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#本書の表記法">本書の表記法</a></li>
<li><a href="https://www.sigbus.info/compilerbook#本書の想定する開発環境">本書の想定する開発環境</a></li>
<li><a href="https://www.sigbus.info/compilerbook#著者について">著者について</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#機械語とアセンブラ">機械語とアセンブラ</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#cpuとメモリ">CPUとメモリ</a></li>
<li><a href="https://www.sigbus.info/compilerbook#アセンブラとは">アセンブラとは</a></li>
<li><a href="https://www.sigbus.info/compilerbook#cとそれに対応するアセンブラ">Cとそれに対応するアセンブラ</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#簡単な例">簡単な例</a></li>
<li><a href="https://www.sigbus.info/compilerbook#関数呼び出しを含む例">関数呼び出しを含む例</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#本章のまとめ">本章のまとめ</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#電卓レベルの言語の作成">電卓レベルの言語の作成</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#ステップ1整数1個をコンパイルする言語の作成">ステップ1：整数1個をコンパイルする言語の作成</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ2加減算のできるコンパイラの作成">ステップ2：加減算のできるコンパイラの作成</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ3トークナイザを導入">ステップ3：トークナイザを導入</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ4エラーメッセージを改良">ステップ4：エラーメッセージを改良</a></li>
<li><a href="https://www.sigbus.info/compilerbook#文法の記述方法と再帰下降構文解析">文法の記述方法と再帰下降構文解析</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#木構造による文法構造の表現">木構造による文法構造の表現</a></li>
<li><a href="https://www.sigbus.info/compilerbook#生成規則による文法の定義">生成規則による文法の定義</a></li>
<li><a href="https://www.sigbus.info/compilerbook#bnfによる生成規則の記述">BNFによる生成規則の記述</a></li>
<li><a href="https://www.sigbus.info/compilerbook#単純な生成規則">単純な生成規則</a></li>
<li><a href="https://www.sigbus.info/compilerbook#生成規則による演算子の優先順位の表現">生成規則による演算子の優先順位の表現</a></li>
<li><a href="https://www.sigbus.info/compilerbook#再帰を含む生成規則">再帰を含む生成規則</a></li>
<li><a href="https://www.sigbus.info/compilerbook#再帰下降構文解析">再帰下降構文解析</a></li> <- いまここ
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#スタックマシン">スタックマシン</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#スタックマシンの概念">スタックマシンの概念</a></li>
<li><a href="https://www.sigbus.info/compilerbook#スタックマシンへのコンパイル">スタックマシンへのコンパイル</a></li>
<li><a href="https://www.sigbus.info/compilerbook#x86-64におけるスタックマシンの実現方法">x86-64におけるスタックマシンの実現方法</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ5四則演算のできる言語の作成">ステップ5：四則演算のできる言語の作成</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ6単項プラスと単項マイナス">ステップ6：単項プラスと単項マイナス</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ7-比較演算子">ステップ7: 比較演算子</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#トークナイザの変更">トークナイザの変更</a></li>
<li><a href="https://www.sigbus.info/compilerbook#新しい文法">新しい文法</a></li>
<li><a href="https://www.sigbus.info/compilerbook#アセンブリコードの生成">アセンブリコードの生成</a></li>
</ul></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#分割コンパイルとリンク">分割コンパイルとリンク</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#分割コンパイルとは">分割コンパイルとは</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#分割コンパイルとその必要性">分割コンパイルとその必要性</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ヘッダファイルの必要性とその内容">ヘッダファイルの必要性とその内容</a></li>
<li><a href="https://www.sigbus.info/compilerbook#リンクエラー">リンクエラー</a></li>
<li><a href="https://www.sigbus.info/compilerbook#グローバル変数の宣言と定義">グローバル変数の宣言と定義</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#c標準ライブラリとアーカイブファイル">C標準ライブラリとアーカイブファイル</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ8-ファイル分割とmakefileの変更">ステップ8: ファイル分割とMakefileの変更</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#ファイルの分割">ファイルの分割</a></li>
<li><a href="https://www.sigbus.info/compilerbook#makefileの変更">Makefileの変更</a></li>
</ul></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#関数とローカル変数">関数とローカル変数</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#ステップ91文字のローカル変数">ステップ9：1文字のローカル変数</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#スタック上の変数領域">スタック上の変数領域</a></li>
<li><a href="https://www.sigbus.info/compilerbook#トークナイザの変更-1">トークナイザの変更</a></li>
<li><a href="https://www.sigbus.info/compilerbook#パーサの変更">パーサの変更</a></li>
<li><a href="https://www.sigbus.info/compilerbook#左辺値と右辺値">左辺値と右辺値</a></li>
<li><a href="https://www.sigbus.info/compilerbook#任意のアドレスから値をロードする方法">任意のアドレスから値をロードする方法</a></li>
<li><a href="https://www.sigbus.info/compilerbook#コードジェネレータの変更">コードジェネレータの変更</a></li>
<li><a href="https://www.sigbus.info/compilerbook#メイン関数の変更">メイン関数の変更</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ10複数文字のローカル変数">ステップ10：複数文字のローカル変数</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ11return文">ステップ11：return文</a></li>
<li><a href="https://www.sigbus.info/compilerbook#年のcコンパイラ">1973年のCコンパイラ</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ12-制御構文を足す">ステップ12: 制御構文を足す</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ13-ブロック">ステップ13: ブロック</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ14-関数の呼び出しに対応する">ステップ14: 関数の呼び出しに対応する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ15-関数の定義に対応する">ステップ15: 関数の定義に対応する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#バイナリレベルのインターフェイス">バイナリレベルのインターフェイス</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#twos_complement">コンピュータにおける整数の表現</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#符号なし整数">符号なし整数</a></li>
<li><a href="https://www.sigbus.info/compilerbook#符号あり整数">符号あり整数</a></li>
<li><a href="https://www.sigbus.info/compilerbook#符号拡張">符号拡張</a></li>
<li><a href="https://www.sigbus.info/compilerbook#符号の反転">符号の反転</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#ポインタと文字列リテラル">ポインタと文字列リテラル</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#ステップ16-単項と単項">ステップ16: 単項<code>&amp;</code>と単項<code>*</code></a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ17-暗黙の変数定義を廃止してintというキーワードを導入する">ステップ17: 暗黙の変数定義を廃止して、intというキーワードを導入する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ18-ポインタ型を導入する">ステップ18: ポインタ型を導入する</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#ポインタを表す型を定義する">ポインタを表す型を定義する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ポインタが指している値に代入する">ポインタが指している値に代入する</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ19-ポインタの加算と減算を実装する">ステップ19: ポインタの加算と減算を実装する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ20-sizeof演算子">ステップ20: sizeof演算子</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ21-配列を実装する">ステップ21: 配列を実装する</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#配列型を定義する">配列型を定義する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#配列からポインタへの暗黙の型変換を実装する">配列からポインタへの暗黙の型変換を実装する</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ22-配列の添字を実装する">ステップ22: 配列の添字を実装する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ23-グローバル変数を実装する">ステップ23: グローバル変数を実装する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ24-文字型を実装する">ステップ24: 文字型を実装する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ25-文字列リテラルを実装する">ステップ25: 文字列リテラルを実装する</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ26-入力をファイルから読む">ステップ26: 入力をファイルから読む</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ27-行コメントとブロックコメント">ステップ27: 行コメントとブロックコメント</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ28-テストをcで書き直す">ステップ28: テストをCで書き直す</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#program">プログラムの実行イメージと初期化式</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#実行ファイルの構造">実行ファイルの構造</a></li>
<li><a href="https://www.sigbus.info/compilerbook#データセグメントの内容">データセグメントの内容</a></li>
<li><a href="https://www.sigbus.info/compilerbook#初期化式の文法">初期化式の文法</a></li>
<li><a href="https://www.sigbus.info/compilerbook#グローバル変数の初期化式">グローバル変数の初期化式</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ローカル変数の初期化式">ローカル変数の初期化式</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#ステップ29以降-要加筆">ステップ29以降: [要加筆]</a></li>
<li><a href="https://www.sigbus.info/compilerbook#dynamic-linking">スタティックリンクとダイナミックリンク</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#スタティックリンク">スタティックリンク</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#type">Cの型の構文</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#型を表す図">型を表す図</a></li>
<li><a href="https://www.sigbus.info/compilerbook#型を表す記法">型を表す記法</a></li>
<li><a href="https://www.sigbus.info/compilerbook#cの型の読み方">Cの型の読み方</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#ネストしていない型の読み方">ネストしていない型の読み方</a></li>
<li><a href="https://www.sigbus.info/compilerbook#ネストしている型の読み方">ネストしている型の読み方</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#練習問題">練習問題</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#おわりに">おわりに</a></li>
<li><a href="https://www.sigbus.info/compilerbook#付録1x86-64命令セット-チートシート">付録1：x86-64命令セット チートシート</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#整数レジスタの一覧">整数レジスタの一覧</a></li>
<li><a href="https://www.sigbus.info/compilerbook#メモリアクセス">メモリアクセス</a></li>
<li><a href="https://www.sigbus.info/compilerbook#関数呼び出し">関数呼び出し</a></li>
<li><a href="https://www.sigbus.info/compilerbook#条件分岐">条件分岐</a></li>
<li><a href="https://www.sigbus.info/compilerbook#条件代入">条件代入</a></li>
<li><a href="https://www.sigbus.info/compilerbook#整数論理演算">整数・論理演算</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#付録2gitによるバージョン管理">付録2：Gitによるバージョン管理</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#gitを使ったワークフロー">Gitを使ったワークフロー</a></li>
<li><a href="https://www.sigbus.info/compilerbook#コミットするときの注意点">コミットするときの注意点</a></li>
<li><a href="https://www.sigbus.info/compilerbook#gitの内部構造">Gitの内部構造</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#docker">付録3：Dockerを使った開発環境の作成</a>
<ul>
<li><a href="https://www.sigbus.info/compilerbook#セットアップ手順">セットアップ手順</a></li>
<li><a href="https://www.sigbus.info/compilerbook#コンテナを使ったビルド">コンテナを使ったビルド</a></li>
<li><a href="https://www.sigbus.info/compilerbook#コンテナに新たなアプリケーションを追加">コンテナに新たなアプリケーションを追加</a></li>
</ul></li>
<li><a href="https://www.sigbus.info/compilerbook#参考資料">参考資料</a></li>
<li><a href="https://www.sigbus.info/compilerbook#索引">索引</a></li>
</ul>