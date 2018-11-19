# 1 dimensional bed variation model of bed-load and mixed grain size

## sample


### case01

<iframe src="https://computational-sediment-hyd.github.io/1DBedVariationMixed/case01.html" width="600" height="300" ></iframe>


<!-- 2 dimensional unsteady Flow model : channel network version

一般的な河道断面形状を対象とした一次元（準二次元)不定流計算モデル．河道網にも対応している．

## Description

 - 一部簡略化しているものの，ほぼ実務レベルで使用する計算のため，非常に煩雑である．
 - 不定流計算のスキームは，referenceの論文を参照されたい．一部風上化の判定に修正を加えているが，一次元流れの場合，影響はない．
 - テストケースとして，多摩川の解析用ファイルセットをsample_dataフォルダに同梱している．
 - fortran2008によるオブジェクト指向プログラミングを採用しており，プログラミングに精通していない方が，すべてを理解することはほぼ不可能なため，読めそうなところだけ読めば問題ないと思います．質問も随時受け付けます．

## Requirement

- Windows 10
- gfortran 7.0 or more (Fortran 2008)
    * gcc最新版は[sourceforge](https://sourceforge.net/projects/mingw-w64/files/)からx86_64-win32-sehをダウンロード．
- cmake 3.0 or more
- linuxでの動作確認は行っておりませんが，WSL（Windows Subsystem for Linux）のubuntuで動作確認を行ったため問題ないと思います．centos，ubuntu（16以前）に標準で導入されているgccが古いため，最新版にアップデートする必要があります．

## Usage

### 実行ファイルの作成方法

- build.bat or build.shにコンパイルオプション等を記載しております．
- 上級者はcmakeをお使い下さい．

## sample

### 多摩川2007年9月出水
- 多摩川の2007年9月出水を対象としたデータセットおよび解析結果を同梱しております．
- 横断測量データ(2007年測量)および水位データは京浜河川事務所より提供頂いたもの，流量データは水文水質データベースよりダウンロードしたものを使用しております．編集前のオリジナルデータはsample_data/tamagawa2007/original_dataフォルダに保存しております．
- 下流端は，50.0k地点に等流水深を与え，上流端は直轄区間の上流端と設定しております．sample_data/tamagawa2007/locationフォルダを参照下さい．
- 計算水位の比較は，59.4k調布橋で行っております．
- 作成した実行ファイルをsample_data/tamagawa2007/simulationフォルダ内で実行すると計算がスタート．計算条件等はnamelistファイル(.nml)に記載しているため，実行時の引数等は不要です．
- namelistの書き方は，[このあたり](http://www.rivhiro-weather.com/knowledge/?p=557)を参照下さい．
- 計算時間は数分程度です． -->

![example](/sample_data/tamagawa2007/output_plot_chart/sample.png "example")

