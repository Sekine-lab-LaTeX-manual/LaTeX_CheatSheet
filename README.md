# LATEX_CheatSheet

このgitリポジトリは関根研究室のLaTeXドキュメントを管理するものです．
このリポジトリには以下のファイルがあります．

- cheat.pdf
- cheat.tex
- cheat.bib

## リポジトリをクローンする


1. ターミナル(コマンドプロンプト)を開いてリポジトリ用のディレクトリを作成
    ```
    mkdir ディレクトリ名
    ```

2. 作成したディレクトリに移動してリポジトリをクローン
    ```
    git clone https://github.com/Sekine-lab-LaTeX-manual/LaTeX_CheatSheet.git
    ```

クローンできたら，好きなようにファイルを加筆・修正しましょう．

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