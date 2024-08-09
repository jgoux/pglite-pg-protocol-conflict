# PGlite and pg-protocol conflict

If `pg-protocol` is present in node_modules, the TypeScript compiler will throw an error when compiling code involving PGlite.

Commands to reproduce the error:

```shell
npm install
npm run build
```