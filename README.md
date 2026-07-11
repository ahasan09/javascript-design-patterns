# JavaScript Design Patterns

Implementations of classic design patterns in modern JavaScript (ES modules), organized by category.

## Patterns Covered

### Creational Patterns

> Deal with object creation mechanisms.

- **Constructor** — `creational-patterns/constructor-pattern.js`
- **Class Design** — `creational-patterns/class-design-pattern.js`
- **Factory** — `creational-patterns/factory-pattern.js`
- **Abstract Factory** — `creational-patterns/abstract-factory-pattern.js`
- **Singleton** — `creational-patterns/singleton-pattern.js`

### Structural Patterns

> Deal with object composition and relationships.

- **Module** — `structural-patterns/module-pattern.js`
- **Mixin** — `structural-patterns/mixin-pattern.js`
- **Other patterns** — `structural-patterns/other-patterns.js`

## Tech Stack

- JavaScript (Node.js, ES modules)

## Prerequisites

- [Node.js](https://nodejs.org/) v18+

## Getting Started

```bash
git clone https://github.com/ahasan09/javascript-design-patterns
cd javascript-design-patterns
npm install
```

## Running Examples

```bash
# Run the entry point
node index.js

# Or run a specific pattern file directly
node creational-patterns/singleton-pattern.js
node structural-patterns/mixin-pattern.js
```

## Project Structure

```
javascript-design-patterns/
├── creational-patterns/
│   ├── abstract-factory-pattern.js
│   ├── class-design-pattern.js
│   ├── constructor-pattern.js
│   ├── factory-pattern.js
│   └── singleton-pattern.js
├── structural-patterns/
│   ├── mixin-pattern.js
│   ├── module-pattern.js
│   └── other-patterns.js
└── index.js   # Entry point
```
