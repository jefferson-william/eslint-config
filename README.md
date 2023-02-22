# @jeffersonwilliammachado/eslint-config

<p>
  <img src="https://img.shields.io/npm/v/@jeffersonwilliammachado/eslint-config?style=flat-square&color=8257E5&labelColor=121214" alt="npm version" />
  <img alt="License" src="https://img.shields.io/github/license/jefferson-william/eslint-config?style=flat-square&color=8257E5&labelColor=121214">
</p>

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies

```
npm i -D eslint @jeffersonwilliammachado/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:

```
{
  "extends": "@jeffersonwilliammachado/eslint-config/react"
  // "extends": "@jeffersonwilliammachado/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.

## License

MIT License.