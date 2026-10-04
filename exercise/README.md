<h1>
  <span class="headline">Practice React Syntax Lab</span>
  <span class="subhead">Exercise</span>
</h1>


# **React Fundementals Lab**

### 1. Create the Components Folder

* Inside `src/`, create a folder called `components`.
* Inside `components`, create a folder called `Button`.

---

### 2. Create the Button Component

* Inside the Button folder, create a new component file.
* **IMPORTANT: ALL COMPONENT NAMES SHOULD BE CAPITAL FIRST LETTER** 
* Make it return a paragraph element for now with the content `Upload`.
* Export the component using `export default Button` at the bottom of your component file.

---


### 3. Import and Render the Button

* Open `App.jsx` again.
* Import the Button component.
* Render the Button component **twice** inside the App.
* run the application using `npm run dev` to see the result. You should see two buttons on the page.

---

### 4. Style the Button

* In the Button folder, create a CSS file.
* Style the paragraph element with background color, border, padding, etc. (What you think will make the button look nicer).

---

### 5. Add a clicking event to the buttons

* In the `Button.jsx` component add a function called `handleClick` that when called will just `console.log('Button Clicked')`.
* Add a onClick event on your p element so when it's clicked it calls the `handleClick` function.

---

### 6. BONUS use .map() for rendering array elements

* Create a new folder `StudentsList` and a  components called `StudentsList.jsx`
* Create a functional component inside that returns jsx
* Paste the following variable in the component:
```jsx
const students = ['Ahmad','Ali','Husna','Abdullah','Sarah','Zainab','Raghad','Sayed Hamed']
```
* Now what you should do is use .map() to show all the names of the students on the page inside of a `<ul></ul>`.
* Now export the component and import it in the `App.jsx` and then render it under the buttons.
* Run the app and see the result

---


### 7. BONUS BONUS Conditonal Rendering

* Only print the student name on the page in the `StudentsList.jsx` if the name is NOT Sayed Hamed

---
