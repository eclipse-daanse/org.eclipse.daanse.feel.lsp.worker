# @eclipse-daanse/org.eclipse.daanse.feel.lsp.worker

Web Worker LSP server for [FEEL-Langium](https://github.com/eclipse-daanse/org.eclipse.daanse.feel.langium) — provides Language Server Protocol support for FEEL expressions inside a browser Web Worker (Monaco integration).

## Install

```bash
npm install @eclipse-daanse/org.eclipse.daanse.feel.lsp.worker
```

## Usage

```ts
const worker = new Worker(
  new URL('@eclipse-daanse/org.eclipse.daanse.feel.lsp.worker', import.meta.url),
  { type: 'module' }
);
```

## Build

```bash
npm ci
npm run build
```

## License

[EPL-2.0](LICENSE)
