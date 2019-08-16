# Smartcare TypeScript Config

## Usage

This repository is distributed via Smartcare's npm registry. Add the following to your projects `.yarnrc` file:

```
"@smart-care:registry" "https://npm.pkg.github.com"
```

```bash
yarn add @smart-care/tsconfig --dev
```

Then in your project's `tsconfig.json`:

```json
{
  "extends": "./node_modules/@smartcare/tsconfig/tsconfig.json"
}
```

## What's inside?

```json
{
  "compilerOptions": {
    "allowSyntheticDefaultImports": true,
    "allowUnreachableCode": false,
    "downlevelIteration": true,
    "esModuleInterop": true,
    "forceConsistentCasingInFileNames": true,
    "importHelpers": true,
    "jsx": "react",
    "moduleResolution": "node",
    "noFallthroughCasesInSwitch": true,
    "noImplicitAny": true,
    "noImplicitReturns": true,
    "noImplicitThis": true,
    "noUnusedLocals": true,
    "pretty": true,
    "removeComments": true,
    "sourceMap": true,
    "strict": true,
    "strictNullChecks": true
  }
}
```

---

MIT License
