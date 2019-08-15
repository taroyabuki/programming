# プログラム言語とプログラミング

データ解析入門は[こちら](https://github.com/taroyabuki/analysis)

## 重要なサイト

* 講義資料：https://github.com/taroyabuki/programming
* 連絡チャネル：https://pmcit.slack.com/ （https://join.slack.com/t/pmcit/signup でアカウントを作り，チャネル「2019プログラム言語とプログラミング」に参加する。）

## 教科書

コーリー・アルソフ『独学プログラマー』（日経BP社, 2018）

## 持ち物

* PC（無線LAN機能付き）

## 実行環境

[Google Colaboratory](https://research.google.com/colaboratory/)の「Python 3のノートブック」を使う。

インターネット接続のない環境で学びたい場合は，Anacondaを使う。（ただし，Anaconda自体のインストールには，インターネット接続が必要である。）

1. https://www.anaconda.com/distribution/ からWindows版の64-Bit Graphical Installerをダウンロードし，実行する．
1. スタートメニューからAnaconda Promptを起動し，`jupyter notebook`と入力し，Enterキーを押す．
1. ブラウザで「New」→「Python 3」

## 評価

* 期末テスト（40）
* レポート1，2（60）

### 期末テスト（40）

手書きのメモを持ち込み可。ただし，用紙は[試験問題その2](exam2.pdf)をA4で印刷したもののみとする。折り目のある用紙や，破れた用紙は持ち込み不可。（クリアファイルに入れて持ってくることを勧める。）

持ち物

* 学生証
* 筆記具
* 試験問題その2（持ち込みを希望する場合）
* **iPad（授業アンケート回答のため）**

### レポート（60）

問題を3問解くレポートを2回提出してもらう予定だったが，問題を6問解くレポートを1回提出することにした。つまり，**解くべき問題は6問**である。

1. GitHubのアカウントを作成する．
1. 教員から指示されたURLにアクセスする．（授業を欠席してURLがわからない場合は，他の学生に聞くか，大学のメアドで教員に問い合わせること．）
1. 「Authorize GitHub Classroom」の画面で「Authorize github」をクリックする（1回だけ）．
1. 「Accept this assignment」をクリックする．
1. 「Your assignment has been created here:」のURLにアクセスする．ここがレポートの保存場所（リポジトリ）である．このレポートの場合は「https://github.com/yabukilab/report1-{GitHubのユーザ名}」
1. ファイルREADME.mdでレポートを書く．（このファイルはMarkdown記法で書くことになっている．詳細は「github markdown」で検索して確認せよ．）
    1. 鉛筆マークをクリック
    1. 編集
    1. 「Commit changes」をクリックして完了．修正したい場合はiに戻る．

注意：レポートは，忘れた頃に読み返して，完全に理解できる詳しさで書くこと。説明，コード，実行結果は必須である。

* 締切：7月31日(水)
* レポートを再提出しなければならない学生の学生番号を8月8日(木)までにここに掲載する。再提出の締切は8月14日(水)

レポート（再提出を含む）に不備があるもの

* Yamada1999Masahiro1122 名なし（1842127を保留にしている）
* 1842016 分量不足（保留）

* RTcontrol 名なし
* tomo0609
* arle4690
* junta0322
* Koukikun4989
* kubokuro
* takahasiyouhei

### 追加課題（10）

このリポジトリのフォルダstudentsに，ファイルを一つ追加するためのプルリクエストを実行せよ。ファイル名は{学生番号}とする（例：`1234567`。`1234567.txt`は不可）。締切：7月31日(水)までにPRしたものを対象とする。8月14日(水)までにマージされなければならない。

## 予定

**休講** 7月10日(水)（第13回）
**補講** 7月8日(月) 5限@8102

1. [イントロダクション](01_introduction.md)
1. [さあ，はじめよう！](02_getting_started.md)
1. [プログラミング入門](03_introduction_to_programming.md)
1. [関数](04_functions.md)
1. [コンテナ](05_containers.md) **宿題：https://github.com のアカウントを作っておくこと（すでにある人は作業不要）．** 参考：[【2019年1月現在】GitHubアカウント作成方法](https://qiita.com/okumurakengo/items/848f7177765cf25fcde0)
1. [文字列操作](06_string_manipulation.md)
1. [ループ](07_loops.md)・バージョン管理（プルリクエスト）
1. [モジュール](08_modules.md)
1. [ファイル](09_files.md)
1. [知識を1つにまとめる（1）](10_bringing_it_all_together.md)
1. 正規表現
1. データ構造
1. アルゴリズム
1. [シミュレーション](14_simulation.md)
1. 期末テスト
