# LLLS/DEPP Thesis Template

**THESIS TEMPLATES IN THIS REPOSITORY ARE UNOFFICIAL**

**このリポジトリの論文テンプレートはまだ非公式です**

The thesis template files for the following courses in the University of Tokyo

- Division of Lifelong Learning Infrastructure Management, Graduate School of Education
- Division of Educational Practices and Policies, Faculty of Education

東京大学の以下のコースのための学位論文テンプレート集です：

- 教育学研究科 生涯学習基盤経営コース
- 教育学部 教育実践政策学コース

本テンプレート集は現段階では日本語で執筆する学生を対象としています（英語版は準備中）。
以下、README も日本語で記述します。


## Contents

本テンプレートは LaTeX と Word の 2 種類が含まれています。
学位論文の執筆においてはどちらを利用しても構いません（体裁は同じになります）が、強く **LaTeX** 版を推奨しています。

フォルダのトップレベルは次のようになっており、対応するフォルダに当該形式のテンプレートが入っています。

```
- LaTeX/
- Office/
- thesis_guideline.pdf
```

`thesis_guideline.pdf` が文書版の執筆要綱です。
（開発中は `LaTeX/thesis_main_sample.pdf` がそれに相当するファイルです。）

`LaTeX` フォルダには、テンプレートとしてそのまま使える`thesis_main_sample.tex`と、執筆要綱を生成するために使った TeX ソースが含まれており、後者はすべて `sample`を接頭辞に持つファイルです。

`Office` フォルダには、LibreOffice 及び MS Office それぞれに、卒業論文用と修士論文用の 2 種類のテンプレートが入っています。

## Usage

### LaTeX version

TeXLive 2016 以上をインストールした状態で利用してください。

また、`LaTeX/` フォルダ直下で以下のコマンドを実行してエラーなく PDF ファイル `thesis_main_sample.pdf` が生成されることを確かめてください。
そしてその PDF が `thesis_guideline.pdf` と同一の内容となっていれば、今後問題なく執筆できるはずです。


```shell
$ cd LaTeX
$ latexmk thesis_main_sample.tex
```

### Office version

Office テンプレートは暫定的な対応です。
全面的なサポートはできませんのでご注意ください。

LibreOffice 版と MS Office Word をダブルクリックするなどして開いてもらえばすぐに利用できます。
推奨バージョンは LibreOffice v5 または MS Office Word 2016 以上です。
それ未満のバージョンでのテンプレートの動作は保証しませんし、その結果生成される学位論文に体裁上の不備があっても本コースでは受理しません。

## Licence and Contribution

本テンプレートはご自由に加工してお使いいただいて構いません。

文系領域の学士・修士論文に使える LaTeX テンプレートのスタンダードとなることを目指しています。
とくに、初心者も上級者も納得の **モダン** な TeX 執筆環境の構築にご協力いただける方の Pull Request をお待ちしております。
