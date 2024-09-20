# Design Patterns in React and Web Development

## Common Design Patterns in React

### 1. Container/Presentational Pattern

- **Description**: This pattern involves separating the component logic and presentation. We create two components: a Container (smart) component that manages state and a Presentational (dumb) component that only handles rendering.
- **Usage**: Commonly used to improve readability and reusability.

### 2. Higher-Order Components (HOCs)

- **Description**: An HOC is a function that takes a component and returns a new component. It's used to abstract shared code and enhance components.
- **Usage**: Useful for cross-cutting concerns like adding user authentication checks.

### 3. Render Props

- **Description**: This pattern allows sharing code between components using a prop whose value is a function.
- **Usage**: Used when multiple components need to share logic but not necessarily render the same UI.

### 4. Hooks

- **Description**: Hooks are functions that let you "hook into" React state and lifecycle features from function components.
- **Usage**: Used for adding stateful logic in function components like useState, useEffect, etc.

## Common Design Patterns in Web Development:

### 1. Singleton

- **Description**: Ensures a class has only one instance, and provides a global point of access to it.
- **Usage**: Commonly used in services like logging or database connection objects.

### 2. Factory

- **Description**: A pattern used to create objects without specifying the exact class of the object that will be created.
- **Usage**: Useful when the system needs to be independent of how its objects are created.

### 3. Observer

- **Description**: A pattern where an object, called the subject, maintains a list of its dependents, called observers, and notifies them of any state changes, typically by calling one of their methods.
- **Usage**: Useful for implementing distributed event-handling systems.

### 4. Module Pattern

- **Description**: The Module pattern encapsulates "privacy", state, and organization using closures. It provides a way of wrapping a mix of public and private methods and variables, protecting pieces from leaking into the global scope.
- **Usage**: Commonly used in JavaScript to keep pieces of code encapsulated from the global scope.
