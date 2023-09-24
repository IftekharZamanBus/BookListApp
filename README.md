# BookListApp

## Overview
This project combines HTML, CSS, and JS to make a project where you can create new books, and search for them using the search bar. It can be used by yourself as a Book List tracker to see how many books you've read and if you ever want to go back to one of them you can just search it using the search bar.

### Technology Stack

- **HTML**

- **CSS**

- **JavaScript**

### Functionality (JavaScript)
This project incorporates several JavaScript functions, below are the many key functions needed for this project to work: 

- **addBooks() - Value placeholder which tells you to add the title, author, or isbn number.**

- **renderBook() - Makes the table work and keep on changing based on the character length, word length, word count, etc.**

- **handleBookListClick() - Once you click the submit button for the book it will return a btn-primary, success, or danger message to the console which will you if it's working or not.**

- **handleEditClick() - If you click the edit button, it will allow you to change everything except the isbn#.**

- **handleSaveClick() - Once you have edited the author or title of the project, it will ask you to save your changes. Once the save button is clicked your changes will be pushed to the display.**

- **handleDeleteClick() - If you ever want to deletea book from your book list, you can just click the delete button and it will delete it for you.**

- **displayNotification() - If anything goes wrong it will display an error message in the console based on exactly what went wrong.**

- **saveBooksToStorage() - Once you click the submit button after submitting a book, it will save it to the storage.**

- **retrieveBooksFromStorage() - Once you have clicked the submit button and the book is in storage, you can retrieve that book from storage using the search bar.**

- **handleSearch() - This handles the search bar and makes it so if you search the author, title, or even ISBN#, the book will show up.**

### Styling and Layout
This is the styling and layout of the project and everything I used to make it look how I wanted it to look.

- **CSS - In the CSS we imported a lux theme from Bootswatch and connected it with the HTML to give it's own looks,**

### Project Strucuture
This is all the files I used and why I used them.

- **index.html - This was mainly used to create containers aswell as all the words you see on the display besides the one that the user has typed.**

- **bootstrap.min.css - This is a imported lux theme from Bootswatch and it makes everything look like the lux theme by using the same classes and ids'.**

- **app.js - This is the js file we used that consists of a lot of functions that keep the site up and working such as, add button, edit button, save button, delete button, etc.**

### Getting Started
To deploy this project on your local machine or incorporate it into your own application, follow these steps: 

1. Clone the repository to your local machine using the following command: 

    **git clone https://github.com/IftekharZamanBus/BookListApp.git**

2. Open the project folder into your desired code editor.

3. Open the index.html file into your web broswer to view the BookListApp.

### Visit My Website

**https://legendary-donut-205fcf.netlify.app**