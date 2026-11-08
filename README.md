# React + TypeScript + Vite, with Prettier

## Install Prettier and add to Eslint

1. Install Prettier: https://prettier.io/docs/install

   ```bash
   npm i -D prettier
   ```

2. Install eslint-config-prettier: https://github.com/prettier/eslint-config-prettier#installation

   ```bash
   npm i -D eslint-config-prettier
   ```

   And add `eslintConfigPrettier` to the end of `eslint.config.js`

3. Create `.prettierrc` with configuration

   ```json
   {
     "tabWidth": 2,
     "useTabs": false,
     "singleQuote": true,
     "trailingComma": "all",
     "semi": true
   }
   ```
