# Fedimint UI Projects

## Quick start

1. Need Docker installed
1. From root dir run `docker-compose up`. This starts the fedimint backend.
1. Open a new shell, and `cd apps/gaurdian-ui`
1. Run `REACT_APP_FM_CONFIG_API="ws://127.0.0.1:18174" yarn dev`

## What's Inside

This project includes the following apps / packages:

### Apps

- `guardian-ui`: Web app experience for setting up and administering fedimints. This is used by the Fedimint guardians
- `gateway-ui`: Web app experience for managing Fedimint gateways. This is used by Gateway administrators

### Packages

- `ui`: Shared React UI component library for building Fedimint UI experiences
- `eslint-config`: Shared `eslint` configurations (includes `eslint-plugin-react` and `eslint-config-prettier`)
- `tsconfig`: Shared `tsconfig.json`s used throughout Fedimint UI apps

## Development

From root repo directory:

1. `yarn install` (First time only)
1. `yarn build`
1. You can run any of the following commands from repo root directory

> - `yarn test` - Tests all apps and packages in the project
> - `yarn build` - Build all apps and packages in the project
> - `yarn clean` - Cleans previous build outputs from all apps and packages in the project
> - `yarn format` - Fixes formatting in all apps and packages in the project

Alternatively, you can navigate to a specific app or package within `fedimint-ui/` directory and run it's respective development commands
