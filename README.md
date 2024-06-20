# Andrelino Silva ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:

```
npm i -D eslint @andrelinos/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": [
    "@andrelinos/eslint-config/next",
    "plugin:tailwindcss/recommended",
    "next/core-web-vitals"
  ],
  "plugins": [
    "simple-import-sort"
  ],
}
```

### React (without Next.js)

Install dependencies:

```
npm i -D eslint @andrelinos/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": [
    "@andrelinos/eslint-config/react",
    "plugin:tailwindcss/recommended"
  ],
  "plugins": [
    "simple-import-sort"
  ]
}
```

### Node.js

Install dependencies:

```
npm i -D eslint @andrelinos/eslint-config
```

Inside `.eslintrc.json`

```
{
  "extends": "@andrelinos/eslint-config/node",
  "plugins": [
    "simple-import-sort"
  ]
}
```
