# @roadiehq/backstage-plugin-argo-cd-backend

## 1.1.1

### Patch Changes

- 773692a: Change default port of backend from 7000 to 7007.

  This is due to the AirPlay Receiver process occupying port 7000 and preventing local Backstage instances on MacOS to start.

## 1.1.0

### Minor Changes

- 1d256c6: Support multiple Argo instances using the app-selector annotation