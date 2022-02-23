# DogeEX_v2-Toolkit
 UI Toolkit of DogeEx v2

This repository is a monorepo manage with [yarn workspaces](https://classic.yarnpkg.com/en/docs/workspaces/) and [Lerna](https://lerna.js.org/). 

## Packages

- [pancake-uikit](https://github.com/pancakeswap/pancake-toolkit/tree/master/packages/pancake-uikit) : React components used to build the Pancake UI
- [eslint-config-pancake](https://github.com/pancakeswap/pancake-toolkit/tree/master/packages/eslint-config-pancake) : An ESLint config for pancake, with Typescript and Prettier support
- [pancake-profile-sdk](https://github.com/pancakeswap/pancake-toolkit/tree/master/packages/pancake-profile-sdk) : Handy functions to retrieve data for Pancakeswap Profile system
- [token-lists](https://github.com/pancakeswap/pancake-toolkit/tree/master/packages/token-lists) : Main PancakeSwap token list and tools to validate it

## How to use

- cd DogeEx-v2-Toolkit
- yarn
- copy directory /packages/pancake-uikit/dist 
- add above directory to main project (DogeEx-v2 NOT Toolkit) folder at /node_modules/@pancakeswap (you will need to overwrite existing dist directory)
