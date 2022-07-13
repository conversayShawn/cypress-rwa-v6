# RWA version 6

This clone is specifically for Cypress v6 of the [Cypress Real World App](https://github.com/cypress-io/cypress-realworld-app)

## Getting Started

The Cypress Real-World App (RWA) is a full-stack Express/React application backed by a local JSON database ([lowdb]).

The app is bundled with [example data](./data/database.json) (`data/database.json`) that contains everything you need to start using the app and run tests out-of-the-box.

> 🚩 **Note**
>
> You can login to the app with any of the [example app users](./data/database.json#L2). The default password for all users is `s3cret`.  
> Example users can be seen by running `yarn list:dev:users`.

### Prerequisites

The only requirement for this project is to have [Node.js](https://nodejs.org/en/) **version 12** installed on your machine. Refer to the [.node-version](./.node-version) file for the exact version.

TypeScript will be added as a local dependency to the project, so no need to install it.

### Installation

```shell
yarn install
```

### Run the app

```shell
yarn dev
```

### Start Cypress

```shell
yarn cypress:open
```