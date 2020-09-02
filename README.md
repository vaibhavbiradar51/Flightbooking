

## Prerequisites

* NodeJS 10+
* npm 6+
* truffle 4.1.13+
* ganache-cli 6.1.6+
* browser with MetaMask connected to ganache

## How to run it

1. Clone the repository and navigate to it
```
cd flight-tickets
```

2. Install dependencies:

```
npm install
```

3. Run Ganache:

```
ganache-cli
```

Make sure it's listening at `127.0.0.1:8545`.

3. Compile the contracts:

```
truffle compile
```

4. Deploy the contracts

```
truffle migrate
```

5. *This step is optional.* Populate the contract with sample data. Do it if you want to have some data to play with. Otherwise you can add all airlines and tickets by yourself.

```
npm run populate
```

If you want to change the sample data, it's configured in `sample-data.json`.

6. Run the frontend

```
npm run start
```

