# LATEX_CheatSheet

このgitリポジトリは関根研究室のLaTeXドキュメントを管理するものです．
このリポジトリには以下のファイルがあります．

- cheat.pdf
- cheat.tex
- cheat.bib

## リポジトリをクローンする

1. 適当なディレクトリに移動してリポジトリをクローン(今いるディレクトリに新しいディレクトリが作られます)
    ```
    git clone https://github.com/Sekine-lab-LaTeX-manual/LaTeX_CheatSheet.git
    ```

2. クローンできたらディレクトリを移動しましょう．
    ```
    cd LaTeX_CheatSheet
    ```

あとは好きなようにファイルを加筆・修正しましょう．

## ドキュメントを更新したいときは

まず，作成したディレクトリに移動して
```
git pull
```
でリモートをローカルに取り込みましょう．

cheat.tex，cheat.bibの内容を変更したら必ずコンパイルし，cheat.pdfを確認しましょう．

変更が確認できたら，リモートにプッシュしましょう．
```
git add -u
git commit -m "任意のコメント"
git push
```
これで更新完了です．