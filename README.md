# さくらのレンタルサーバのDB接続の手順

1. プロダクトの準備
   1. 動くものを作る！
      1. ローカルでデータベースにアクセスできることを確認
      2. ローカルで開発したプロダクトのデータベースの情報をPHPMyAdminでSQLファイルにしてエクスポートする
2. GitHubの準備
   1. GitHubに課題をpushする
3. さくらでデプロイの準備
   2. さくらサーバ内でデプロイするプロダクトのデータベースを作成する
   3. 作ったデータベースに3.1のSQLファイルをインポートして設定を反映させる
   4. サーバに関するファイルの情報をローカルから本番環境のものに書き換える
   5. FileZillaでプロダクトのファイルをアップロードする
   6. 接続確認する
   7. 無事SQLが実行(データの登録、参照)できればOK