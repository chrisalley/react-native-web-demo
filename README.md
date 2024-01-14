# React Native Web Demo

Install dependencies:

`pnpm install`

Run Expo app on the web browser with the following command:

`pnpm web`

Generate a deployable web app using the following command:

`npx expo export:web`

The above command will create static resources in the ./web-build directory, so you can test with serve:

```
cd web-build
npx serve
```

Run tests:

`pnpm test`
