# bun-typeorm-compile-issue

Repository to reproduce the issue of Bun 1.1.33 generating a binary file with TypeORM as a dependency.

```bash
bun build --compile index.ts --target=bun --sourcemap --outfile compiled
```
