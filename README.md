# README

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。
その後、次のコマンドで必要になる RubyGems をインストールします。

```
$ bundle install --without production
```

その後、データベースへのマイグレーションを実行します。

```
$ bundle exec rails db:migrate
```

最後に、テストを実行してうまく動いているかどうか確認してください。

```
$ bundle exec rails test
```

テストが無事に通ったら、Railsサーバーを立ち上げる準備が整っているはずです。

```
$ bundle exec rails server
```