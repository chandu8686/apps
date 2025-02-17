# @saleor/apps-ui

## 1.2.1

### Patch Changes

- fdabc51: Mapped app-sdk package to root library

## 1.2.0

### Minor Changes

- e8660e8: Added two new components: ButtonsBox, which is a simple grid wrapper for horizontal buttons and SkeletonSection which composes Macaw Skeletons and make them looking more like a layout
- e8660e8: Added Layout.AppSection and Layout.AppSectionCard components to build standard app layouts

## 1.1.8

### Patch Changes

- a81f061: Updated Macaw to pre-127
- fcc37e7: Remove clsx package from the projects no longer using it.

## 1.1.7

### Patch Changes

- 8b3d961: Updated Macaw UI to pre.118

## 1.1.6

### Patch Changes

- 261957f: Updated dependencies: vite, vitest, eslint, prettier, dotenv, turbo, syncpack, changesets, lint staged

## 1.1.5

### Patch Changes

- aa6fec1: Updated Macaw UI to pre-106

## 1.1.4

### Patch Changes

- 70cb741: Update Zod to 3.21.4
- e7c2d3a: Updated and ESLint dependencies
- 3c6cd4c: Updated the @saleor/app-sdk package to version 0.41.1.
- 6210447: Updated tRPC packages to 10.34.0

## 1.1.3

### Patch Changes

- 2d77bca: Updated Next.js to 13.4.8
- 6299e06: Update @saleor/app-sdk to 0.41.0

## 1.1.2

### Patch Changes

- f96563f: Fixed a missing text-decoration on a breadcrumb link.
- 860bac4: Updated @saleor/app-sdk to 0.40.1
- cb6ee29: Updated dependencies

## 1.1.1

### Patch Changes

- a8834a1: Unified graphql version to 16.6
- a8834a1: Unified graphql codegen packages
- a8834a1: Set exact app-sdk version
- a8834a1: Removed unnecessary duplicated dependencies from apps and moved them to shared and root (types, eslint rules)
- a8834a1: Updated dev dependencies - Typescript, Eslint and Turborepo
- 928c727: Updated @saleor/macaw-ui to 0.8.0-pre.95. This version introduces change in spacing scale, so there may be slight changes in spacing

## 1.1.0

### Minor Changes

- 24615cf: Added SemanticChip component that wraps MacawUI Chip with semantic variants: error, warning, success & default
- ba7c3de: Adds shared Breadcrumbs component. Each breadcrumbs item can be rendered with or without the href. The last item is automatically rendered without the href and with distinct styles.
- e751459: Added TextLink component that can work with Next router and AppBridge.dispatch

### Patch Changes

- f9ca488: Fixed TextLink color and style
