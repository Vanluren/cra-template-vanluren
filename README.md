# Vanluren's  template
This template initializes a create-react-app project using an opinionated directory structure based on the [Atomic Design Framework](https://atomicdesign.bradfrost.com/) proposed by Brad Frost.

It adds: 
- Typescript
- Redux
- Styled-components


## Installation

``sh
npx create-react-app my-app --template vanluren

# or

yarn create react-app my-app --template vanluren
``


## Directory Structure


We try to follow the teachings of [Brad Frost](https://bradfrost.com/) and his ['Atomic Design'](https://atomicdesign.bradfrost.com/table-of-contents/).
An example of a react project using the atomic design principles [lives here](https://github.com/danilowoz/react-atomic-design)

```sh
| [root]
|-- src
    |-- components
        |-- atoms
            |-- ComponentName
                |-- index.ts
        |-- molecules
        |-- organisms
        |-- views/pages
        |-- templates
    |-- store
        |-- storeSlice
            |-- sagas.ts
            |-- actions.ts
            |-- reducers.ts
            |-- types.ts
            |-- index.ts
        |-- configuration.ts
    |-- services
        |-- api
            |-- index.ts
        |-- i18n
|-- public
    |-- assets
| tsconfig.json
| package.json
| README.md
```
