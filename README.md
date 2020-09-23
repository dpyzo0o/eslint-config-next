# eslint-config-next

This package includes the shareable ESLint configuration for a js/ts Next.js app.

## Installation

Note that you have to install all peer dependencies.

```bash
npm install --save-dev @dpyzo0o/eslint-config-next eslint babel-eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-import eslint-plugin-react eslint-plugin-react-hooks eslint-config-prettier
```

## Usage

Create a file named `.eslintrc.json` with following contents in the root folder of your project:

```json
{
  "extends": "@dpyzo0o/eslint-config-next"
}
```

That's it! You can override the settings from `@dpyzo0o/eslint-config-next` by editing the `.eslintrc.json` file. Learn more about [configuring ESLint](https://eslint.org/docs/user-guide/configuring) on the ESLint website.
