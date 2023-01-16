# TS-Template
General purpose TypeScript project template for VSC, with eslint and nodemon.

<br>

### Stack:
- TypeScript (compiles to CommonJS for Node)
- ESLint with TypeScript parser & plugin
- VS Code auto-fix on save
- Nodemon to recompile and restart on changes
- TS-Node to quickly run TS scripts without needing TSC

<br>

### Setup:
1. Run `npm i` to install dependencies
2. Install this VS Code extension: [`dbaeumer.vscode-eslint`](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

<br>

### Usage:
- `npm start` to compile & start
- `npm run watch` to watch for file changes, recompile and restart automatically
- `npm test` to compile and run the script at `src/test.ts`
