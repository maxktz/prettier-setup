# My basic prettier setup

I usually add use it, in small projects without Eslint

## Installation

1. Install Pretiier and Plugins

    ```sh
    bun i -D prettier @trivago/prettier-plugin-sort-imports
    ```

2. Copy `.prettierrc` file

3. Add lint script to `package.json`

    ```json
    {
      "scripts": {
        "lint": "prettier --write ."
      }
    }
    ```
