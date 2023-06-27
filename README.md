# Repro: Gluestack Typescript Error in `@latest`

1. Clone this repository
2. `npx tsc` - See that there are no Typescript errors
3. `npm install @gluestack-ui/provider@latest @gluestack-ui/toast@latest`
4. `npx tsc` - See that Typescript cannot find declaration files

# Instructions used to create this example:

1. `npx create-expo-app -t expo-template-blank-typescript`
2. Follow Steps 1 & 2 in the
   [gluestack-ui Expo Installation instructions](https://ui.gluestack.io/docs/getting-started/install-expo)
3. `npm install @gluestack-ui/provider@0.1.4 @gluestack-ui/toast@0.1.9`
4. `npx tsc` - See there are no Typescript errors
