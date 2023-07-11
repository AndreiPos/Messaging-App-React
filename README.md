# Messaging-App
Chat application built with React for real-time messaging

**Steps:**
1. Create "Client" and "Server" folders
2. Inside the Client folder I have used the "npx" to install the react application so I don't have to configure the build setup manually
3. Installing the necessary dependencies
4. Creating the initial structure
	  a. Creating an index.js file inside the container folder to make it easier to import components
	  b. BEM Methodology (CSS Methodology)
	  c. Creating the App.css file for the styles of the web page
	  d. Creating the sidebar with buttons and a title
	  e. Creating a search bar
	  f. Rendering the preview of the chat channel
	  g. Creating the conversation channels
5. Client-Side Authentication
	  a. Learning about Axios
	  b. Creating sign-up and sign-in forms
6. Server-Side Authentication
	  a. Necessary dependencies:
		  bcrypt: Used for hashing passwords
		  crypto: Used for cryptographic functions
		  dotenv: used for loading environmental variables
		  express: Web framework used for building server-side applications
		  getstream: Used to integrate real-time chat and activity feeds into applications
		  stream-chat: Used to integrate Stream's chat API into applications
		  nodemon: Development tool used to monitor changes in Node.js applications and automatically restart the server
		  twilio: Used to integrate Twilio's cloud communication services into applications
		  corse: Allows resource sharing in Express applications
	b. Adding routes to the server
	c. Implementing the logic of receiving the data from the front-end and creating the signup and log-in feature
7. Client-Server communication.
	a. Creating the request between the server and the Client
	b. Being able to register and log in after creating an account
	c. Working logout button
8. Channel container
	a. Creating a chat room
9. Channel and sidebar
	a. Creating and displaying the message sent by the user
	b. Creating the channels and groups
	c. Creating the user list and invite feature
	d. Error handling
	e. Creating groups and private messaging
10. Edit channel feature
	a. Edit channel name or add new members. A message will be shown after the name is changed.
11. Search feature
	a. Find channels and people on the search bar
12. Twilio SMS notifications / Phone notifications
	a. Implementing Twilio API to send message notifications.
