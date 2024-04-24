# Welcome

Please take the time to read through all of the sections below; we want you to do great! :rocket:

Feel free to reach out to your recruiting contact with any questions or concerns.

## Goal
Modify the provided Nuxt 3 app to match [this mock](https://www.figma.com/file/Nqtrx7PvY68U8FeNphzHDM/Untitled?type=design&node-id=0%3A1&mode=design&t=QrPxbJQ6qtH5BfBR-1) as closely as possible while utilizing best-practices to improve the codebase and implement the functional requirements outlined below.

- The provided exercise files are a starting point and they have room for improvement; feel free to modify
- Don't treat the mock as gospel -- if you see things that don't make sense, ask questions or implement what you think is right
- In the exercise you are utilizing a local API; however, code your submission as if you are using a production API, accounting for typical issues that can occur

### Links

- Figma Mock: <https://www.figma.com/file/Nqtrx7PvY68U8FeNphzHDM/Untitled?type=design&node-id=0%3A1&mode=design&t=QrPxbJQ6qtH5BfBR-1>

### API
- getUser: https://api.ganknow.com/v1/users/nickname/paddie?timezone=7
- getTimeline: https://api.ganknow.com/v1/posts?author=56e5e423-a0a5-44a9-a665-b73e5b12d7cd&perPage=20&page=1
- getTotalFollowers: https://api.ganknow.com/v1/users/follow-profile/follower/56e5e423-a0a5-44a9-a665-b73e5b12d7cd?count=true

## Functional Requirements
- [Vue 3](https://vuejs.org/) and TypeScript
- User should be able to view the name, a brief description, versions available, and other info shown in the mock for services
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
- Use SSR
- Caching endpoint response
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
