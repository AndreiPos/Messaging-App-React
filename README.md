# Chat application built with React for real-time messaging

This project is a real-time messaging application built using React. It allows users to communicate with each other in real-time, create chat channels, and exchange messages seamlessly.

I completed this project by following [this](https://www.youtube.com/watch?v=MJzbJQLGehs) tutorial that provided step-by-step guidance throughout the development process. The tutorial served as a valuable resource in learning React concepts, implementing client-server communication, integrating authentication, and incorporating essential features such as channel management, search functionality, and Twilio API for message notifications.


## What have I learnt

**Coding Techniques:**

Creating an index.js file to simplify component imports and improve code flexibility.\
Using the Block Element Modifier (BEM) Methodology to enhance CSS maintainability. Example: "channel-search__input__icon".\
Utilizing the "?" (if) and ":" (else) syntax for conditional statements to improve readability.\
Leveraging "rafce" from the ES7 React Native snippets to generate boilerplate code for components.\
Using the "&&" operator to conditionally render content based on a condition.\
Making use of Axios, a library for backend communication.

**JavaScript Concepts:**

Template literals (``) for incorporating variables into strings.\
Object literals (:) to define property-value pairs within an object.

**Error Handling:**

Utilizing the try-catch statement to handle errors and execute code based on error occurrence.

**React Hooks:**

Leveraging the useEffect function to manage side effects in functional components.\
Employing useState to manage local state within functional components.

### Problems and Bugs:

Grammar mistakes: Addressed and resolved.\
React Version: Uninstalled the current version of React and switched to React@17 for this project.

	
## <h3>Steps followed for the completion of the project:</h3>
1. Create "Client" and "Server" folders
2. Inside the Client folder "npx" was used to install the React application for an automatic setup of the build
3. Installing the necessary dependencies
4. Creating the initial structure
     - Creating an index.js file inside the container folder to make it easier to import components
     - BEM Methodology (CSS Methodology)
     - Creating the App.css file for the styles of the web page
     - Creating the sidebar with buttons and a title
     - Creating a search bar
     - Rendering the preview of the chat channel
     - Creating the conversation channels
5. Client-Side Authentication
     - Learning about Axios
     - Creating sign-up and sign-in forms
6. Server-Side Authentication
     - Necessary dependencies:
       - bcrypt: Used for hashing passwords
       - crypto: Used for cryptographic functions
       - dotenv: used for loading environmental variables
       - express: Web framework used for building server-side applications
       - getstream: Used to integrate real-time chat and activity feeds into applications
       - stream-chat: Used to integrate Stream's chat API into applications
       - nodemon: Development tool used to monitor changes in Node.js applications and automatically restart the server
       - Twilio: Used to integrate Twilio's cloud communication services into applications
       - corse: Allows resource sharing in Express applications
     - Adding routes to the server
     - Implementing the logic of receiving the data from the front end and creating the signup and log-in feature
7. Client-Server communication.
     - Creating the request between the server and the Client
     - Being able to register and log in after creating an account
     - Working logout button
8. Channel container
     - Creating a chat room
9. Channel and sidebar
     - Creating and displaying the message sent by the user
     - Creating the channels and groups
     - Creating the user list and invite feature
     - Error handling
     - Creating groups and private messaging
10. Edit channel feature
     - Edit channel name or add new members. A message will be shown after the name is changed.
11. Search feature
     - Find channels and people on the search bar
12. Twilio SMS notifications / Phone notifications
     - Implementing Twilio API to send message notifications.
