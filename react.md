# [React](https://react.dev/) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/main/LICENSE) [![npm version](https://img.shields.io/npm/v/react.svg?style=flat)](https://www.npmjs.com/package/react)  [![(Runtime) Build and Test](https://github.com/facebook/react/actions/workflows/runtime_build_and_test.yml/badge.svg)](https://github.com/facebook/react/actions/workflows/runtime_build_and_test.yml) [![(Compiler) TypeScript](https://github.com/facebook/react/actions/workflows/compiler_typescript.yml/badge.svg?branch=main)](https://github.com/facebook/react/actions/workflows/compiler_typescript.yml) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://legacy.reactjs.org/docs/how-to-contribute.html#your-first-pull-request)

React is a JavaScript library for building user interfaces.
  

  * **Declarative**: Reacct makes it painless to create interactive UIs. Design simple views for each state in your application, and Recat will efficiently uodate and render just the right components when Your date changes. Declarative views make your code more predictable, simple to understand, and easier to debug.

  * **Component-Based**: Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in Javascript instead of templates, you can easily pass rich date through your app and keep the state out of the DOM.

  * **Learn Once, Write AnyWhere**: We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using [<u>**Node**</u>](https://nodejs.org/en) and power mobile apps using [<u>**React Native.**</u>](https://reactnative.dev/)

     [Learn how to use React in your project.](https://react.dev/learn) 

# Installation
------------------
 React has been designed for gradual adoption from the start, and you can use as little or as much React as you need:

* Use [<u>Quick Start</u>](https://react.dev/learn) to get a taste of React.
* [<u>Add React to an Exisiting Project</u>](https://react.dev/learn/add-react-to-an-existing-project) to use as little or as much React as you need.
* [<u>Create a New React App</u>](https://react.dev/learn/start-a-new-react-project) if you're looking for a powderful JavaScript toolchain.

# Documentation
-------
You can find the React documentation [<u>on the website.</u>](https://react.dev/)

Check out the [<u>Getting Started</u>](https://react.dev/learn) page for a quick overview.

# Examples
-------
```jsx
import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```

