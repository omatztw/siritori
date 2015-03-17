#簡易音声合成しりとりアプリ

---

#Overview
しりとりをするアプリ。
返答が音声合成とテキストで返ってくる。

## Description
オープンキャンバス向けに作成したアプリ。
触り始めたpythonをつかって、中学生向けにしりとりアプリを作成し展示した。

基本的な動作は

1. 入力されたテキストの末尾の文字を記録
1. 辞書ファイル「末尾の文字.txt」からランダムな行から記述されている語彙をコピー
1. 語彙を音声合成で読み上げ、テキストで出力

という流れになっている。
作成のしやすさを優先したため、漢字、片仮名、濁音、同じ単語を使うルール違反などに未対応。

* 平仮名で入力しなければならない
* 先頭と末尾には漢字、濁音、片仮名を使ってはいけない

という条件付で動作する。

## Requirement

pyct、openjtalkが必要
 
## Demo

![実行例](https://dl.dropboxusercontent.com/u/33568010/github/%E7%AF%84%E5%9B%B2%E3%82%92%E9%81%B8%E6%8A%9E_024.png)