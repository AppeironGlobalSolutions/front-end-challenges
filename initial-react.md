# Challenge:
==========

Build a simple to-do list application using React and the React Redux Toolkit. The application should have the following features:

-   A text input field where the user can enter a new to-do item
-   A button to add the new item to the list
-   A list of all the to-do items that have been added
-   A checkbox next to each item in the list to mark it as complete
-   A button to remove completed items from the list

## Requirements:
-------------

-   Use React for the frontend and the React Redux Toolkit for managing the application state
-   The to-do list should be stored in the global state using the Redux Toolkit's `createSlice` function
-   The application should be functional and visually appealing

## Bonus:
------

-   Add the ability to edit an item in the list by double clicking on it
-   Persist the list in local storage so that it is not lost when the page is refreshed
-   Use the React Redux Toolkit's `createAsyncThunk` function to make an API call to a to-do list backend and save the list to the server when items are added, removed, or completed
-   Use Material-UI for styles, inputs, and more
-   Use Formik and Yup for form validations, with error and help text
