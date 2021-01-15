# REACT STARTER KIT
dear future self, use these setting / instructions to help yourself set up your project faster!

## NPM
`` npm init -y ``

## GIT
`` git init ``

### .gitignore

```
*.idea/
*.iml
node_modules/
.DS_Store
.cache/
dist/
coverage/
.vscode/
.env
```

## REACT
`` npm install react react-dom ``

## ESLINT
``
npm install --save-dev prettier eslint eslint-config-prettier eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y babel-eslint 
``

## .eslintrc.json
```json
{
  "extends": [
    "eslint:recommended",
    "plugin:react/recommended",
    "plugin:jsx-a11y/recommended",
    "plugin:import/errors",
    "prettier",
    "prettier/react"
  ],
  "plugins": [
    "react",
    "jsx-a11y",
    "import"
  ],
  "parserOptions": {
    "ecmaVersion": 2018,
    "sourceType": "module",
    "ecmaFeatures": {
      "jsx": true
    }
  },
  "rules": {
    "react/prop-types": 0,
    "no-console": 1
  },
  "env": {
    "es6": true,
    "browser": true,
    "node": true
  },
  "settings": {
    "react": {
      "version": "detect"
    }
  }
}
```

## NPM SCRIPTS
assuming you have parcel-bundler installed globally
`` npm install -g parcel-bundler ``

```JSON
{
  "scripts": {
    "dev": "parcel src/index.html"
  }
}
```
