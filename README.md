# React JS ![React JS logo](/images/react-js.png)

## What is REACT JS? 💭

React.js is an **open-source JavaScript library**, crafted with precision by Facebook, that aims to simplify the intricate process of building interactive user interfaces. Imagine a user interface built with React as a collection of components, each responsible for outputting a small, reusable piece of HTML code.

In React, you develop your applications by creating reusable components that you can think of as independent Lego blocks. These components are individual pieces of a final interface, which, when assembled, form the application’s entire user interface. [Watch here for more info!](https://youtu.be/N3AkSS5hXMA)

### Purpose of REACT JS📜

The purpose of React JS is to make it easier to build fast, interactive, and dynamic user interfaces for web applications. By using a component-based approach, React allows developers to break down complex UIs into smaller, reusable pieces, making code easier to manage and update. Its virtual DOM feature enhances performance by efficiently updating only the parts of the UI that change, rather than reloading the entire page. Overall, React simplifies the process of creating responsive and engaging web apps, making it a popular choice for developers.

### Key Features of REACT JS🤖

- **JSX(JavaScript Syntax Extension)**: JSX combines HTML and JavaScript, allowing embedded JavaScript in HTML elements

- **Virtual DOM (Document Object Manipulation)**: React’s virtual DOM updates only changed elements, unlike other frameworks that refresh the entire DOM, making web applications faster.

- **One-Way Data Binding**: In React’s one-way data binding, data flows from parent to child components only, with child components communicating changes back to modify the parent’s state.

- **Component-Based Architecture**: React allows developers to create self-contained components that handle their own state, simplifying complex UI creation and reuse.

- **Strong Developer Tooling**: React offers tools like React Developer Tools for Chrome to help developers debug and inspect component hierarchies.

- **Declarative Syntax**: React lets developers define the UI based on app state, automatically updating it to simplify code and ease debugging.

---

## Setting Up React JS🛠

### *Prerequisite Applications*

Download and install these following softwares before installing React JS:

- **Node.js**: You have to install Node first because React.js is a JavaScript library, and Node.js is a JavaScript runtime environment that allows you to run JavaScript on the server side. [Download Node.js here!](https://nodejs.org/en)

- **Code Editor**: Install any code editor that can compile React JS. A good code editor recommended for React development is [Visual Studio Code.](https://code.visualstudio.com/download)

After setting up the prerequisite apps we can proceed with setting up React JS.

### Step-by-step React JS Set Up✨

1. **Installation of Node.js** and **NPM (Node Package Manager)**
    - Verify installation in the command prompt:

      ```bash
      node -v
      npm -v
      ```

2. **Install React Js**
    - Using ***CRA (create-react-app)***: Still in your command prompt window, navigate to the directory that you want to use in creating your React project. To do this, type `cd [directory name]` then click enter.
        - Example:

          ```bash
          cd documents
          ```

        - `cd documents` command to go to documents directory.

    - In the documents directory (or wherever you're creating your project), create a folder that you will be using to create your React app. Type `mkdir [folder name]` then navigate to the newly created directory using `cd [newly created folder name]`.
    - In the newly created folder directory, type in `npx create-react-app [project name of your choice]`, and then wait until your React project is completely created.
        - Example:

          ```bash
          npx create-react-app react-app-ko-ito
          ```

        > [!NOTE]
        > When naming a project for React JS, the name of the project cannot contain any uppercase letters.

3. **Open Project in the Code Editor**
    - Lastly, open the React project in your code editor by typing in `code .` at the command prompt.

> [!IMPORTANT]
> There are various ways to intall and set up React JS, the method I included here is the "traditional" way and the React team does not recommend using it anymore. [Here is a documentation of the other way of installing React.](https://www.freecodecamp.org/news/how-to-install-react-a-step-by-step-guide/)
