# express-crud（作成中）

## 概要

こちらのリポジトリではExpressでブログ投稿APIを作成することで、認証・認可とユーザ作成、ブログのCRUD APIを実装していきます。

## デモ

デモは [Heroku](https://www.heroku.com) に上がっています。

demo: [Demo](https://express-crud-sample.herokuapp.com/)

## 課題で身に着けること

- データベースの基本
- TypeScriptの基本
- MVC(Model View Controller)
- SQLでのCRUD
- ORMの基礎
- ORMでのCRUD
- API(Passport)を使用した認証・認可
- Expressを利用したWeb APIの実装

## 課題の進め方

### 0. 実装に必要な概念を学ぶ

#### Docker

コンテナ仮想化技術をメインでは学びませんがMySQLを使用する際に使うので概要だけでもさらうようにしておいてください。

#### データベース(MySQL)の基本

これまでデータベースを触ったことがない人、Wikiの内容を初めてみる方は課題前に必ずチュートリアルを終わらせてから課題に入ってください。

[MySQLチュートリアル](https://github.com/version-1/express-crud/wiki/MySQL%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB)

#### ORMとは

#### MVCとは

#### WebAPIでの認証・認可

[Express+Passportでの認証の実装]()

### 1. 課題用リポジトリの作成

フォークでなく個人のアカウントにリポジトリ を作成してください。
課題はdevelopブランチで開発を進め、最後完成した後にmasterへのプルリクエストを作成してコードレビューをうけるようにしてください。


### 2. 実装

下記順番に実装を行うようお願いします。

#### ステップ1 Express+TypeScript環境の構築

#### ステップ2 Sequerizeの導入

[API仕様書](https://github.com/version-1/express-crud/wiki/API%E4%BB%95%E6%A7%98%E6%9B%B8) を元にモデルの作成

- モデルの作成
- DB接続の確認

#### ステップ3 migration, seederのセットアップ

#### ステップ4 認証/認可の実装

`/auth` 配下のエンドポイントの実装

[API仕様書](https://github.com/version-1/express-crud/wiki/API%E4%BB%95%E6%A7%98%E6%9B%B8)


#### ステップ4 その他のエンドポイントの実装

仕様書にあるその他のエンドポイントの実装

[API仕様書](https://github.com/version-1/express-crud/wiki/API%E4%BB%95%E6%A7%98%E6%9B%B8)

### 3. HerokuにAPIをデプロイ

HerokuにAPIをデプロイして公開します。
手順はWikiを参照してください。

[Herokuへのデプロイ手順](https://github.com/version-1/express-crud/wiki/Heroku%E3%81%B8%E3%81%AE%E3%83%87%E3%83%97%E3%83%AD%E3%82%A4)

## 注意事項
