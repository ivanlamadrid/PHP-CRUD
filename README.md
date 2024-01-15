# CRUD-PHP

This repository contains a simple Client Management System implemented in PHP. The system allows users to perform basic CRUD (Create, Read, Update, Delete) operations on client records.

## Files

1. **index.php**
   - This file displays a list of clients in a tabular format.
   - Users can navigate to create new clients, edit existing ones, or delete records.

2. **create.php**
   - Manages the creation of new client records.
   - Users can input client details such as name, email, phone, and address.
   - Validates input and provides appropriate feedback.

3. **edit.php**
   - Handles the editing of existing client records.
   - Retrieves the client details based on the provided client ID.
   - Users can modify the information and submit changes.

4. **delete.php**
   - Manages the deletion of client records.
   - Users can delete a client by clicking the corresponding button in the list.

## Setup

1. **Database Configuration**
   - The system uses a MySQL database. Ensure you have a database named 'myshop'.
   - Update the database connection details (servername, username, password) in each PHP file accordingly.

2. **Bootstrap**
   - The system uses Bootstrap for styling. The necessary Bootstrap files are included via CDN links.
   - Ensure an internet connection is available for proper styling.

## Usage

1. **List of Clients (index.php)**
   - Access this file to view the list of clients.
   - Users can perform actions like creating, editing, and deleting clients.

2. **Create New Client (create.php)**
   - Navigate to this page using the "New Client" button on the index page.
   - Fill in the client details and submit the form.

3. **Edit Client (edit.php)**
   - Click the "Edit" button next to a client on the index page.
   - Modify the client details and submit the changes.

4. **Delete Client (delete.php)**
   - Click the "Delete" button next to a client on the index page.
   - Confirm the deletion to remove the client record.

## Known Issues

- No user authentication: The system currently lacks user authentication, making it unsuitable for deployment in a production environment.
- Minimal error handling: The error handling is basic and may need improvement for a robust application.

## Contributing

Feel free to contribute to the development of this simple PHP Client Management System. Open issues or submit pull requests to suggest improvements or fix any existing problems.
