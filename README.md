# stylelint-config-lowmess

This [stylelint](https://stylelint.io) config contains rules specific to how [I](@lowmess) write my CSS.

To see the rules that this config uses, please read [the config itself](/index.js).

## Installation

```bash
npm install stylelint-config-lowmess --save-dev
```

## Usage

Create a `.stylelintrc` file at the base of your project:

```json
{
  "extends": "stylelint-config-lowmess"
}
```

### Extending the config

Simply add a `"rules"` key to your config, then add your overrides and additions there.

For example, to change the `indentation` to tabs:

```json
{
  "extends": "stylelint-config-lowmess",
  "rules": {
    "indentation": "tab"
  }
}
```
