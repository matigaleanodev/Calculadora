# Calculadora

[Español](README.es.md)

Angular calculator demo. It explores component interaction and expression evaluation with Math.js.

## Stack

Angular · TypeScript · Math.js.

## Scope and configuration

Self-contained frontend exercise. It is kept as a learning reference, not as a supported calculator library.

## Expression handling

[AppComponent](src/app/app.component.ts) collects the expression in `entrada`, evaluates it with Math.js when `=` is pressed, and resets it to `0` when cleared. Expression errors are not caught by the component; this example does not provide an error-recovery UI.

## Local development

Use a Node.js toolchain compatible with package.json and the dependency lockfile, when present.

```sh
npm install
npm start
npm run build
npm test
```
