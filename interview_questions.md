    1. What is React, and how does it differ from other JavaScript frameworks/libraries?

    Answer: 
    - JavaScript library for building user interfaces. 
    - focuses on the efficient rendering of UI components by using a virtual DOM. 
    - Unlike other frameworks, React is only concerned with the view layer, making it highly adaptable and easily integrable with other tools.

    2. Explain the concept of Virtual DOM in React.

    Answer: 
    - The Virtual DOM is a lightweight, in-memory representation of the actual DOM elements. 
    - React uses it to optimize the updating process. When changes occur, React first updates the Virtual DOM, then compares it with the previous state to identify the minimal required changes. 
    - finally it updates only the necessary parts of the actual DOM, reducing rendering time and improving performance.

    What are React Hooks, and why were they introduced?

    Answer: 
    - React Hooks are functions that allow functional components to use state and lifecycle features previously available only in class components. 
    - They were introduced to simplify state management and side effects in functional components, making it easier to reuse logic across different components without the need for class syntax.

    What is JSX in React?

    Answer: 
    - JSX (JavaScript XML) is a syntax extension for JavaScript recommended by React. 
    - allows you to write HTML elements and components in a syntax similar to XML or HTML within JavaScript code. 
    - JSX makes React code more concise and readable, and it gets transpiled into JavaScript that React understands.

    Explain the difference between controlled and uncontrolled components in React forms.

    Answer: 
    - Controlled components are React components where form data is controlled by the state. 
    - Input elements receive their current value from the component's state and trigger changes through state handlers. 
    - In contrast, uncontrolled components allow form data to be handled by the DOM itself. 
    - Input elements in uncontrolled components rely on refs, and their values are accessed directly from the DOM when needed. 
    - Controlled components provide more control and predictability over form data.
   
    What is React and why is it used?

    Answer: 
    - React is a JavaScript library for building user interfaces. It's used for creating efficient, modular, and reusable UI components.

    Explain the purpose of useState hook in React.

    Answer: 
    - useState is a React hook used to add state to functional components, allowing them to manage and update local state.
    
    What is the significance of the useEffect hook in React?

    Answer: 
    - useEffect is used for handling side effects in functional components, such as data fetching, subscriptions, or manual DOM manipulations.
    Describe the key difference between props and state in React.

    Answer: 
    - Props are external inputs to a component, passed down from a parent component, while state is internal data that can be managed and updated within the component.

    How does React Router help in navigation within a React application?

    Answer: 
    - React Router is a library that enables navigation and routing in React applications, allowing for the creation of multi-page experiences with dynamic UI updates.
