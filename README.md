## Cartesi Calculator Pro

This repository contains the source code for the Cartesi Calculator Pro, a powerful tool for performing complex calculations. This application made use of [MathJS](https://mathjs.org/docs/getting_started.html) to solve complex algorithms.

## Installation

Docker

Docker is a platform that allows you to automate the deployment, scaling, and management of applications. It uses containerization to package up an application with all of its dependencies into a standardized unit for software development.

To install Docker, follow these steps [click to install Docker](https://docs.docker.com/get-docker/)

## Sunodo

Sunodo is a powerful tool for managing and deploying applications. To install Sunodo, follow these steps [click to install sunodo](https://docs.sunodo.io/guide/introduction/installing)

## Quick start

The subsequent commands will help install the Cartesi Calculator Pro.

```javascript
    git clone https://github.com/the-first-elder/Cartesi-calculator-pro-with-sunodo.git
    sunodo build
    sunodo run
```

Open a new terminal and input

```javascript
    sunodo send generic
    Select Foundry
    Use Default Rpc Url
    Use Default Wallet Mnemonic
    select any address
    use Default Dapp Address
    select string encoding and input complex maths example `3 + 2 * 5!` and boom!
```

Answer is in previously opened terminal

## Other complex calculation example

`2 / (2.3 + 0.7)` // 4 </br>
`12.7 cm to inch` // 5 inch </br>
`sin(45 deg) ^ 2` // 0.5 </br>
`9 / 3 + 2i` // 3 + 2i </br>
`det([-1, 2; 3, 1])` //-7 </br>
`sqrt(3^2 + 4^2)` //5

More can be found [HERE](https://mathjs.org/examples/index.html)

## To build the app.

`cd frontend-web-cartesi`

```shell
yarn install
yarn start
```

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Voucher Notes

To execute Vouchers, the voucher epoch must be finalized so the rollups framework generate the proofs.
As a reminder, you can advance time in hardhat with the command:

```shell
curl --data '{"id":1337,"jsonrpc":"2.0","method":"evm_increaseTime","params":[864010]}' http://localhost:8545
```
