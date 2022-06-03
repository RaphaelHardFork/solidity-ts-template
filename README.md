# Solidity TypeScript Template

![](https://img.shields.io/badge/Node.js-v16.15.0-blue)

## After cloning

```
yarn
forge update
```

Then add a `.env` file following the `.env.exemple` file

## Using

Create contracts in `src`, write unit tests in **Solidity** using [Foundry](https://book.getfoundry.sh/forge/writing-tests.html) in `src/test` or in **JS/TS** in `test`.

Then deploy with scripts, you can use `deployed` function to save a track of your deployed contract in `deployed.json`
