# Setting Typescript

**tsconfig.json**

```json
{
  "compilerOptions": {
    "target": "esnext",
    "lib": ["es2017"],
    "allowSyntheticDefaultImports": true,
    "noUnusedLocals": true,
    "noUnusedParameters": true,
    "removeComments": false,
    "preserveConstEnums": true,
    "sourceMap": true,
    "allowJs": true,
    "skipLibCheck": true,
    "strict": false,
    "forceConsistentCasingInFileNames": true,
    "esModuleInterop": true,
    "module": "commonjs",
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "isolatedModules": false,
    "outDir": "dist",
    "baseUrl": "./server"
  },
  "mime": {
    "text/x-typescript": ["ts", "tsx"]
  },
  // "exclude": ["dist"],
  "include": ["**/*.ts"]
}
```
