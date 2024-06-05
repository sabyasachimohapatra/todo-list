# User Management App

This project is a simple User Management App that allows users to add, edit, and delete names. The application uses Bootstrap for styling and Font Awesome for icons. It also employs localStorage to persist user data across browser sessions.

## Features

- Add a new user
- Edit an existing user
- Delete a user
- Persist user data using localStorage

## Technologies Used

- HTML
- CSS (Bootstrap 5.0.2)
- JavaScript
- Font Awesome for icons
- localStorage for data persistence

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/user-management-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd user-management-app
   ```

## Usage

1. Open the `index.html` file in your web browser.
2. Enter a name in the text field and click the "Add User" button to add a new user.
3. Use the edit (pencil) icon to edit an existing user.
4. Use the delete (trash) icon to delete a user.

## File Structure

```
user-management-app/
│
├── index.html
├── script.js
├── README.md
```

### index.html

This is the main HTML file that contains the structure of the User Management App. It includes references to Bootstrap and Font Awesome for styling.

### script.js

This JavaScript file contains the logic for adding, editing, deleting, and displaying users. It interacts with localStorage to persist user data.

## Code Explanation

### HTML

- The HTML structure includes a form with an input field for the user's name and a button to add the user.
- A table is used to display the list of users along with actions to edit or delete each user.

### JavaScript

- The `addUserBtn` button triggers the addition or editing of a user.
- The `SaveInfo` function saves the user data to localStorage.
- The `DisplayInfo` function displays the list of users in the table.
- The `EditInfo` function populates the input field with the selected user's name for editing.
- The `DeleteInfo` function removes the selected user from the list and updates localStorage.

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Create a pull request.


## Screenshort of Todo-List
![Screenshot of todo-list](https://github.com/sabyasachimohapatra/todo-list/assets/153741349/de41e3a3-5f39-4c84-8bb4-749aaefaa862)
