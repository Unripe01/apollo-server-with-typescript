# apollo-server-with-typescript
apolloserver + typescript + docker 環境を作ってみた。

## 作成手順
まずはGoogleのガイドラインで自動生成してくれるらしい
``` 
npx gts init -y
```

## 型作成コマンド
npm run codegen

## 認証処理
Authorization ヘッダに適当な値を入れないと認証できません。
![image](https://user-images.githubusercontent.com/2908535/126059735-5f89b7a9-1dff-44c4-a856-001e89a1bad5.png)
![image](https://user-images.githubusercontent.com/2908535/126059736-43034a11-4f67-44e9-a307-dd7edb2be5bd.png)

## 参考記事
https://zenn.dev/intercept6/articles/3daca0298d32d8022e71
