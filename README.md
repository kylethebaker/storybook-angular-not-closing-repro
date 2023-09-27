# Storybook not closing after building

This is fresh repo generated using:
- `npx @angular/cli@16 new` with scss as the style preprocessor
- `npx storybook@latest init` not using compodoc

To reproduce:
- run `npm run build-storybook` (or `ng run sb-not-closing:build-storybook`)
- build will complete with last line being `info => Output directory: /path/to/where-ever`
- command doesn't exit, though storybook-static directory contains working docs

