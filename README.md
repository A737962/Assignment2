1. Difference between Npm and Npx in React.

* Npm(Node Package Manager) is a package/dependency manager, used to install and run node.js packages/dependencies globally/locally.
* Npx(Node Package Executer) is a tool to execute node.js packages.

2. How to change the react application port (default port=3000)?

* You can do by editing your package.json file which is created when you create an app in react.
* Edit the start attribute inside the script attribute i.e., "start": "set PORT=(YOUR_PORT_NUMBER) && react-scripts start"
* There is another way of doing i.e., creating an .env file and adding PORT=(YOUR_PORT_NUMBER)

3. Explain the Execution flow of a React App.

* Initialization - Component is constructed with given props and state. Done in the constructor of a component class.
* Mounting - Stage of rendering of JSX returned by the render method itself.
* Updating - State is updated and the affected component is re-rendered.
* Unmounting - Component is removed from the page.

4. What is Strictmode in ReactJs?

* StrictMode is a tool for detecting and highlighting problems in a application.
* It helps in:
* Identifying components with unsafe lifecycles.
* Warning about legacy string ref API usage.
* Warning about deprecated findDOMNODE usage.
* Detecting unexpected side effects.
* Detecting legacy context API.

5. What are ReactJs Fragments?

* It a wrapper for multiple component return without wrapping them in a container or array.
