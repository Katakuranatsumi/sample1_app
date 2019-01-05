# README

＃ Ruby on Railsチュートリアルのサンプルアプリケーション

これはRuby on Railsチュートリアル（３章以降）を参照して作ったサンプルアプリケーションです。
「Ruby on Rails チュートリアル」（https://railstutorial.jp/）

＃＃使い方

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。
その後、次のコマンドをターミナル(Windowsはコマンドプロンプト)で打ち、RubyGemsをインストールします。

$ bundle install --without production

次に、データベースへのマイグレーションを実行してください。

$ rails db:migrate

次に、テストを実行してうまく動いているか確認してください。

$ rails test

テストが無事に通ったら、Railsサーバーを立ち上げてください

$ rails server

* Ruby version
  ruby 2.5.0p0
* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
