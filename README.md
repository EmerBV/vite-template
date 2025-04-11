<h1 align="center">
  Vite React Template (by EmerBV)
</h1>

<p align="center">
  Template for creating React apps with TypeScript following best practices: Unit and end-to-end tests, Continuous Integration, and linting.
</p>

## ⚡ Using this Vite template

1. Create your project based on this template:
   - a) If you want to create a GitHub repository, we would recommend to use the GitHub "Use this template" button and clone your newly created repository
   - b) If you prefer to just create a local project, you can use [degit](https://github.com/Rich-Harris/degit):
     ```bash
     npx degit EmerBV/vite-template my-app
     ```
2. Update your project meta-information:
   - [ ] Update the [`package.json`](https://github.com/EmerBV/vite-template/blob/main/package.json):
     - [ ] Specify proper values for the `name`, `author` and `license` properties
     - [ ] Remove the `private` property if you plan to publish the app as a npm package
   - [ ] Change the author in [`LICENSE`](https://github.com/EmerBV/vite-template/blob/main/LICENSE)
   - [ ] Change the title in [`index.html`](https://github.com/EmerBV/vite-template/blob/main/index.html)
   - [ ] Replace the favicon in the [`public`](https://github.com/EmerBV/vite-template/blob/main/public) directory
   - [ ] Clean up this [`README.md`](https://github.com/EmerBV/vite-template/blob/main/README.md)
## ⚡ Run the app:
   1. `cd my-app`: Move to your project root directory
   2. `npm install`: Install all the project dependencies
   3. `npm start`: Start the development server on [localhost:3000](http://localhost:3000)

## ✅ Testing

### Unit tests

`npm run test`: Run unit tests with Jest and React Testing Library

### End-to-end tests

1. `npm start`: Start the development server on [localhost:3000](http://localhost:3000)
2. Run end-to-end tests with Cypress choosing one of the following options:
  - `npm run cy:open`: Open Cypress in dev mode
  - `npm run cy:run`: Execute Cypress in CLI

## 🔦 Linting

- `npm run lint`: Run linter
- `npm run lint:fix`: Fix lint issues

## 🌈 Tech Stack

- [TypeScript](https://www.typescriptlang.org)
- [ESLint](https://eslint.org) and [Prettier](https://prettier.io)
- [Jest](https://jestjs.io) with [React Testing Library](https://testing-library.com/docs/react-testing-library/intro) for the unit tests
- [Cypress](https://www.cypress.io) with [Testing Library](https://testing-library.com/docs/cypress-testing-library) for the end-to-end tests
- [GitHub Action Workflows](https://github.com/features/actions) set up to run tests and linting on push
- [Makefile](https://github.com/EmerBV/vite-template/blob/main/Makefile) for standardize how to run projects
- [Sass](https://sass-lang.com) to supercharge CSS with nested classes and more fun
- [.editorconfig](https://editorconfig.org) for sharing the IDE config

### 👻 Why not adding `.vscode` or `.idea` to the `.gitignore` template

These are folders created due to personal environment preferences. We should ignore these personal development environment preferences to be ignored using your global `.gitignore` file and leave the project `.gitignore` file as clean as possible, that is, only containing the project specific rules.

You can create a `.gitignore_global` file with rules that will apply to all your repositories with:

```bash
touch ~/.gitignore_global
git config --global core.excludesfile ~/.gitignore_global
```