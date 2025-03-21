# @backstage/plugin-sentry

## 0.3.20

### Patch Changes

- Updated dependencies
  - @backstage/plugin-catalog-react@0.4.5
  - @backstage/core-components@0.4.0
  - @backstage/catalog-model@0.9.1

## 0.3.19

### Patch Changes

- 0e7595d19: Do not show [No Type] when issue metadata includes title instead of type
- d8e4afc62: Render the statsFor property in sentry issues table
- Updated dependencies
  - @backstage/plugin-catalog-react@0.4.3
  - @backstage/core-components@0.3.2
  - @backstage/theme@0.2.10

## 0.3.18

### Patch Changes

- 8bedb75ae: Update Luxon dependency to 2.x
- 56c773909: Switched `@types/react` dependency to request `*` rather than a specific version.
- Updated dependencies
  - @backstage/core-components@0.3.1
  - @backstage/core-plugin-api@0.1.6
  - @backstage/plugin-catalog-react@0.4.2

## 0.3.17

### Patch Changes

- Updated dependencies
  - @backstage/core-components@0.3.0
  - @backstage/core-plugin-api@0.1.5
  - @backstage/plugin-catalog-react@0.4.1

## 0.3.16

### Patch Changes

- 9d40fcb1e: - Bumping `material-ui/core` version to at least `4.12.2` as they made some breaking changes in later versions which broke `Pagination` of the `Table`.
  - Switching out `material-table` to `@material-table/core` for support for the later versions of `material-ui/core`
  - This causes a minor API change to `@backstage/core-components` as the interface for `Table` re-exports the `prop` from the underlying `Table` components.
  - `onChangeRowsPerPage` has been renamed to `onRowsPerPageChange`
  - `onChangePage` has been renamed to `onPageChange`
  - Migration guide is here: https://material-table-core.com/docs/breaking-changes
- Updated dependencies
  - @backstage/core-components@0.2.0
  - @backstage/plugin-catalog-react@0.4.0
  - @backstage/core-plugin-api@0.1.4
  - @backstage/theme@0.2.9

## 0.3.15

### Patch Changes

- Updated dependencies
  - @backstage/plugin-catalog-react@0.3.0

## 0.3.14

### Patch Changes

- Updated dependencies
  - @backstage/core-components@0.1.5
  - @backstage/catalog-model@0.9.0
  - @backstage/plugin-catalog-react@0.2.6

## 0.3.13

### Patch Changes

- 48c9fcd33: Migrated to use the new `@backstage/core-*` packages rather than `@backstage/core`.
- Updated dependencies
  - @backstage/core-plugin-api@0.1.3
  - @backstage/catalog-model@0.8.4
  - @backstage/plugin-catalog-react@0.2.4

## 0.3.12

### Patch Changes

- 6c12f0ec6: Migrated the package from `timeago.js` to `luxon`. See #4278
- Updated dependencies
  - @backstage/plugin-catalog-react@0.2.3
  - @backstage/catalog-model@0.8.3
  - @backstage/core@0.7.13

## 0.3.11

### Patch Changes

- Updated dependencies [add62a455]
- Updated dependencies [cc592248b]
- Updated dependencies [17c497b81]
- Updated dependencies [704875e26]
  - @backstage/catalog-model@0.8.0
  - @backstage/core@0.7.11
  - @backstage/plugin-catalog-react@0.2.0

## 0.3.10

### Patch Changes

- 062bbf90f: chore: bump `@testing-library/user-event` from 12.8.3 to 13.1.8
- 675a569a9: chore: bump `react-use` dependency in all packages
- Updated dependencies [062bbf90f]
- Updated dependencies [10c008a3a]
- Updated dependencies [889d89b6e]
- Updated dependencies [16be1d093]
- Updated dependencies [3f988cb63]
- Updated dependencies [675a569a9]
  - @backstage/core@0.7.9
  - @backstage/plugin-catalog-react@0.1.6
  - @backstage/catalog-model@0.7.9

## 0.3.9

### Patch Changes

- c614ede9a: Updated README to have up-to-date install instructions.
- Updated dependencies [9afcac5af]
- Updated dependencies [e0c9ed759]
- Updated dependencies [6eaecbd81]
  - @backstage/core@0.7.7

## 0.3.8

### Patch Changes

- Updated dependencies [12d8f27a6]
- Updated dependencies [40c0fdbaa]
- Updated dependencies [2a271d89e]
- Updated dependencies [bece09057]
- Updated dependencies [169f48deb]
- Updated dependencies [8a1566719]
- Updated dependencies [9d455f69a]
- Updated dependencies [4c049a1a1]
- Updated dependencies [02816ecd7]
  - @backstage/catalog-model@0.7.3
  - @backstage/core@0.7.0
  - @backstage/plugin-catalog-react@0.1.1

## 0.3.7

### Patch Changes

- Updated dependencies [3a58084b6]
- Updated dependencies [e799e74d4]
- Updated dependencies [d0760ecdf]
- Updated dependencies [1407b34c6]
- Updated dependencies [88f1f1b60]
- Updated dependencies [bad21a085]
- Updated dependencies [9615e68fb]
- Updated dependencies [49f9b7346]
- Updated dependencies [5c2e2863f]
- Updated dependencies [3a58084b6]
- Updated dependencies [2c1f2a7c2]
  - @backstage/core@0.6.3
  - @backstage/plugin-catalog-react@0.1.0
  - @backstage/catalog-model@0.7.2

## 0.3.6

### Patch Changes

- f4c2bcf54: Use a more strict type for `variant` of cards.
- Updated dependencies [fd3f2a8c0]
- Updated dependencies [d34d26125]
- Updated dependencies [0af242b6d]
- Updated dependencies [f4c2bcf54]
- Updated dependencies [10a0124e0]
- Updated dependencies [07e226872]
- Updated dependencies [f62e7abe5]
- Updated dependencies [96f378d10]
- Updated dependencies [688b73110]
  - @backstage/core@0.6.2
  - @backstage/plugin-catalog-react@0.0.4

## 0.3.5

### Patch Changes

- 53d3e2d62: Export the plugin instance as `sentryPlugin`. The plugin instance is still exported as `plugin` as well, but it will be removed in the future.
- Updated dependencies [19d354c78]
- Updated dependencies [b51ee6ece]
  - @backstage/plugin-catalog-react@0.0.3
  - @backstage/core@0.6.1

## 0.3.4

### Patch Changes

- 019fe39a0: Switch dependency from `@backstage/plugin-catalog` to `@backstage/plugin-catalog-react`.
- Updated dependencies [12ece98cd]
- Updated dependencies [d82246867]
- Updated dependencies [7fc89bae2]
- Updated dependencies [c810082ae]
- Updated dependencies [5fa3bdb55]
- Updated dependencies [6e612ce25]
- Updated dependencies [025e122c3]
- Updated dependencies [21e624ba9]
- Updated dependencies [da9f53c60]
- Updated dependencies [32c95605f]
- Updated dependencies [7881f2117]
- Updated dependencies [54c7d02f7]
- Updated dependencies [11cb5ef94]
  - @backstage/core@0.6.0
  - @backstage/plugin-catalog-react@0.0.2
  - @backstage/theme@0.2.3
  - @backstage/catalog-model@0.7.1

## 0.3.3

### Patch Changes

- Updated dependencies [def2307f3]
- Updated dependencies [efd6ef753]
- Updated dependencies [593632f07]
- Updated dependencies [33846acfc]
- Updated dependencies [a187b8ad0]
- Updated dependencies [f04db53d7]
- Updated dependencies [a93f42213]
  - @backstage/catalog-model@0.7.0
  - @backstage/core@0.5.0
  - @backstage/plugin-catalog@0.2.12

## 0.3.2

### Patch Changes

- 88da267cc: Port to new composability API by exporting new `EntitySentryContent` and `EntitySentryCard` component extensions.
- Updated dependencies [9c09a364f]
  - @backstage/plugin-catalog@0.2.10

## 0.3.1

### Patch Changes

- 962d1ad66: Added configuration schema for the commonly used properties
- Updated dependencies [c911061b7]
- Updated dependencies [8ef71ed32]
- Updated dependencies [0e6298f7e]
- Updated dependencies [ac3560b42]
  - @backstage/catalog-model@0.6.0
  - @backstage/core@0.4.1

## 0.3.0

### Minor Changes

- 075d3dc5a: The plugin uses the `proxy-backend` instead of a custom `sentry-backend`.
  It requires a proxy configuration:

  `app-config.yaml`:

  ```yaml
  proxy:
    '/sentry/api':
      target: https://sentry.io/api/
      allowedMethods: ['GET']
      headers:
        Authorization:
          $env: SENTRY_TOKEN # export SENTRY_TOKEN="Bearer <your-sentry-token>"
  ```

  The `MockApiBackend` is no longer configured by the `NODE_ENV` variable.
  Instead, the mock backend can be used with an api-override:

  `packages/app/src/apis.ts`:

  ```ts
  import { createApiFactory } from '@backstage/core';
  import { MockSentryApi, sentryApiRef } from '@backstage/plugin-sentry';

  export const apis = [
    // ...

    createApiFactory(sentryApiRef, new MockSentryApi()),
  ];
  ```

  If you already use the Sentry backend, you must remove it from the backend:

  Delete `packages/backend/src/plugins/sentry.ts`.

  ```diff
  # packages/backend/package.json

  ...
      "@backstage/plugin-scaffolder-backend": "^0.3.2",
  -   "@backstage/plugin-sentry-backend": "^0.1.3",
      "@backstage/plugin-techdocs-backend": "^0.3.0",
  ...
  ```

  ```diff
  // packages/backend/src/index.html

    const apiRouter = Router();
    apiRouter.use('/catalog', await catalog(catalogEnv));
    apiRouter.use('/rollbar', await rollbar(rollbarEnv));
    apiRouter.use('/scaffolder', await scaffolder(scaffolderEnv));
  - apiRouter.use('/sentry', await sentry(sentryEnv));
    apiRouter.use('/auth', await auth(authEnv));
    apiRouter.use('/techdocs', await techdocs(techdocsEnv));
    apiRouter.use('/kubernetes', await kubernetes(kubernetesEnv));
    apiRouter.use('/proxy', await proxy(proxyEnv));
    apiRouter.use('/graphql', await graphql(graphqlEnv));
    apiRouter.use(notFoundHandler());
  ```

### Patch Changes

- Updated dependencies [2527628e1]
- Updated dependencies [1c69d4716]
- Updated dependencies [83b6e0c1f]
- Updated dependencies [1665ae8bb]
- Updated dependencies [04f26f88d]
- Updated dependencies [ff243ce96]
  - @backstage/core@0.4.0
  - @backstage/catalog-model@0.5.0
  - @backstage/theme@0.2.2

## 0.2.4

### Patch Changes

- 303c5ea17: Refactor route registration to remove deprecating code
- Updated dependencies [08835a61d]
- Updated dependencies [a9fd599f7]
- Updated dependencies [bcc211a08]
  - @backstage/catalog-model@0.4.0

## 0.2.3

### Patch Changes

- Updated dependencies [475fc0aaa]
- Updated dependencies [1166fcc36]
- Updated dependencies [1185919f3]
  - @backstage/core@0.3.2
  - @backstage/catalog-model@0.3.0

## 0.2.2

### Patch Changes

- 1722cb53c: Added configuration schema
- Updated dependencies [1722cb53c]
  - @backstage/core@0.3.1

## 0.2.1

### Patch Changes

- Updated dependencies [7b37d65fd]
- Updated dependencies [4aca74e08]
- Updated dependencies [e8f69ba93]
- Updated dependencies [0c0798f08]
- Updated dependencies [0c0798f08]
- Updated dependencies [199237d2f]
- Updated dependencies [6627b626f]
- Updated dependencies [4577e377b]
  - @backstage/core@0.3.0
  - @backstage/theme@0.2.1

## 0.2.0

### Minor Changes

- 28edd7d29: Create backend plugin through CLI

### Patch Changes

- Updated dependencies [819a70229]
- Updated dependencies [3a4236570]
- Updated dependencies [ae5983387]
- Updated dependencies [0d4459c08]
- Updated dependencies [482b6313d]
- Updated dependencies [e0be86b6f]
- Updated dependencies [f70a52868]
- Updated dependencies [12b5fe940]
- Updated dependencies [1c60f716e]
- Updated dependencies [144c66d50]
- Updated dependencies [a768a07fb]
- Updated dependencies [b79017fd3]
- Updated dependencies [6d97d2d6f]
- Updated dependencies [5adfc005e]
- Updated dependencies [93a3fa3ae]
- Updated dependencies [782f3b354]
- Updated dependencies [2713f28f4]
- Updated dependencies [406015b0d]
- Updated dependencies [82759d3e4]
- Updated dependencies [ac8d5d5c7]
- Updated dependencies [fa56f4615]
- Updated dependencies [ebca83d48]
- Updated dependencies [aca79334f]
- Updated dependencies [c0d5242a0]
- Updated dependencies [b3d57961c]
- Updated dependencies [3beb5c9fc]
- Updated dependencies [754e31db5]
- Updated dependencies [1611c6dbc]
  - @backstage/core@0.2.0
  - @backstage/catalog-model@0.2.0
  - @backstage/theme@0.2.0
