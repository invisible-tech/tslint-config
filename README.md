# tslint-config

TypeScript Linting Rules based on our ES Linting Rules

# Install

```
yarn add -D @invisible/tslint-config
# or
npm install -D @invisible/tslint-config
```

# Usage

1. Add `"@invisible/tslint-config"` to `extends` on your `tslint.json` file:
```json
  // It should look something like:
  {
    "extends": [ "@invisible/tslint-config" ]
  }
```

2. Add missing development dependencies:
```
yarn add -D tslint typescript
```
