# practice-ts
## package.jsonの作成
```
pnmp init
```

## TypeScriptインストール
```
pnpm install --save-dev typescript @types/node ts-node
```

## tsconfig.jsonの作成
```
npx tsc --init
```

## TypeScriptのコンパイル
```
pnpm install
npx tsc
```

## Node.jsで実行
```
node dist/<対象のjsファイル>
```

## TypeScripのコンパイルとNode.jsでの実行
```
npx ts-node 
npx node --loader ts-node/esm src/index.ts
```
