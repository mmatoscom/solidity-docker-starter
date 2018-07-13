![NodeFactory](banner.png)

# Solidity-Docker-Starter
![CircleCI branch](https://img.shields.io/circleci/project/github/NodeFactoryIo/solidity-docker-starter/master.svg)

## Requirements

Following software is required to be installed to use this repo:
 * [NodeJs](https://nodejs.org/en/) >= v8.4.0

## Usage

On first use of this repo, run `npm run init` which will install
all required dependencies for running tasks. Then run `npx run build` which will
build docker image.

Run `npx run` to see all available commands:
- contracts:clean                 - Delete contract artifacts
- contracts:deploy                - Run all missing migrations to deploy contracts to ethereum network. Command accepts param with id of network
- contracts:redeploy              - Run all migrations again to deploy contracts to ethereum network. Command accepts param with id of network
- contracts:compile               - Compiles all contracts
- contracts:test                  - Runs tests against contracts in docker. It accepts test name as optional argument
- clean                           - Removes all build directories and dependencies
- lint                            - Runs eslint on current project
- build                           - Builds new docker image

## Contribution

If this repository helped you, let us know by donating ETH to `0xbD9f96663E07a83ff18915c9074d9dc04d8E64c9` or feel free to contribute with more features!
