# Share components with Yarn workspaces

Install yarn
https://classic.yarnpkg.com/en/docs/install/

1. Install dependencies
```sh
yarn
```

2. Start development
```sh
# will boot up the 'frontend' and 'dashboard' applications
yarn dev
```

3. This will open the browser on http://localhost:8081 and http://localhost:8080

#### Modify the file `packages/common/src/components/Table.vue` to see changes live on both projects

#### Project structure
```sh
# common components for frontend apps
/packages/common

# frontend application
/packages/frontend

# other application for example
/packages/dashboard
```