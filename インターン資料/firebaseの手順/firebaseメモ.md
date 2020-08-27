# firebase

## 事前準備

- googleアカウントが必要
- node.jsのインストールが必要
  - https://nodejs.org/ja/
  - インストールの確認はコマンドプロンプトを起動して「node -v」を実行して「v12.18.3」が表示されたらOK

## 作業手順

- firebaseのサイトに移動
  - https://firebase.google.com/?hl=ja
- プロジェクト作成
- 開発　→ Hosting
- 表示されたコマンド叩く
```sh
firebase login
cd {project_dir}
firebase list
firebase init
firebase deploy

非公開にするには：firebase hosting:disable
```

詳細は画像参照
