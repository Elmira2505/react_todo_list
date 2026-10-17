#react 
VS Code Hotkeys for Creating React Components

If you want to quickly create a React functional component in VS Code, the easiest way is to use the ES7+ React/Redux/GraphQL/React-Native Snippets extension. Once installed, you can type a short trigger and hit Tab (or Enter) to auto-generate the component boilerplate.

Here are the most common snippet triggers:

rfce → React Functional Component with export default

import React from 'react';

export default function MyComponent() {
  return <div>MyComponent</div>;
}
rafce → React Arrow Function Component with export default

import React from 'react';

const MyComponent = () => {
  return <div>MyComponent</div>;
};

export default MyComponent;
rfc → React Functional Component (no default export)

import React from 'react';

function MyComponent() {
  return <div>MyComponent</div>;
}