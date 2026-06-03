# @plurnk/plurnk-mimetypes-grammar-haskell

Pre-built `tree-sitter-haskell` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-haskell
```

## what's in here

- **`haskell.wasm`** — pre-built from the pinned upstream [tree-sitter-haskell](https://github.com/tree-sitter/tree-sitter-haskell) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `haskell.wasm` is built from the upstream tree-sitter-haskell grammar; see the pinned commit for that project's attribution.
