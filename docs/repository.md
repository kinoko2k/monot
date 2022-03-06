###### Monot - 内部開発者向けドキュメント
# リポジトリの使い分け
適切に開発を進めるには、リポジトリを正しく使うことが必要です。ここでは、そんなリポジトリの使い分けなどを書いていきます。なおわからないことがあったらDiscordへ、Go

## 前提
- Git、GitHubについて最低限の知識があること

## `monot`リポジトリ
こちらのリポジトリは、主に前バージョンのマイナーアップデート開発用に使われます。
また、ベータ版に関しては`monot`リポジトリの`beta`ブランチで行うようにする予定です。

## `monot-dev`リポジトリ
こちらは、非公開リポジトリとなっていて、次期メジャーバージョンの開発用に使われます。
マイナーアップデートの開発にはこちらのリポジトリを使用しません。

## 並列作業
`monot-dev`リポジトリで開発したメジャーバージョンを公開した後、その後バグなどが発覚した場合、`monot`リポジトリで公開されているバージョン、そして`monot-dev`リポジトリで保管されているバージョン両方のソースコードに変更を加えます。

## メジャーバージョン公開
メジャーバージョン公開に関してはSorakimeさんがなんとかやってくれますので何も考えなくてもいいです。