## Getting Started

If you don't have [Expo CLI](https://expo.io/) installed, run this command to install expo:

```bash
npm install -g expo-cli
```

Install the libraries (Required Node > 12.13.0) 

```bash
yarn install

#or

npm install
```

Run iOS:

```bash
yarn run ios

#or

yarn run ios
```

Run Android:

```bash
yarn run android

#or

npm run android
```

## Api Used

I'm using the [Poke Api](https://pokeapi.co/) 

## Workflow

The branching model used is gitflow, this helps a lot with collaboration and scaling the development team.

### master

deployments to production

### develop

Developtment branch.

### feature/initial_setup

Adding tsconfig, precommiter and material ui.