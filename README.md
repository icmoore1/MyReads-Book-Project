# My Reads Project

## Project Overview

A book tracking app built with React / Bookshelf app that allows you to select and categorise books you have read, are currently reading, or want to read.

**App Functionality**

In this application, the main page displays a list of "shelves" (i.e. categories), each of which contains a number of books. The three shelves are:

* Currently Reading
* Want to Read
* Read

Each book has a control that lets you select the shelf for that book. When you select a different shelf, the book moves there. Note that the default value for the control should always be the current shelf the book is in.

The main page also has a link to /search, a search page that allows you to find books to add to your library.

The search page has a text input that may be used to find books. As the value of the text input changes, the books that match that query are displayed on the page, along with a control that lets you add the book to your library. To keep the interface consistent, you may consider re-using some of the code you used to display the books on the main page.

When a book is on a bookshelf, it should have the same state on both the main application page and the search page.

The search page also has a link to / (the root URL), which leads back to the main page.

When you navigate back to the main page from the search page, you should instantly see all of the selections you made on the search page in your library.

## UI Setup
- git clone https://github.com/icmoore1/MyReads-Book-Project.git
- `npm install` or `yarn install`
- `npm start` or `yarn start`

## Server Setup
- git clone https://github.com/udacity/reactnd-contacts-server.git
- `npm install`
- `node server.js`


## Checklist

### Application Setup
- [x] The application was created with create-react-app and requires only npm install and npm start to get it installed and launched.
- [x] A README is included with the project. The README includes clear instructions for installing and launching the project.

### Main Page
- [x] The main page shows 3 shelves for books.

- [x] The main page shows a control that allows users to move books between shelves. The control should be tied to each book instance.
- [x] When the browser is refreshed, the same information is displayed on the page.

### Search Page

- [x] The search page has a search input field. As the user types into the search field, books that match the query are displayed on the page.
- [x] Search results on the search page allow the user to select “currently reading”, “want to read”, or “read” to place the book in a certain shelf.
- [x] When an item is categorized on the search page, and the user navigates to the main page, it appears on that shelf in the main page.

### Routing
- [x] The main page contains a link to the search page. When the link is clicked, the search page is displayed and the URL in the browser’s address bar is /search.
- [x] The search page contains a link to the main page. When the link is clicked, the main page is displayed and the URL in the browser’s address bar is /.

### Code Functionality
- [x] Component state is passed down from parent components to child components. The state variable is not modified directly - setState() function is used correctly.
- [x] Books have the same state on both the search page and the main application page: If a book is on a bookshelf, that is reflected in both locations.
- [x] All JSX code is formatted properly and functional.


## Contributing

NOTE:  Relied heavily on YouTube video by a fellow Udacity classmate (Ryan Waite)to assist in helping to understand what was needed to be done as an overview to get started:  https://www.youtube.com/watch?v=acJHkd6K5kI


## Resources & Dependencies

* [react-router-dom](https://www.npmjs.com/package/react-router-dom)