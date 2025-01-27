# Interview-stuff
 
[Link 7 Problem Statements](https://github.com/joanllenas/7guis-React)!

## Open Source API

### Fakestore API whch returns all the products
```
https://fakestoreapi.com/products
```

### Fakestore API whch returns 1 product
```
https://fakestoreapi.com/products/1
```

### Json Place Holder API's
```
https://jsonplaceholder.typicode.com/users
```
```
https://jsonplaceholder.typicode.com/todos
```
```
https://jsonplaceholder.typicode.com/photos
```

***

### Searchable Data List:
- Display the list and implement a search bar to filter results based on user input.
- Create a Pagination component to navigate through pages.

---

### Debounced Search Bar:

***Description:*** Implement a debounced search bar in React that fetches search suggestions from a API. The app should include:

<ol>
  <li>An input field where users can type their search query.</li>
  <li>Fetching suggestions with a debounce of 500ms.</li>
  <li>Cancel the previous API request if the user types before the debounce completes.</li>
</ol>

***Requirements:***

<ol>
  <li>Use useState for managing query and results.</li>
  <li>Use useEffect for debouncing the API call.</li>
  <li>Use the Fetch API or Axios to simulate fetching suggestions.</li>
  <li>Display a loading state when fetching suggestions.</li>
</ol>

- Create a search bar that fetches suggestions from an API with a debounce of 500ms.
- Bonus: Cancel the previous request if the user types before debounce completes.

---

### To-Do List App Problem Statement.

**Description:** Create a React application that allows users to manage a to-do list. The app should support the following functionality:
<ol>
  <li>Add a new task by typing in an input field and pressing a button.</li>
  <li>Display the list of tasks added.</li>
  <li>Delete a specific task when the user clicks a delete button next to it.</li>
</ol>

**Requirements:**
<ol>
  <li>Use useState for local state management.</li>
  <li>Ensure tasks are displayed in the order they are added.</li>
  <li>Prevent adding empty tasks.</li>
</ol>
