# workflow-automation-sandbox

次のステージへのプルリクエストを自動作成するテストだ

- `dev` へのPRがマージされたら 自動デプロイ開始
- 自動デプロイが成功したら、 `dev` => `staging` にPR作成
- このとき `dev` => `staging` のPRがすでにあれば、コメントに追記する
- `staging` PRがマージされたら `staging` => `main` に対して同様のことを実施する

----

コメント追記テスト用
