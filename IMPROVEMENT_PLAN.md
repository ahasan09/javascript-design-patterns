# Improvement Plan: javascript-design-pattern

## Overview
GoF creational and structural patterns in JavaScript with Babel/Nodemon. No tests, only covers two of three GoF categories (missing behavioral), and uses a Babel+Nodemon setup rather than modern ES modules.

## Improvements

### Complete GoF Coverage
- Add behavioral patterns: Chain of Responsibility, Command, Iterator, Mediator, Memento, Observer, State, Strategy, Template Method, Visitor
- Add modern JavaScript patterns not in GoF: Module, Revealing Module, Mixin, Proxy, Pub/Sub

### Testing
- Add Jest unit tests for each pattern demonstrating its behavior
- Each test should show: "problem without the pattern" and "solution with the pattern"
- Wire `npm test` to Jest in `package.json`

### Modernization
- Replace Babel + Nodemon with native ES modules (Node.js supports them natively since v12) and remove the transpilation step
- Convert to TypeScript — design patterns benefit greatly from type annotations (interfaces, generics)
- Replace Nodemon with `tsx --watch` or `ts-node` for TypeScript watch mode

### Code Quality
- Add ESLint + `@typescript-eslint` + Prettier
- Add JSDoc/TSDoc comments to each pattern class documenting intent and usage

### Documentation
- Add a root `README.md` listing all patterns with descriptions, real-world use cases, and links to further reading
- Add inline "When to use" and "When NOT to use" comments

### DevOps
- Add GitHub Actions CI: lint + test on every push
