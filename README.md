# My basic prettier setup

I usually add use it, in small projects without Eslint

## Install Pretiier and Plugins

```sh
bun i -D prettier @trivago/prettier-plugin-sort-imports
```

## Package.json

```json
{
  "scripts": {
    "lint": "prettier --write ."
  }
}
```
