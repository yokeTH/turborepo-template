# Turborepo starter

Run the following command:

## Add ShadcnUI

```
pnpm dlx shadcn@latest add -c apps/template
```

## Generate new apps

```sh
pnpm exec turbo gen workspace --copy

# ❯ pnpm exec turbo gen workspace --copy
# turbo 2.5.6


# >>> Copy an existing workspace from "turborepo-template"

# ? What type of workspace should be added? app
# ? What is the name of the app? docs
# ? Which workspace should "docs" start from?   template
# ? Where should "docs" be added? apps/docs
# ? Add workspace dependencies to "docs"? Yes
# ? Select all dependencies types to modify for "docs" dependencies, devDependencies
# ? Which packages should be added as dependencies to "docs?   @repo/ui
# ? Which packages should be added as devDependencies to "docs?   @repo/eslint-config,   @repo/typescript-config
#
# AFTER THAT edit app portname
#
```
