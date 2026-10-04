<h1>
  <span class="headline">Practice React Syntax Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Setup

Open your Terminal application and navigate to your `~/code/ga/labs` directory:

```bash
cd ~/code/ga/labs
```

Create a new Vite project for your React app:

```bash
npm create vite@latest
```

You'll be prompted to choose a project name. Let's name it `react-components-lab`.

- Select a framework. Use the arrow keys to choose the `React` option and hit `Enter`.

- Select a variant. Again, use the arrow keys to choose `JavaScript` and hit `Enter`.

Navigate to your new project directory and install the necessary dependencies:

```bash
cd react-components-lab
npm i
```

Open the project's folder in your code editor:

```bash
code .
```

### Clear `App.jsx`

Open the `App.jsx` file in the `src` directory and replace its contents with the following:

```jsx
// src/App.jsx

function App(){

  return (
    <h1>Hello world!</h1>
  );
}

export default App
```

- Open both `index.css` and `App.css` and delete everything inside

### Running the development server

To start the development server and view our app in the browser, we'll use the following command:

```bash
npm run dev
```

You should see that `Vite` is available on port number 5173:

```plaintext
localhost:5173
```
