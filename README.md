# TypeORM Playground

TypeORM の機能検証用のリポジトリ

## 環境構築

1. TypeScript の実行環境を用意する
   `npm install --save-dev typescript @types/node ts-node`
2. TypeORM をインストールする
   `npm install --save typeorm reflect-metadata`
3. SQL Server をインストールする
   `npm install --save mssql sqlite3`

TypeScript を実行するためのコンパイル設定を追加する。

```json
{
  "compilerOptions": {
    "lib": ["es5", "es6"],
    "target": "es6",
    "module": "commonjs",
    "moduleResolution": "node",
    "emitDecoratorMetadata": true,
    "experimentalDecorators": true,
    "sourceMap": true
  },
  "exclude": ["node_modules"]
}
```
