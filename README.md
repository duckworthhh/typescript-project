# IO Chat

Name: James Henry Baculo  
Section: BSCS2A

## Description

IO Chat is a simple real-time chat application built with Node.js, Express, and Socket.IO. Users can open the application in their browsers and exchange messages instantly.

## Bonus Feature: Username on Every Message

I added a username feature that was not included in the original version shown in the video. Before sending a message, each user enters a username. I kept the original chat structure and added a username input. The browser now sends the username together with the message through the existing Socket.IO event, and the server broadcasts both values so every chat message displays the sender's username. This makes it easier to identify who sent each message when multiple people are chatting.

## Requirements

- Node.js and npm installed
- Internet connection for the Bootstrap and jQuery CDN files

## How to Run

1. Clone or download this repository.
2. Open the project folder in VS Code or a terminal.
3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   npm start
   ```

5. Open this address in your browser:

   `http://localhost:3000`

6. To test the chat, open the same address in two browser windows or tabs. Enter a username in each one and send messages.

## Project Files

```text
IO-Chat/
├── Index.html
├── server.js
├── package.json
├── .gitignore
├── README.md
└── screenshots/
    └── io-chat.png
```

## Screenshot

After running the application, take a screenshot showing the chat working. For a clearer demonstration, open two browser windows, use different usernames, and show a message from each user. Save the screenshot as:

`screenshots/io-chat.png`

