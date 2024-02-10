## Note Taker App

This Note Taker application allows users to create, save, and delete notes. It utilizes Express.js for the server-side framework, UUID for generating unique IDs for each note, and is deployed on Heroku.

### Features

- **Create Notes**: Users can create new notes by providing a title and text content.
- **Save Notes**: Notes are saved to the server, allowing users to access them later.
- **Delete Notes**: Users can delete unwanted notes, removing them from the application.

### Technologies Used

- **Express.js**: A Node.js web application framework used for building the server-side of the application. It handles routing and middleware to manage requests and responses.
- **UUID (Universally Unique Identifier)**: A package used to generate unique identifiers for each note, ensuring that each note has a distinct ID.
- **Heroku**: A cloud platform used for deploying the application. Heroku provides a simple way to host web applications without worrying about server management.

### Deployment

The application is deployed on Heroku and can be accessed using the following link: [Note Taker App](https://note-taker23-de0287693503.herokuapp.com/)

### How to Run Locally

To run the application locally, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone <https://github.com/mcook2323/note-taker.git>
   ```

2. Navigate to the project directory:

   ```
   cd <project-directory>
   ```

3. Install dependencies using npm:

   ```
   npm install
   ```

4. Start the server:

   ```
   npm start
   ```

5. Access the application in your web browser at `http://localhost:3001`.

### Usage

1. **Creating a Note**: Click on the "New Note" button and fill in the title and content of the note. Click the save icon to save the note.

2. **Viewing Notes**: All saved notes are displayed on the left side of the application. Click on a note to view its content.

3. **Deleting a Note**: To delete a note, click on the delete icon next to the note you want to remove.




