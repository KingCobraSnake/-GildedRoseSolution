Please check gilded-rose.ts for my additions and use mocha's test with  npm run test:mocha .


additons example:   //MY ADDITION: Quality reduction added for "conjured" materials.
# Gilded Rose

This is the Gilded Rose kata in TypeScript.

## Getting started

Install dependencies

```sh
npm install
```

## Running app
_You may need to install `ts-node`_

```sh
npx ts-node test/golden-master-text-test.ts
```

Or with number of days as args:
```sh
npx ts-node test/golden-master-text-test.ts 10
```

## Running tests

To run all tests

### Jest way

```sh
npm run test:jest
```

To run all tests in watch mode

```sh
npm run test:jest:watch
```

### Mocha way

```sh
npm run test:mocha
```
