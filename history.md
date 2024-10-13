## oct-13-2024

- コンテナ内から接続可能に
  - docker-compose.ymlにnetworkを追加
  - .envの接続先ホスト名を変更
- postgresqlに切り替え
  - npm run devでは接続可、コンテナ内からは接続不可
- テンプレートから基本コード作成

```
npx try-prisma --template typescript/graphql-nestjs
```
