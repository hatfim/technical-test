# Welcome

Please take the time to read through all of the sections below; we want you to do great! :rocket:

Feel free to reach out to your recruiting contact with any questions or concerns.

## Goal
Modify the provided Nuxt 3 app to match [this mock](https://www.figma.com/file/Nqtrx7PvY68U8FeNphzHDM/Gank-Technical-Test) as closely as possible while utilizing best-practices to improve the codebase and implement the functional requirements outlined below.

- The provided exercise files are a starting point and they have room for improvement; feel free to modify
- Don't treat the mock as gospel -- if you see things that don't make sense, ask questions or implement what you think is right
- In the exercise you are utilizing a local API; however, code your submission as if you are using a production API, accounting for typical issues that can occur

### Links

- Figma Mock: <https://www.figma.com/file/Nqtrx7PvY68U8FeNphzHDM/Gank-Technical-Test>
- Profile page reference <https://ganknow.com/paddie>
- Profile feed page reference <https://ganknow.com/paddie?tab=feed>
- Feed details page: <https://ganknow.com/post/9f76c755-3d8b-4899-9350-5b05d911bcc3>

### API
- getUser: <https://api.ganknow.com/v1/users/nickname/paddie?timezone=7>
- getTimeline: <https://api.ganknow.com/v1/posts?author=56e5e423-a0a5-44a9-a665-b73e5b12d7cd&perPage=20&page=1>
- getTotalFollowers: <https://api.ganknow.com/v1/users/follow-profile/follower/56e5e423-a0a5-44a9-a665-b73e5b12d7cd?count=true>

## Functional Requirements
- [Vue 3](https://vuejs.org/) and TypeScript
- User should be able to view the user profile, feed timeline, and other info shown in the mock for profile page
- User should be able to click on a feed to view more details
- User should be able to paginate through feed
- The button doesn't have to be operable  -- interacting with this elements could do nothing, could be fully implemented (stretch goal), or something in between
- Please update the `README` in the project with a section to describe your design considerations, assumptions, and trade-offs made during this exercise. Also feel free to include any notes about your submission


## Additional Considerations (if applicable)

- The UI should be responsive and look great at different browser viewport sizes
- Pixel-perfect implementation
- Routing and views (e.g. navigating to timeline)
- State management with [Pinia](https://pinia.vuejs.org/)
- [Component Tests and/or Unit Tests](#run-component-and-unit-tests-with-vitest-and-optionally-vue-test-utils)
- Utilize SSR (Server-Side Rendering).
- Implement caching system
- Other items covered in your profile page


## Evaluation

We will review your code for quality and your ability to talk through it, how you approach the UI, and what tradeoffs you make. Specifically we'll be looking at the following:

- How closely your implementation matches the design along with the other [Functional Requirements](#functional-requirements)
- Code quality, including appropriate componentization and modularity
- TypeScript usage
- Coding (and Vue) best-practices
- The project should pass type checking and build successfully
- How you dedicate the allotted time to focus on your strengths
- Test coverage, if applicable

## How to submit the project

You have up to a week to complete the exercise, but we don't expect you to spend more than a few hours on it.

When it's ready, please send your recruiter a link to the source code in a GitHub repository (no Pull Requests).

---
## Project Setup

### Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

### Clone the repository

```sh
git clone git@github.com:hatfim/technical-test.git
```

### pnpm

This repository uses [`pnpm`](https://pnpm.io) rather than `npm` or `yarn`. [See here for instructions on installing pnpm](https://pnpm.io/installation).

### Install dependencies

```sh
pnpm install
```
### Compile and Hot-Reload for Development

Start the the Nuxt app:

```sh
pnpm dev
```
### Linting and fixing the code

#### ESLint

```sh
# Run the linter
pnpm lint

# Run javascript specific linter
pnpm lint:js

# Run prettier lint check
pnpm lint:prettier

# Fix linting errors
pnpm lintfix
```

### Run Component and Unit Tests with [Vitest](https://vitest.dev/) and optionally [Vue Test Utils](https://test-utils.vuejs.org/)

Component and unit test files must be located in the `/components` directory and have a filename format of `*.spec.ts`. In the starter project, see `src/components/StarterHeading.spec.ts` for an example.

```sh
# Run tests
pnpm test

# or run the tests in the Vitest UI
pnpm test:open
```
### Build and Minify for Production

```sh
pnpm build
```

### Preview your built application

First, you'll need to build the app

```sh
pnpm start
```

Now run the `preview` command

```sh
pnpm preview
```
