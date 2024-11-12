# Biome useImportType and Nest.js reproduction

## Reproduction Steps

1. Run `npm run start:dev` to make sure app starts without an errors
2. Run `npm run lint:write` or `biome lint --write`
3. Run `npm run start:dev` again and see that app breaks because AppService imports as type