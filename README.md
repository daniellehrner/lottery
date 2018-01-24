# Lottery - smart contract example

This is an example project for a smart contract which can be deployed on the `Ethereum` network. The project includes automatic tests and a deployment script.

## Setup
Run the following command to install all required JavaScript packages

```
npm install
```

Create an `.env` file by copying `.env.example`

```
cp .env.example .env
```

Replace all the required values in the `.env` file with your own private data

## Deployment
After completing the setup you can deploy the contract with the following command

```
node deploy.sh
```

## Tests
The tests can be found in the `test` directory and can be executed with
```
npm run test
```
