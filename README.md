# Bolideai Microservice Share State

Provider for passing states between micro-frontends in Module Federation

## Installation

```sh
npm i @bolideai/mf-shared-state
```

## Usage

In parent application:
```js
import { ShareContextProvider } from '@bolideai/mf-shared-state';

<ShareContextProvider.Provider value={{ key: 12345, time: Date.now() }}>
    ...
</ShareContextProvider.Provider>

```

In any child application:
```js
import { ShareContextProvider } from '@bolideai/mf-shared-state';

const { key, time } = React.useContext(ShareContextProvider);
```

## Build and update

1. Install dependencies:
```sh
npm install
```
2. Make changes
3. Build:
```sh
npx webpack
```

## Author
Dubov V.
vitaliy.dubov@searchanise.io 
