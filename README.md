# @colussi/prettier-config

[![npm version](https://badge.fury.io/js/@colussi%2Fprettier-config.svg)](https://badge.fury.io/js/@colussi%2Fprettier-config)[![CI](https://github.com/JonatanColussi/prettier-config/actions/workflows/main.yml/badge.svg)](https://github.com/JonatanColussi/prettier-config/actions/workflows/main.yml)

Shared [Prettier](https://prettier.io) configuration.

## Usage

**Install**:

```sh
$ npm install -D @colussi/prettier-config
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@colussi/prettier-config"
}
```

[Read more on sharing configurations.](https://prettier.io/docs/en/configuration.html#sharing-configurations)

## Philosophy

> By far the biggest reason for adopting Prettier is to stop all the on-going debates over styles.
>
> – [Prettier's Option Philosophy](https://prettier.io/docs/en/option-philosophy.html)

This configuration is intended to provide consistent, automatic formatting throughout a project and pairs well with [eslint-config](https://github.com/JonatanColussi/eslint-config).
