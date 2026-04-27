# JavaScript Design Patterns

Implementations of classic Gang of Four (GoF) design patterns in TypeScript/JavaScript, organized by category.

## Patterns Covered

### Creational Patterns

> Deal with object creation mechanisms.

- **Factory Method** — create objects without specifying the exact class
- **Singleton** — ensure only one instance of a class exists
- **Builder** — construct complex objects step by step
- **Prototype** — clone existing objects

### Structural Patterns

> Deal with object composition and relationships.

- **Adapter** — make incompatible interfaces work together
- **Decorator** — add behavior to objects dynamically
- **Facade** — provide a simplified interface to a complex system
- **Proxy** — control access to another object

## Tech Stack

- TypeScript / JavaScript (Node.js)

## Prerequisites

- [Node.js](https://nodejs.org/) v14+

## Getting Started

```bash
git clone https://github.com/ahasan09/javascript-design-patterns
cd javascript-design-patterns
npm install
```

## Running Examples

```bash
# Run the main entry point (demonstrates all patterns)
node index.js

# Or run a specific pattern
node creational-patterns/singleton/index.js
node structural-patterns/adapter/index.js
```

## Project Structure

```
javascript-design-patterns/
├── creational-patterns/
│   ├── singleton/
│   ├── factory/
│   ├── builder/
│   └── prototype/
├── structural-patterns/
│   ├── adapter/
│   ├── decorator/
│   ├── facade/
│   └── proxy/
└── index.js   # Entry point — runs all pattern demos
```
