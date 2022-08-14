# Example TypeScript monorepo using NPM workspaces

Example project that uses NPM workspaces to create a Node.js TypeScript monorepo.

This project is the result of one of my [blog article](https://daveiscoding.com/nodejs-typescript-monorepo-via-npm-workspaces)s.

## Getting started

Install dependencies

```
npm i
```

Build the project

```
npm run build
```

## Run it

**CLI module**

```
npm start -w @fantastic/cli
```

**Web module**

```
npm start -w @fantastic/web
```
