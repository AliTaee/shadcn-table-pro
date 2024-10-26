# Shadcn Table Pro

Recipe and starter boilerplate for advanced React tables.

I agree with the shadcn author, and I quote them:

> Every data table or datagrid I've created has been unique. They all behave differently, have specific sorting and filtering requirements, and work with different data sources.

> It doesn't make sense to combine all of these variations into a single component. If we do that, we'll lose the flexibility that headless UI provides.

> So instead of a data-table component, I thought it would be more helpful to provide a guide on how to build your own.

Although there is a good base integration [recipe](https://ui.shadcn.com/docs/components/data-table) for Shadcn and TanStack Table, I prefer to build a more feature-rich solution. This approach allows you to use it as a foundation for your project, customize it, and adapt it based on your design needs.

````

## Development 🧑🏻‍💻

### Run storybook 📚

```bash
npm run storybook
# or
yarn run storybook
# or
pnpm storybook
````

### Run tests 🧪

For unit tests:

```bash
npm run test
# or
yarn test
# or
pnpm test
```

for running unit tests in watch mode:

```bash
npm run test:watch
# or
yarn test:watch
# or
pnpm test:watch
```

### Run Lint 🥸

```bash
npm run lint
# or
yarn run lint
# or
pnpm lint
```

### Run Prettier 🧹

```bash
npm run format
# or
yarn run format
# or
pnpm format
```

### Build 🗜️

```bash
npm run build
# or
yarn run build
# or
pnpm build
```

## Tools and Setup in this project: 🧰

- [React](https://react.dev/)
- [tanstack.com/table/](https://tanstack.com/table/): Supercharge your tables or build a datagrid from scratch for TS/JS, React, Vue, Solid, Svelte & Lit while retaining 100% control over markup and styles.
- [Rollup](https://rollupjs.org/): The JavaScript module bundler
- [Prettier](https://prettier.io/): Code formatter
- [Eslint](https://eslint.org/): Code Linter
- [TypeScript](https://www.typescriptlang.org/)
- [Storybook](https://storybook.js.org/): Storybook is a frontend workshop for building UI components and pages in isolation. Thousands of teams use it for UI development, testing, and documentation.
- [Jest](https://jestjs.io/): Run unit tests.
- [Testing library](https://testing-library.com/): Simple and complete testing utilities that encourage good testing practices.

## Learn More 📚

To learn more about setup, and this project, take a look at the following resources:

- [How to build a component library with React and TypeScript](https://blog.logrocket.com/how-to-build-component-library-react-typescript/)
- [Building Efficient npm Packages with React, TypeScript, and CSS Modules: A Comprehensive Guide](https://hackernoon.com/building-efficient-npm-packages-with-react-typescript-and-css-modules-a-comprehensive-guide)
- [How to Create and Publish React TypeScript npm Package With Demo and Automated Build](https://betterprogramming.pub/how-to-create-and-publish-react-typescript-npm-package-with-demo-and-automated-build-80c40ec28aca#7b1c)
- [Husky and lint-staged for pre-commit in React](https://dev.to/griseduardo/husky-and-lint-staged-for-pre-commit-in-react-39nd)
- [Rollup Config for React Component Library With TypeScript + SCSS](https://www.codefeetime.com/post/rollup-config-for-react-component-library-with-typescript-scss/)
