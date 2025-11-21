# Calculadora

[English](README.md)

Demo Angular de una calculadora. Explora interacción entre componentes y evaluación de expresiones con Math.js.

## Stack

Angular · TypeScript · Math.js.

## Alcance y configuración

Ejercicio frontend independiente. Se conserva como referencia de aprendizaje, no como biblioteca de cálculo con soporte.

## Evaluación de expresiones

[AppComponent](src/app/app.component.ts) acumula la expresión en `entrada`, la evalúa con Math.js al presionar `=` y la reinicia a `0` al limpiar. El componente no captura errores de evaluación; este ejemplo no ofrece una interfaz de recuperación ante expresiones inválidas.

## Desarrollo local

Usar un entorno Node.js compatible con package.json y el lockfile de dependencias, cuando exista.

```sh
npm install
npm start
npm run build
npm test
```
