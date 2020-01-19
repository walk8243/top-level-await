# Top Level Await

このリポジトリでは、[Top Level Await](https://github.com/tc39/proposal-top-level-await)をTypeScriptで使ってみる内容です。

## 必要な環境

- Node.js
  - 13.2.0（13.6.0で実行できることは確認済み）
- TypeScript
  - v3.8
- V8
  - 7.9（7.8まででは対応していない）

## 実行

```.sh
yarn run build
yarn run start
```

## 参考

- [TypeScript側での対応Issue](https://github.com/microsoft/TypeScript/issues/25988)
- [V8エンジンのドキュメント](https://v8.dev/features/top-level-await)
- [JavaScriptでimportを使う方法](https://github.com/microsoft/TypeScript/issues/18442)
