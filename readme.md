# tapas-countries

A ReactJS hook to get the country information.

## How to use it?

You can use the project in this way:

### Install
```bash
# with npm
npm install tapas-countries

# with yarn
yarn add tapas-countries
```

### Usage

- Import the package in your app:
```js
import {useCountry} from 'tapas-countries';
```
- Get the country information from the hook:
```js
const {loading, error, country} = useCountry('Republic Of India')'
```