# Employee Directory React Project

#### [Description](#description) | [Demo](#demo) | [Getting Started](#getting-started) | [Requirements](#requirements) | [Bonuses](#bonuses)

---------

## Description:
Over the next few days, you and a partner will be building a React app similar to the demo seen below. This app will firm up your existing knowledge of the React basics (components, JSX, props, state, events) and also utilize newer skills like controlled forms, custom component methods, the `useEffect()` hook, and API calls. Each pair will collaborate on a shared GitHub repository, and each person should contribute roughly half of the code contained within the repository. Although you will be working most closely with your partner, you are both encouraged to work with the rest of the team to discuss strategy, debug issues, review code, etc.

Below you will see a demo of an Employee Directory app that allows searching and sorting of a list of employees, and the ability to add a new employee to the list. **Note that your app does not need to be an employee directory in particular:** you and your partner may choose to make a contact list app, a budget management app, a searchable pet adoption app, etc etc etc. So long as the app you create meets the [core requirements](#requirements) listed below, feel free to choose an idea that you and your partner are excited to build!

---------

## Demo:

![Employee Directory Functionality Demo](employee-directory-demo.gif)

[View larger version of demo here](https://watch.screencastify.com/v/9EB97BcHHvZw2y7D58UD).

---------

## Getting Started:

- [ ] Take time with your partner to read through the [core requirements](#requirements) below, and to choose an idea to fulfill these requirements.
- [ ] Next, build out simple wireframes for your app using [wireframe.cc](https://wireframe.cc/), [Figma](https://www.figma.com/) or a similar tool. Use these wireframes to determine how to divide your app up into modular components, and to determine how you and your partner can divide up the necessary tasks.
- [ ] Consider using [Trello](http://trello.com) to create a project board to track tasks, priorities, and deadlines, and for visibility into what each partner is working on. [See here](https://trello.com/b/WjhFXOdJ/demo-project-board) for an example of how one might be organized.
- [ ] One partner should create a GitHub repository for your app, and should add the other partner **AND** `scullenBitwise` as collaborators. After the repo is set up, work together to set up [branch protections](https://docs.github.com/en/enterprise-server@3.2/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches) and determine a game plan for Git branching.
- [ ] **All work should be done within branches, and code should only be moved to your `main`/`master` branch by way of partner-approved pull requests. As you work, do regular adds/commits to give yourself multiple "save points" just in case something goes wrong.**
- [ ] Use clear, descriptive, and professional commit messages. (This will make things easier if you ever have to revert to a prior commit, and it looks great to potential employers!)
- [ ] One partner should use create-react-app to generate a new React app for your app: `npx create-react-app project-name-here`. If you need help getting your project linked up to a GitHub repo, just ask! Once this code has been merged into the `main`/`master` branch, the other partner can clone the repo, create a branch, and get started developing!
- [ ] Use the demos provided in class for reference. [Here](https://github.com/scullenBitwise/react-apprenticeship) is a link to the full demo repo.
- [ ] Dig into the React or JavaScript documentation if you get stuck!
- [ ] When you run into a bug or other unexpected behavior, use your debugging tools wisely: read error messages critically, set breakpoints, use `console.log()` and watch variables, use your Google Fu, etc.
- [ ] Challenge yourself to use ES6 syntax whenever possible: arrow functions, destructuring, the spread operator, object property value shorthand, template literals, etc.

---------

## Requirements:

- [ ] Your app should have multiple components. Use props to pass data from parent components into child components to allow customization of the child components. (Sometimes it's easiest to start with one or two big components, and to break code out into smaller, more specific components after the core functionality is in place.)
- [ ] Your app should start with an array of data either contained in an in-project `.json` file, or should request data from an external API on initial render. This data should be saved in state.
- [ ] Your app should allow the user to add a new item by completing and submitting an HTML form.
- [ ] Your form should include at least one less traditional form field type: select menu, radio buttons, checkboxes, date input, etc.
- [ ] Use controlled form elements so that as soon as the values stored in the form fields change, the corresponding state value is updated. For this project, you and your partner should handle all form logic by hand and should not use React form libraries like `Formik` or `React Hook Form`.
- [ ] Your form's `submit` button should be disabled until the user has completed all of the required fields.
- [ ] Your app should use a table (or similar structure) to render the data in the app in an understandable fashion.
- [ ] Your app should have a search field that filters the data displayed to match the search term.
- [ ] Your app should allow sorting of the data on at least one field, both ascending and descending.
- [ ] Make your code as DRY (**D**on't **R**epeat **Y**ourself) as possible!

---------

## Bonuses:

- [ ] Add in detailed input validation, and display error messages and conditional error styling when appropriate.
- [ ] Implement functionality to allow deletion and/or editing of an item.
- [ ] Use localStorage or Firebase to store and update your app's data to allow data persistence.
- [ ] Practice using [Bitwise's official commit message format](https://github.com/Shift3/standards-and-practices/blob/main/standards/commits.md).
- [ ] Deploy your app to GitHub Pages, Netlify, or a similar service and share the url with your team so we can all try it!
- [ ] Write a detailed README.md file using best practices: [README Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
- [ ] Learn a different technique for styling in React! Consider tools like [Tailwind CSS](https://tailwindcss.com/), [Styled Components](https://styled-components.com/), [React Materialize](https://madewithreactjs.com/react-materialize), [Reactstrap](https://reactstrap.github.io/?path=/story/home-installation--page), etc.