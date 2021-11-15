### This is a test accompanying [this Quokka issue](https://github.com/wallabyjs/quokka/issues/713).

```cli
git clone https://github.com/FlorisSteenkamp/Quokka-ESM-TypeScript-test.git
```

## To see that TypeScript is happy simply do (from the Cli):

```cli
tsc
```

or simply observe there are no TypeScript errors in the VS Code editor.

## To see that Node.js is happy:

```cli
node --loader ts-node/esm ./src/index.ts
```
