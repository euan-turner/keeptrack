# ts_react_tutorial

**Following [Hands on React](https://handsonreact.com/docs/labs/react-tutorial-typescript)**

![TS and React](md_images/cover.png)

## Fundamentals

---

- [x] Lab 1: Creating a New Project
- To setup application: `npx create-react-app app_name --template typescript --use-npm`

---

- [x] Lab 2: Running Your Project
- To view live changes:`npm start`

---

- [x] Lab 3: Styles Using CSS
- To add mini css: `npm install mini.css@3.0.1`
- To apply mini css to ***src\index.css***: `@import '../node_modules/mini.css/dist/mini-dark.min.css';`

---

- [x] Lab 4: Your First Component
- Import component and use: `<ComponentName \>`

---

- [x] Lab 5: Creating Data Structures

---

- [x] Lab 6: Passing Data into a Component
- Use props to pass data into a component

---

- [x] Lab 7: Displaying List Data
- Use .map to create a component for each list element

---

- [x] Lab 8: More Reusable Components
- Subcomponents should be extracted to be more reusable where appropriate

---

- [x] Lab 9: Responding to an Event
- Define event handler within component, assign to HTML tag handler attribute

---

- [x] Lab 10: Create a Form
- Forms require slight changes from HTML to React syntax

---

- [x] Lab 11: Communicating from Child to Parent Component
- Events can also be handled by a parent, passing the handler as a prop to the child

---

- [x] Lab 12: Hiding and Showing Components
- State is used to maintain information about a component over function calls
- `useState({})` returns a `[state, setter]` list that can be destructured
- State is local to the function component

---

- [x] Lab 13: More Component Communication

---

- [x] Lab 14: Multiple Levels of Component Communication
- Event handlers can be passed down as props through multiple levels of a hierarchy

---

- [x] Lab 15: Form Values to State

---

- [x] Lab 16: Form Validation
- Apply validation rules to form inputs before submission
- Use div to show error message next to entry

---

- [x] Lab 17: Setup Backend REST API
- To install REST API server: `npm install json-server@0.16.2`
- Add `"api": "json-server api/db.json --port 4000"` to ***package.json*** scripts
- Have api directory with ***db.json*** in app root directory
- Use `npm run api` to run api, must be done whenever trying to run on localhost

---

- [x] Lab 18: HTTP GET
- Check for error messages on GET request
- Convert JSON in ***db.json*** to object
- Use state and hooks to control requests

---

- [x] Lab 19: HTTP PUT
- Put data to ***db.json*** in similar way to getting
- Use in save project function in main page

---

- [x] Lab 20: Router Basics
- Run `npm install react-router-dom`
- This provides support for navigation around multiple pages

---

- [x] Lab 21: Route Parameters
- Use `<Link>` from react-router-dom to make components hyperlinks
- Routes must be specified in `<Routes>` in ***app.tsx***

---

- [x] Lab 22: Build & Deploy
- Run `npm install -g serve` to install serve
- Run `npm run build` to create deployment build
- Run `serve -s build` to serve a local single page application
- Look at [Vercel](https://vercel.com/#get-started) for deploying backend pages

## Redux

- [x] Lab 23: Redux Install
- To install redux, run
  - `npm install redux react-redux redux-devtools-extension redux-thunk`
  - `npm install --save-dev @types/react-redux`
- Create a ***state.ts*** file to setup redux

---

- [x] Lab 24: Redux Actions & Reducer
- Define types for each action with the database in ***projectTypes.ts***
- Dispatch matching type for each action outcome in ***projectActions.ts***
- Reduce each action to a new state in ***projectReducers.ts***
- Configure reducer and states in ***state.ts***

---

- [ ] Lab 25: Redux with React

Testing

- [ ] Testing Lab 1: First Component Tests
- [ ] Testing Lab 2: Snapshot Tests
- [ ] Testing Lab 3: More Testing Components
- [ ] Testing Lab 4: Nested Components
- [ ] Testing Lab 5: Container Components
- [ ] Testing Lab 6: Testing Forms
- [ ] Testing Lab 7: Action Tests
- [ ] Testing Lab 8: Reducer Tests
- [ ] Testing Lab 9: API Tests
