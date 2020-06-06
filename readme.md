# tarot-eslint-config

Default ESLint configuration for [Tarot](https://github.com/codynova/tarot).

This package is automatically used in the Tarot `build` process unless you have provided a custom `eslintConfigPath`.

To use in your own custom configuration, install then extend this package in your eslint config:

```bash
yarn add --dev tarot-eslint-config
```

```jsonc
// .eslintrc
{
    "extends": [
        "tarot-eslint-config"
    ]
}
```