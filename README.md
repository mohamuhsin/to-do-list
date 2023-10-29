# To-Do-List

**Project: Building a Simple To-Do List**

*Overview*: Create a basic to-do list using React components.

**Step 1:** Set up a new React app.

**Step 2:** Create a To-Do List component.

1. Inside the `src` folder, create a new file named `TodoList.js`.
2. Create a functional component that displays a list of to-do items.
3. Use JSX to render a list of items with checkboxes.

**Step 3:** Create a form for adding new to-do items.

1. Inside `TodoList.js`, add a form with an input field for entering new to-do items and a submit button.

**Step 4:** Implement basic interactivity.

1. Add state to your `TodoList` component to manage the list of to-do items.
2. Implement event handlers to add new items to the list when the form is submitted and update the state accordingly.

**Step 5:** Display and update the list.
**Step 6:** Style your app using css.


1. Use JSX to map over the list of to-do items and display them.
2. Implement the ability to mark items as completed by changing their styles when clicked.

**CSS Code**

```
/* TodoList.css */

.todo-list {
  text-align: center;
  font-family: Arial, sans-serif;
  max-width: 400px;
  margin: 0 auto;
}

.todo-list h1 {
  background-color: #333;
  color: white;
  padding: 10px;
}

.todo-list input[type="text"] {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
}

.todo-list ul {
  list-style: none;
  padding: 0;
}

.todo-list li {
  border: 1px solid #ccc;
  padding: 10px;
  margin: 5px 0;
  cursor: pointer;
}

.todo-list button {
  background-color: #333;
  color: white;
  border: none;
  padding: 10px;
  margin: 5px 0;
  cursor: pointer;
}

.todo-list button:hover {
  background-color: #555;
}
```
