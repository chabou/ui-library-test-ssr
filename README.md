How this project was made:

```
npx create-next-app ui-library-test-ssr
yarn add @blablacar/ui-library
vim pages/index.js
yarn dev
```

Result http://localhost:3000: No SSR (first render hasn't any style)

Edit `package.json` and set `4.0.0` as version for `@blablacar/ui-library`

`yarn && yarn dev`

Result http://localhost:3000: SSR
