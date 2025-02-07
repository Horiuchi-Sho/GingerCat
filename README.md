# GingerCat
- 2024年度デジタルコム先端技術研究会で開発したアプリ
<img width="400px" src="imgs/Title.png">

## 概要
「ガリレオによるピサの斜塔の実験」のような有名な物理実験を題材にして、ゲームエンジン間の物理エンジン設定や動作の違いを体感するのが目的。

Unity と Godot で同等の物理エンジン設定を行った実験シーンを作成し、比較する。

## [Unity版 GingerCat](https://horiuchi-sho.github.io/GingerCat/Unity/index.html)
- ピサの斜塔の実験シーン
- 物体の自由落下と情報表示
<img width="400px" src="imgs/SampleImage_Unity.png">

***

## [Godot版 GingerCat](https://horiuchi-sho.github.io/GingerCat/Godot/index.html)
- ピサの斜塔実験シーン
- 物体の自由落下のみ
<img width="400px" src="imgs/SampleImage_Godot.png">

## 物理エンジンの設定情報の関する調査

***

***

# リポジトリ構成

## ブランチ
- main : 開発用ブランチ
- release : GitHub Pagesで公開するWebアプリの公開用ブランチ

### ファイルツリー
```
(root)
  +- README.md : ホームページ相当といて記述する
  +- Godot : Godot版アプリの配置用ディレクトリ。直下に Web でエクスポートした index.html を含むビルド成果物一式を配置する
  +- Unity : Unity版アプリの配置用ディレクトリ。直下に Web を Active にしてビルドした index.html を含むビルド成果物一式を配置する
  +- docs : 公開用としてファイル配置していたが廃止
```

## Godot版
- Web で エクスポート する

## Unity版
- Build Profile で Web を Active にしてビルド
- Project Settings > Player > Publishing Settings > Decompression Fallback を有効にしてビルドする

