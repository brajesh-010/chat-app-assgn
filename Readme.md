# Chat Application

**Introduction:**
For this assignment, we're going to dive into creating a cool chat application! It's a fun project where we'll build a platform for people to chat with each other in real-time.

**Prerequisites:**
Before we get started, make sure you have Node.js and npm installed on your computer. If you don't have them yet, you can easily download and install them from the official Node.js website.

**Installation:**
1. First, let's get the code for our chat app. Go to this link: [chat-app-assgn](https://github.com/brajesh-010/chat-app-assgn) and click on the "Code" button. Then select "Download ZIP".
2. Once the ZIP file is downloaded, extract it to a folder on your computer.
3. Open your terminal (Command Prompt on Windows, Terminal on macOS or Linux) and navigate to the folder where you extracted the code.
4. Now, let's install all the necessary dependencies. Type the following command and press Enter:
   ```
   npm install
   ```

**Configuration:**
There's not much to configure for this project, so you're good to go after installing the dependencies.

**Running the Application:**
1. In your terminal, navigate to the project folder if you're not already there.
2. Type the following command and press Enter to start the server:
   ```
   npm start
   ```
3. Open your web browser and go to [http://localhost:3000](http://localhost:3000) to access the chat application.

**Usage:**
1. When you open the application in your browser, you'll see a login page. If you don't have an account yet, you can sign up for a new one.
2. Once you're logged in, you'll be taken to the chat interface.
3. To start chatting, select a user from the list or create a new group chat.
4. Type your message in the chat box at the bottom and hit "Send" to send your message.
5. You'll see messages from other users popping up in real-time!

**Features:**
Our chat application comes with some cool features:
- User authentication: You need to log in to use the app.
- Real-time messaging: Messages appear instantly without needing to refresh the page.
- Group chats: You can chat with multiple people at once by creating or joining group chats.
- Message history: You can see previous messages in your conversations.

**Code Structure Overview:**
Our code is organized into different files and folders. The main parts are:
- **Server:** This handles all the behind-the-scenes stuff like managing users and sending messages.
- **Client:** This is what users see and interact with in their browsers. It's responsible for showing the chat interface and sending messages.

**Technologies Used:**
We used Node.js for the server-side code and Socket.IO for real-time communication between the server and clients. For the frontend, we used HTML, CSS, and JavaScript.

**Conclusion:**
That's it! You've created your very own chat application. Have fun chatting with your friends, and feel free to explore the code to see how it all works together.

**Resources:**
- [Node.js](https://nodejs.org/)
- [Socket.IO](https://socket.io/)
