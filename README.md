# Test App

静的なフロントエンドとWebAPIの足し算アプリケーション

## 開発モードでの起動手順

devモード起動方法

```console
cd backend/
npm ci
npm run dev
```

ブラウザから http://localhost:8080 でアクセス

## バックエンドをビルドして実行する手順

バックエンドのビルド/起動方法 

```console
cd backend/
npm ci
npm run build
node dist/index.js
```
