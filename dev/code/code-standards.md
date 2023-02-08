# Coding Standards

## Content Outline

* Variables/Constant
* Functions
* Routes
* Code Formatting/Styling (Rails, React, NodeJS/TS)
* Code Versioning
* Error Statements (Rails, React, NodeJS/TS)
* Nested Conditions
* Comments

## Variables/Constants
* Use descriptive, meaningful names
* Avoid global variables and use appropriate scoping (local, instance, class, etc.)
* Use constants for values that don't change with constant keyword and upper case words separated by "_"
* Initialize variables at the earliest possible point

### Unique practices for React:
* Use camelCase Naming Convention for Variables and PascalCase for Components.

### Unique practices for Ruby on Rails:
* Minimize use of instance variables, use method-level variables where possible
* Avoid using class variables
* Use attr_accessor or attr_reader to define getters and setters for instance variables
* Follow snake_case for variables and methods, CamelCase for class names.
* Use ? suffix for predicate methods (return a boolean).

## Functions
### Rails:
* Use descriptive, meaningful names for functions
* Keep functions small and focused on a single responsibility
* Use snake_case for function names.
* Avoid using global functions, use class or module methods instead
* Use optional parameters to make functions more flexible
* Return early from functions to simplify the logic
* Use method chaining for readability and composability.

### React Project: 
* Use stateless functional components for simple UI logic.
* Pass data and event handlers as props to child components.
* Avoid using inline functions in render method, as it causes re-renders.
* Use useCallback or useMemo for optimized rendering with functional components.
* Make use of higher-order components or render props for code reuse.
* Use functional updates for updating state with functional components.
* Use arrow functions for concise syntax and implicit binding of this.
* Use async/await for handling asynchronous code in functional components.
* Consider using libraries such as Lodash for functional utility functions.
* Separate business logic from UI logic and implement in separate functions. 

## Routes
### Rails:
* Use RESTful routes for better organization and conventions.
* Use resources for standard CRUD operations.
* Use shallow nesting for routes with one-to-many associations.
* Keep routes shallow, avoid deep nesting.
* Use singular resource names for routes, avoid using plural names.
* Use member and collection routes for customizing routes.
* Keep routes simple and avoid using too many variables in the path.
* Use concerns for extracting common behavior in routes.
* Keep route names simple, avoid using complex names.
* Use namespaces for organizing routes into modules.

### React Project: 
* Use a library like React Router for routing.
* Use dynamic routing with parameters to handle routes with dynamic data.
* Use exact prop for matching routes exactly.
* Use nested routes for related resources.
* Use the switch component for rendering a single route.
* Use Switch component to render the first matching route.
* Keep routing logic in a separate module.
* Use link components instead of navigation through JavaScript code.
* Consider using named routes for better readability and maintainability.
* Use history.push or history.replace for programmatic navigation
* Use redirects for handling unauthorized access or error pages
* Consider using private routes for protected pages and components.
* Use lazy loading and code splitting for optimizing performance.

## Code Formatting/Styling
### Rails:
* We recommend to use rubocop for automated code linting and formatting.
* Use a consistent file structure, such as keeping controllers in the "app/controllers" directory and models in the "app/models" directory.
* Use modules to group related classes and concerns.
* Keep controllers thin, by delegating business logic to models and services.
* Keep models simple and focused, with clear responsibilities and a single source of truth.
* Use services and value objects to encapsulate complex business logic.
* Use concerns and helpers to keep logic organized.
### React
* We recommend to use ESLint for automated code linting and formatting.