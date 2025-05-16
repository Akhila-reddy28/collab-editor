# collab-editor

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: KUNTA AKHILA REDDY

*INTERN ID*: CT06DA429

*DOMAIN*: FRONT STACK WEB DEVELOPMENT

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

The project is designed to create a real-time collaborative text editor where multiple users can edit the same document simultaneously over the internet. It consists of both backend and frontend parts, each with a specific role to make the whole system work smoothly.At the core of the project is the backend server, written in Node.js, located in the file named server.js. This server uses Socket.IO, a powerful library that allows real-time, bidirectional communication between the server and multiple clients (users). When a user types or makes changes in the editor, these changes are immediately sent to the server using WebSockets, and then the server broadcasts these updates to all other connected users. This ensures that every user sees the exact same content and updates happen instantly for everyone, creating a seamless collaborative experience.To keep the document data safe and persistent even if the server restarts or users disconnect, the project uses MongoDB, a NoSQL database. The data structure and interaction with MongoDB are handled through a Mongoose model defined in the document.js file. Mongoose is a helpful library that simplifies working with MongoDB by allowing developers to define schemas and models easily. Whenever users open the editor, the server loads the current state of the document from the database and sends it to the users. As users continue editing, the server updates the database to reflect these changes, ensuring that the latest version is always stored.The project uses environment variables stored in a .env file, which helps configure important settings like the server’s port number or the database connection string (MongoDB URI). Using environment variables keeps sensitive information secure and makes it easier to change settings without modifying the code.All the external libraries and dependencies required by the project are listed in the package.json file, a standard Node.js file that tracks what modules the project needs to run. When these dependencies are installed, they are saved in the node_modules/ directory. This ensures that the project can easily be set up on any machine with all necessary packages.this project combines modern web technologies to allow real-time collaborative editing on documents. Users open the webpage served by the backend server, which loads the latest document content from the database. As users type or modify the text, their changes are sent instantly to the server and shared with all other connected users. The server keeps the document data saved safely in MongoDB, so nothing is lost. This structure — with a backend managing connections and persistence, a frontend handling user interaction, and a database ensuring data safety — creates a powerful tool for teamwork and collaboration on written content over the web.

#OUTPUT

![Image](https://github.com/user-attachments/assets/3a532024-e4a5-4a29-a316-4be4d60f9503)
