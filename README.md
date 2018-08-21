# eslint-config-nebulas-contract

> ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html) for the Nebulas smart contract style


## Installation

```
$ npm install --save-dev eslint eslint-plugin-nebulas-contract eslint-config-nebulas-contract
```


## Usage

Once the `eslint-config-nebulas-contract` package is installed, you can use it by specifying `nebulas-contract` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "nebulas-contract",
  "rules": {
    // Additional, per-project rules...
  }
}
```

### Using the `nebulas-contract` config with `eslint:recommended`

There are several rules in the [`eslint:recommended` ruleset](http://eslint.org/docs/rules/) that Google style is not opinionated about that you might want to enforce in your project.

To use Google style in conjunction with ESLint's recommended rule set, extend them both, making sure to list `google` last:

```js
{
  "extends": ["eslint:recommended", "nebulas-contract"],
  "rules": {
    // Additional, per-project rules...
  }
}
```

MIT © [yucopowo](https://github.com/yucopowo)

