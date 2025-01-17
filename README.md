# Guvi-React-JS-Task-6
This Repository is created for submitting the allocated task from React JS Day - 10 session.

The given task is to Create a React App that allows for CRUD operations with user data using React and Axios.

- Mock API URL : https://jsonplaceholder.typicode.com/users

Application Work Flow:

Adding a User:

- To add a new user, the user clicks on the "Add User" button.
This action opens a form where the user can input the new user's details such as name and email.
- After filling out the form and saving it, a request is made to the remote API to add the new user.
- If the addition is successful, a Snackbar alert is shown with a success message indicating that the user has been added.
- If there is an error during the addition process, a Snackbar alert is shown with an error message indicating the failure.

Reading a user:

- Users can view the list of users Upon loading.

Editing a User:

- To edit an existing user, the user clicks on the "Edit" button.
- This action opens a form pre-filled with the user's current details, allowing the user to make changes.
- After making the desired changes and saving the form, a request is made to the remote API to update the user's information.
- If the update is successful, a Snackbar alert is shown with a success message indicating that the user has been updated.
- If there is an error during the update process, a Snackbar alert is shown with an error message indicating the failure.

Deleting a User:

- To delete an existing user, the user clicks on the "Delete" button.
- If the deletion is successful, a Snackbar alert is shown with a success message indicating that the user has been deleted.
- If there is an error during the deletion process, a Snackbar alert is shown with an error message indicating the failure.

Technology Stack:

- React: Used for building the frontend user interface and managing application state.
- Axios: Utilized for making HTTP requests to a remote API to perform CRUD operations.
- Material-UI: Provides pre-designed React components for creating a visually appealing and responsive user interface.

Kindly refer the following files for source code:
- /src/App.jsx
- /src/UserList.jsx
- /src/UserItem.jsx
- /src/UserForm.jsx

Attached application workflow Screenshots for your reference under "Screenshots" folder.

Thankyou and Awaiting feedback. 
