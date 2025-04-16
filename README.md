# Make a simple function via CLI

- ref. 簡単な関数を作ってみよう | TypeScript 入門『サバイバル TypeScript』 https://typescriptbook.jp/tutorials/make-a-simple-function-via-cli

```shell
root ➜ /workspaces/typescript-book-simple-function $ node increment_javascript.js
1000
9991
```

```shell
root ➜ /workspaces/typescript-book-simple-function $ tsc increment_typescript.ts
increment_typescript.ts:5:25 - error TS2345: Argument of type 'string' is not assignable to parameter of type 'number'.

5 console.log(incrementTs("999"));
                          ~~~~~


Found 1 error in increment_typescript.ts:5
```
