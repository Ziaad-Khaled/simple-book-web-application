# Web-Based Book Application

## Project Objective

The objective of this project is to give you hands-on experience in developing a network application based on the client/server architecture. A web application that serves as a simple book database is built. This website allows users to access information about books, including abstracts, genres, authors, reviews, and more. Users are allowed to create an account, add books to their "want to read" lists, and search for books.

## Components

### Users Login (Main Page)

- Registered users are allowed to log in to their accounts using their stored username and password.
- If an unregistered user tries to log in, an error message is displayed.

### User Registration

- Users are allowed to create an account using a unique username and a password.
- The users' information is stored in a JSON file that represents a simple database.
- If the user tries to register using an already taken username, an error message is displayed.

### Home Page

- The home page is the first page that should be encountered by the users when they log in to their accounts.
- It contains several book genres and a button to view the user's "want to read" list.
- When the user clicks on any book genre, they are redirected to that genre's page.

### Genre Page

- The genre page contains all the books within this genre.
- When a user clicks on any book's name, they are redirected to that book's page.

### Book Page

- The book page contains an abstract for the book.
- The page also contains an embedded video describing the book, which can be streamed by the user.
- Finally, an "add to want to read" button is added. The button adds this book to the user's "want to read" list in the database.

### Want to Read List Page

- The want to read list page contains the books that the user previously added using the "add to want to read list" button.
- A "view want to read list" button is added to the home page that directs the user to their own want to read list page.

### Search

- A search bar is displayed in all pages except for the registration and login pages.
- The search will be done using books' names only.
- The search result is either a "book not found" message if the book was not available in the database or a list of the books that contain the search keyword in their names.
- The search results should be clickable and they direct you to that specific book's page.

## Technologies

### Node.js

- Node.js is an open source platform for executing JavaScript language outside the browser (JavaScript run-time environment).
- You can install Node.js through the following page: [Node.js Download](https://nodejs.org/en/download/current/).
- When the installation is done, a tool called NPM (node package manager) is also installed. NPM is used to install node packages directly through the terminal (command prompt). To know more about NPM and the available packages visit [npmjs.com](https://www.npmjs.com/).

### Express

- Express is a node package that is used as a web application framework.
- Express can be installed directly through the terminal using the command "npm install express". Express is the package responsible for running the web server.

### Visual Studio Code (VSCode)

- VSCode is the IDE that will be used for developing the web application. VSCode has built-in support for JavaScript, HTML, and several other languages. Furthermore, it has a built-in terminal that can be used directly to execute commands.

### File System

- File system is a core module in NodeJS. It is an API that allows you to interact with the file system in your computer. the File System is used to create a local database for your website as a simple storage files for your data.

### Embedded JavaScript (EJS)

- EJS is a template engine that allows the user to generate HTML with plain JavaScript. It allows you to load data from your application in the view. After the template is rendered, it generates an HTML file for the browser.

## Installation

To set up the project, follow these steps:

1. **Node.js and NPM**:
   - Install Node.js and NPM from [here](https://nodejs.org/en/download/current/).

2. **Express**:
   - Install Express using the terminal with the command: `npm install express`.

3. **Visual Studio Code (VSCode)**:
   - Download and install VSCode from [here](https://code.visualstudio.com/).

4. **File System (Core Module)**:
   - Node.js includes the File System core module for file operations.

5. **Embedded JavaScript (EJS)**:
   - EJS will be used for rendering HTML templates.

Now you're ready to start developing your web-based book database application!

## Preview

Here's a glimpse of what the web application will look like:

![S1](https://github.com/Ziaad-Khaled/simple-book-web-application/assets/77291238/7ab02031-f35a-41ed-8820-ad6610ab87e9)
![S2](https://github.com/Ziaad-Khaled/simple-book-web-application/assets/77291238/771d6b52-42ec-4342-890b-2a5c667f7fc7)
![S3](https://github.com/Ziaad-Khaled/simple-book-web-application/assets/77291238/5545477c-dc34-4eeb-a00b-4d8bbb2915c9)



Feel free to explore the user interface, navigation, and functionality of the web application.
