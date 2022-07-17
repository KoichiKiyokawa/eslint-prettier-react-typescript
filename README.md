# @KoichiKiyokawa/eslint-config-prettier-react-typescript

## How to use
### 1. Install

npm
```bash
npm i -D https://github.com/KoichiKiyokawa/eslint-config-prettier-react-typescript#v0.0.2
```

or yarn
```bash
yarn add -D https://github.com/KoichiKiyokawa/eslint-config-prettier-react-typescript#v0.0.2
```

or pnpm
```bash
pnpm i -D https://github.com/KoichiKiyokawa/eslint-config-prettier-react-typescript#v0.0.2
```

### 2. Create `.eslintrc.yml`
```yml
extends: "@KoichiKiyokawa/eslint-config-prettier-react-typescript"
```

### 3. Set npm script
`package.json`
```json
"scripts": {
  "lint": "eslint 'src/**/*.{ts,tsx}' --ignore-path .gitignore && prettier --write . --ignore-path .gitignore"
}
```
