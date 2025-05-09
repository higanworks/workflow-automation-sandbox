# workflow-automation-sandbox

次のステージへのプルリクエストを自動作成するテストだ

- dev へのPRがマージされたら dev => staging にPR作成
- dev => staging のPRがすでにあれば、コメントに追記する
