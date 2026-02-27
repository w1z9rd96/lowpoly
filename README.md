{
  "name": "lowpoly-br-io-stackblitz",
  "version": "0.7.1",
  "private": true,
  "type": "module",
  "scripts": {
    "dev": "ts-node-dev --respawn --transpile-only --esm server/src/index.ts",
    "build": "tsc -p .",
    "start": "node dist/server/src/index.js"
  },
  "dependencies": {
    "@colyseus/schema": "^2.0.28",
    "@colyseus/ws-transport": "^0.16.0",
    "colyseus": "^0.16.0",
    "express": "^4.19.2"
  },
  "devDependencies": {
    "ts-node": "^10.9.2",
    "ts-node-dev": "^2.0.0",
    "typescript": "^5.6.3"
  },
  "stackblitz": {
    "startCommand": "npm run dev"
  }
}