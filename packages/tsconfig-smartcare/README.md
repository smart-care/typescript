# Smartcare TypeScript Config

## Usage

```bash
yarn add @smartcare/tsconfig --dev
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
