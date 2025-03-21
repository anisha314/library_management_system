## Online Library Management System

This project is an Online Library Management System built using React.js, Redux, and Tailwind CSS. It allows users to browse, add, and manage books in an online library. The application includes a responsive UI and uses React Router for navigation.
## Table of Contents
Features

Pages

Components

Technologies Used

Installation

Usage

Folder Structure

Contributing

License

Features

Browse and search for books

View detailed information about a book

Add new books to the library

Responsive design

Error handling for invalid routes

Pages

Home Page: Introduction and overview of the library system.

Book Detail Page: Displays detailed information about a selected book.

Add Book Page: Form to add a new book to the library.

Browse Books Page: Lists all available books with options to categorize and search.

Error Page: Displays a 404 error for invalid routes.

Components

Navbar: Navigation bar for navigating through the application.

BookCard: Displays individual book details in a card format.

BooksData: Lists all the books in the library.

Categories: Filters books based on categories.

Footer: Footer section of the website.

SearchField: Input field for searching books.

TabButton: Buttons for navigating between different book categories.

Technologies Used

React.js: JavaScript library for building user interfaces.

Redux: State management library for React applications.

Tailwind CSS: Utility-first CSS framework for styling.

React Router: Library for handling routing in React applications.

nanoid: Library for generating unique IDs.

Vite: Development tool that provides a fast build and development environment for modern web projects.

Installation

Follow these steps to run the project locally:

Clone the repository:

git clone https://github.com/your-repo/online-library-management.git

Navigate to the project folder:

cd online-library-management

Install dependencies:

npm install

Run the application:

npm run dev



## Folder Structure
online-library-management/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── BookCard.js
│   │   ├── BooksData.js
│   │   ├── Categories.js
│   │   ├── Footer.js
│   │   ├── Navbar.js
│   │   ├── SearchField.js
│   │   ├── TabButton.js
│   ├── pages/
│   │   ├── AddBookPage.js
│   │   ├── BookDetailPage.js
│   │   ├── BrowseBookPage.js
│   │   ├── ErrorPage.js
│   │   ├── HomePage.js
│   ├── store/
│   │   ├── index.js
│   ├── utils/
│   │   ├── bookSlice.js
│   │   ├── mockData.js
│   ├── App.js
│   ├── index.js
├── package.json
## Running application

- 1.Clone repository
- 2.navigate to the folder
- 3.npm install 
- 4.npm run dev
