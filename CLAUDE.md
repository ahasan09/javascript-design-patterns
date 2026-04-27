# JavaScript Design Pattern

GoF creational and structural design patterns implemented in JavaScript, transpiled with Babel and watched with Nodemon. An Express server (`index.js`) demonstrates a pattern by serving its output.

## Tech Stack
- JavaScript (ES6+)
- Babel (transpilation)
- Nodemon (file watcher)
- Express (demo server)

## Project Structure
```
javascript-design-pattern/
├── creational-patterns/
│   └── <pattern>.js
├── structural-patterns/
│   └── <pattern>.js
├── index.js              # Express demo entry point
└── package.json
```

## Development
```bash
# Install dependencies
npm install

# Run with file watching
npm start
```

## Key Notes
- Babel is used to support modern ES6+ syntax.
- `npm start` uses Nodemon to auto-restart on file changes.
