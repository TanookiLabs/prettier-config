## Setup

```bash
yarn add --dev prettier @tanooki/prettier-config
```

update package.json's prettier field:

```json
{
  "prettier": "@tanooki/prettier-config"
}
```

## Development

- change the index.json
- bump version in package.json
- push to master

a github action will publish a new version of the package to npm.

