# Google Books Search

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Walkthrough Video](#walkthrough-video)
- [License](#license)

## Description

Google Books Search is a web application that allows users to search for books using the Google Books API, save their favorite books, and view saved books. It uses modern web technologies such as React, GraphQL, Apollo Client, and Bootstrap.

## User Story

AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

## Acceptance Criteria

GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  

## Installation

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/pchoi87/google-books-search.git
    ```
2. Navigate to the project directory.
    ```bash
    cd google-books-search
    ```
3. Install the dependencies.
    ```bash
    npm install
    ```
4. Start the development server.
    ```bash
    npm run develop
    ```
5. Open your browser and navigate to `http://localhost:3000`.

## Usage

1. Search for Books:  
   - Enter a book title in the search bar and click the "Search" button.
   - Browse the list of search results and click on a book to view its details.
2. Save a Book: 
   - Click "Save this Book!" to add a book to your saved list. 
   - View your saved books by clicking "See Your Books" in the navigation bar.
3. Delete a Saved Book: 
   - Click "Delete this Book!" to remove a book from your saved list.

## Technologies Used
- Front-end: React, GraphQL, Apollo Client, Bootstrap, Vite
- Back-end: Node.js, Express.js, Apollo, MongoDB 

## Features 
- Search for books using the Google Books API.
- Save your favorite books to your account.
- View and delete books from your profile.  
- Responsive design using Bootstrap.
- User authentication with JWT.  

## License 
This project is licensed under the MIT License.
