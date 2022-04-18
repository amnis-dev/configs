# Amnis Configurations

Common ESLint configurations for Amnis projects.

## Installation

Install the configuration appropriate for the type of project.
### Node Project

Install configurations for a NodeJS application.

```sh
# NPM
npm install -D @amnis/tsconfig-node @amnis/eslint-config-node

# Yarn
yarn add -D @amnis/tsconfig-node @amnis/eslint-config-node
```

Extend in `.eslintrc.json/js`.

```json
{
  "extends": "@amnis/eslint-config-node"
}
```

Extend in `tsconfig.json`.

```json
{
  "extends": "@amnis/tsconfig-node"
}
```

### React Project

Install configurations for a React application.

```sh
# NPM
npm install -D @amnis/tsconfig-react @amnis/eslint-config-react

# Yarn
yarn add -D @amnis/tsconfig-react @amnis/eslint-config-react
```

Extend in `.eslintrc.json/js`.

```json
{
  "extends": "@amnis/eslint-config-react"
}
```

Extend in `tsconfig.json`.

```json
{
  "extends": "@amnis/tsconfig-react"
}
```