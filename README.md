# User Management with Role-Based Access Control (RBAC)

This project is a **User Management System** built using **React.js**. It enables managing users and their roles in a simple, table-based UI. You can add, edit, and delete users, with each user having a **name**, **email**, **role**, and **status (active/inactive)**. The data is stored in **localStorage**, ensuring it persists after page refreshes.

## Key Features

- **Add Users**: Create new users with a name, email, and role. Email format is validated before saving.
- **Edit Users**: Modify existing user details by clicking "Edit" in the user table.
- **Delete Users**: Remove users from the table permanently.
- **Responsive Design**: The app adapts to different screen sizes, making it suitable for both desktop and mobile devices.

## Technologies Used

- **React**: For building the user interface.
- **Tailwind CSS**: For styling and responsive design.
- **localStorage**: For persisting user data across page refreshes.

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/harver2001/RBAC-VRV-Security
   ```

2. **Install dependencies:**

   - Make sure Node.js and npm are installed.
   - Run the following to install dependencies:

     ```bash
     npm install
     ```

3. **Start the app:**

   ```bash
   npm start
   ```

## Using the Application

- **Add Roles**: Create roles first, which can be assigned to users later.
- **Add Users**: Click the "Add User" button to add new users.
- **Edit Users**: Use the "Edit" button next to a user to modify their details.
- **Delete Users**: Click "Delete" to permanently remove a user from the system.
- **Role Management**: Assign roles when adding or editing users to control access permissions.
- **Data Persistence**: User and role data is stored in `localStorage`, so it remains even after refreshing the page.
```
