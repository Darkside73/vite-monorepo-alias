# Vue 3 + Typescript + Vite + Monorepo path alias issue

- package-b uses package-a via yarn workspaces
- package-a creates alias "@" to its src directory (in tsconfig)
- vite resolves package-a's alias "@" as package-b
