# javascript interview resources

This Repository contains Theoretical as well as coding questions some are repeated as well.

## CSS Interview Questions
➡️ Explain the difference between inline, internal, and external CSS.<br>
    Inline CSS is applied directly within HTML elements, internal CSS is placed in the head section of an HTML document, and external CSS is 
  stored in separate CSS files and linked to HTML documents. <br><br>
➡️ What are the different types of CSS selectors?<br>
    CSS selectors include element selectors, class selectors, ID selectors, attribute selectors, and pseudo-class selectors.<br><br>
➡️ How do you apply CSS styles to specific elements based on their class or ID?<br>
    To apply CSS styles to specific elements based on their class, use the class selector (e.g., ".classname") and for specific elements 
  based on their ID, use the ID selector (e.g., "#elementID").<br><br>
➡️ What is the box model in CSS and how does it work?<br>
    The box model in CSS defines how elements are rendered, including content, padding, border, and margin.<br><br>
➡️ How do you center an element horizontally and vertically in CSS?<br><br>
    To center an element horizontally, use "margin: 0 auto," and to center it vertically, use "display: flex; align-items: center; justify- 
  content: center."<br><br>
➡️ What are pseudo-classes and pseudo-elements in CSS?<br>
  Pseudo-classes select elements based on their state or position, while pseudo-elements style specific parts of elements (e.g., :hover, 
  :first-child, ::before).<br><br>
➡️ Explain the concept of specificity in CSS.<br>
  Specificity determines which CSS rules take precedence when multiple rules target the same element, based on the selectors used.<br><br>
➡️ What is the difference between margin and padding in CSS?<br>
  Margin is the space outside the border of an element, while padding is the space between the content and the border of an element.<br><br>
➡️ How do you create a responsive layout in CSS?<br>
  Create a responsive layout by using media queries, relative units (such as percentages), and CSS grid or flexbox.<br><br>
➡️ What are media queries in CSS and how do they work?<br>
  Media queries allow CSS rules to be applied based on the characteristics of the device or browser, such as screen width or device 
  orientation.<br><br>
➡️ How do you handle browser compatibility issues in CSS?<br>
  Handle browser compatibility by using CSS feature detection, vendor prefixes, and polyfills.<br><br>
➡️ What is the difference between absolute and relative positioning in CSS?<br>
  Absolute positioning removes an element from the normal flow and positions it relative to its containing element, while relative 
  positioning positions an element relative to its normal position in the document flow.<br><br>
➡️ How do you create a CSS animation or transition?<br>
  CSS animations and transitions can be created using keyframes and the animation or transition properties, respectively.<br><br>
➡️ Explain the concept of flexbox in CSS and how it can be used for layout.<br>
  Flexbox is a CSS layout module that provides a flexible way to arrange and align elements within a container.<br><br>
➡️ What is the purpose of CSS preprocessors like Sass or Less?<br>
  CSS preprocessors like Sass or Less enhance CSS by adding features such as variables, nesting, and mixins.<br><br>
➡️ How do you optimize CSS for performance?
  Optimize CSS performance by minimizing file size, reducing the number of HTTP requests, and using efficient selectors and property values.<br><br>
➡️ What is the difference between CSS grid and flexbox?
  CSS grid is a two-dimensional layout system, while flexbox is a one-dimensional layout system primarily used for arranging elements in a 
  single row or column.<br><br>
➡️ How do you handle CSS specificity conflicts?
  Handle CSS specificity conflicts by using more specific selectors or by using !important, although it is generally recommended to avoid 
  !important.<br><br>
➡️ Explain the concept of CSS vendor prefixes and why they are used.
  CSS vendor prefixes are used to add browser-specific prefixes to CSS properties and values to ensure compatibility with different browser 
  versions and implementations. <br><br>

## Javascript Interview Questions
➡️ What are the different data types in JavaScript?<br>
   JavaScript has several data types including number, string, boolean, object, null, undefined, symbol, and bigint.<br><br>
➡️ Explain the concept of hoisting in JavaScript.<br>
  Hoisting is a JavaScript behavior where variable and function declarations are moved to the top of their scope during the compilation phase.<br><br>
➡️ What is the difference between null and undefined in JavaScript?<br>
  null represents the intentional absence of any object value, while undefined indicates the absence of a defined value.<br><br>
➡️ How does prototypal inheritance work in JavaScript?<br>
  Prototypal inheritance allows objects to inherit properties and methods from a prototype object, forming a chain of prototypes.<br><br>
➡️ What are closures in JavaScript and how are they used?<br>
   Closures are functions that have access to variables from their outer (enclosing) function scope, even after the outer function has 
   finished executing.<br><br>
➡️ Explain the concept of event delegation in JavaScript.<br>
   Event delegation is a technique where event handlers are attached to a parent element instead of individual child elements, leveraging 
   event bubbling to handle events.<br><br>
➡️ How does the "this" keyword work in JavaScript?<br>
   The "this" keyword refers to the context in which a function is executed, determined by how the function is called.<br><br>
➡️ What are higher-order functions in JavaScript?<br>
  Higher-order functions are functions that can take other functions as arguments or return functions as results.<br><br>
➡️ Explain the difference between synchronous and asynchronous programming in JavaScript.<br>
  Synchronous programming executes code sequentially, blocking further execution until a task is complete, while asynchronous programming 
  allows multiple tasks to run concurrently without blocking.<br><br>
➡️ How do you handle errors in JavaScript? What is the purpose of try-catch blocks?<br>
  Errors in JavaScript can be handled using try-catch blocks, which catch and handle exceptions that occur during the execution of a block 
  of code.<br><br>
➡️ What are the different ways to create objects in JavaScript?<br>
   Objects in JavaScript can be created using object literals, constructor functions, and the "class" keyword introduced in ES6.<br><br>
➡️ Explain the concept of callback functions in JavaScript.<br>
  Callback functions are functions that are passed as arguments to other functions and are invoked at a later time or when a certain 
  condition is met.<br><br>
➡️ What is the difference between let, const, and var in JavaScript?<br>
  let and const are block-scoped variables introduced in ES6, while var is function-scoped and can be redeclared and reassigned.<br><br>
➡️ How does the event loop work in JavaScript?<br>
  The event loop is a mechanism in JavaScript that handles asynchronous operations by placing them in a queue and executing them in a 
  single-threaded manner.<br><br>
➡️ What are arrow functions in JavaScript? How do they differ from regular functions?<br>
  Arrow functions are a concise syntax for creating functions in JavaScript and they have a lexical "this" binding, unlike regular 
  functions that bind "this" dynamically.<br><br>
➡️ Explain the concept of closures and their practical uses.<br>
  Closures are functions bundled with their lexical environment, and they are used for encapsulation, private variables, and data persistence.
  <br><br>
➡️ What is the purpose of the bind, call, and apply methods in JavaScript?<br>
  bind, call, and apply are methods that allow explicit control over the "this" value in function execution, binding a specific object as the function's context
  <br><br>
➡️ How do you handle asynchronous operations in JavaScript? What are Promises and async/await?<br>
  Asynchronous operations in JavaScript are commonly handled using Promises or async/await syntax, providing a more readable and structured way to work with asynchronous code.
  <br><br>
➡️ Explain the concept of debouncing and throttling in JavaScript.<br>
  Debouncing and throttling are techniques used to limit the frequency of a function's execution, particularly useful for optimizing performance in event-driven scenarios.
   <br><br>
➡️ What are the different ways to manipulate the DOM in JavaScript?  <br>
  The DOM can be manipulated using methods like getElementById, querySelector, createElement, appendChild, and modifying element properties and attributes.
  <br><br>
## When and what have to use in Frontend One liner
-  Deal with Asynchronous Data - Async/Await ( Better Code readability and error handling)
- Support Internationalization - i18next
- Ensure Performance of application- Browser Performance API
- Testing Component and business logic- Jest and RTL 
- Code style and prevent bugs- Linters and formatters like ESLINT, Prettier
- Frontend accessible to all users- Follow WCAG guideline and tools for check accessibility compliance
- Maintain code quality and enforece coding standard - static type checker like typescript and linters like ESLint
- Deal with user-intensive application - Lazy loading for better peerformance
- Prevent blocking of UI thread - Web workers 
- Responsive design- Mobile-first approach with media queries
- Make website accessible - Use ARIA attributes and Semantic HTML
- Real-time data update- Websockers or Server-sent events
- seamless navigation between different part of application- client-side routing
- Optimize large list of table in UI- Windowing
- form validation and data collection- Formik, react-hook-form
- System has component-based architecture- Component composition
- If need to store data on client side- Local storage, cookie, indexedDB
- reduce intial load time - code spitting
- Work offline- implement service worker and build PWA
- dealing with API- GraphQL for better fetch data
- frequent style changes based on prop- css-in-js libraries
- multiple similar component- higher order component or render props for code reusability
- SEO Friendly- implement server side rendering or pre-rendering
- For large scale application - mono repo structure for easy package management
React Coding Questions
Detect Overlapping Circle - https://codesandbox.io/s/interesting-swirles-4mvpw5?file=/src/App.js
