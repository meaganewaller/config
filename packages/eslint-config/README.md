# @meaganewaller/eslint-config

The ESLint configuration for TypeScript projects by meeaganealler.

## Installation

Install the package via pnpm:

```bash
pnpm install --D @meaganewaller/eslint-config
npm install --save-dev @meaganewaller/eslint-config
yarn add --dev  @meaganewaller/eslint-config
```

## Usage

Extend the configuration in your ESLint config file:

```js
module.exports = {
  extends: ['@meaganewaller/eslint-config'],
}
```

## Configuration

The configuration includes the following plugins and extends:

- eslint:recommended
- plugin:react/recommended
- plugin:@typescript-eslint/recommended
- plugin:@typescript-eslint/eslint-recommended
- plugin:react-hooks/recommended
- plugin:jsx-a11y/recommended
- plugin:prettier/recommended
- simple-import-sort
- unused-imports

## License

This project is licensed under the [MIT License](LICENSE).
