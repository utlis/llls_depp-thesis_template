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
以下、READMEも日本語で記述します。


## Contents

本テンプレートはLaTeXとWordの2種類が含まれています。
学位論文の執筆においてはどちらを利用しても構いません（体裁は同じになります）が、強く **LaTeX** 版を推奨しています。

フォルダのトップレベルは次のようになっており、対応するフォルダに当該形式のテンプレートが入っています。

`thesis_guideline.pdf` が文書版の執筆要綱です。

`LaTeX`フォルダには、テンプレートとしてそのまま使える`thesis_main.pdf`と、執筆要綱を生成するために使った tex ソースが含まれており、後者はすべて `sample`を接頭辞に持つファイルです。

`Word`フォルダには卒業論文用のテンプレートと、修士論文用テンプレートがそれぞれ入っています。

```{}
- LaTeX/
- Word/
- thesis_guideline.pdf
```


## Usage

### LaTeX version

TeXLive 2016 以上をインストールした状態で利用してください。

また、`LaTeX/`フォルダ直下で以下のコマンドを実行してエラーなくPDFファイル`sample_guideline.pdf`が生成されることを確かめてください。
そしてそのPDFが`../thesis_guideline.pdf`と同一の内容となっていれば、今後問題なく執筆できるはずです。


```
$ latexmk sample_guideline.tex
```

### Word version

Word版はまだ作っていません。

Word版に関しては、MS Office で開いてもらえばすぐに利用できます。
推奨バージョンは Office 2016 以上です。
それ未満のバージョンでのテンプレートの動作は保証しませんし、その結果生成される学位論文に体裁上の不備があっても本コースでは受理しません。

中身は空になっていますので、執筆要綱の第2章を参照しながら執筆してください。

## Licence and Contribution

本テンプレートはご自由に加工してお使いいただいて構いません。

文系領域の学士・修士論文に使えるLaTeXテンプレートのスタンダードとなることを目指しています。
とくに、初心者も上級者も納得の **モダン** なTeX執筆環境の構築にご協力いただける方の Pull Request をお待ちしております。
