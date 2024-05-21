# Nomicsfoundation Hardhat Config

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/nomicsfoundation/hardhat-config.git
```

Move into the hardhat-config working directory

```sh
cd hardhat-config/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.19
$ tsdx test
 PASS  test/fraction.test.ts
 PASS  test/constants.test.ts
 PASS  test/token.test.ts

Test Suites: 1 skipped, 3 passed, 3 of 4 total
Tests:       3 skipped, 20 passed, 23 total
Snapshots:   0 total
Time:        0.869s, estimated 1s
Ran all test suites.
Done in 1.48s.
```
