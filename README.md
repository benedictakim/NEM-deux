# NEM-deux

## DogEarD App Node-Express-Mongoose (NEM) | Server-side
This code is the server side (NEM) of MERN application "DogEarD" - a book club application that matches users based on shared book interests.

### Install

*npm run seed
*npm install
*npm start

## User Functionalities

AS A USER after login: 
1. I CAN: Save/pick books 
   (TBD - books display: filter out user’s book picks; in other words, display books not saved to user or display all?)
2. I CAN: click on one of my book picks
3. THEN, I CAN: view a list of other users who saved/picked this book
   (TBD - THEN, I CAN: comment in the book page)
4. I CAN: See the Book of the Week


## API Functions

First Header  | Second Header |
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```
Methods |	URLs    	|       Actions
GET	        api/books	        Get all books
GET	        api/books/:id	    Get Book by id
GET	        api/user/:book_id	Get Users by book_id
GET	        api/books/:user_id	Get Books by user_id
PUT	        api/user/	        Add new Books to user
PUT	        api/books	        Add new User to Books


## Functionalities working thus far:
1. Create books 
2. Create users
3. FindAll Books
4. FindAll Users
5. FindById - find book by book id
6. FindById - find user by user id

## Coding yet to be debugged/written

Many-to-Many relationships
7. Books into users: Create or update or both?
8. Users into books: Create or update or both?
9. FindById - find book by user id
10. FindById - find user by book id


## Example Code Sources
Many-to-Many Mongoose
https://dev.to/mkilmer/how-create-relationships-with-mongoose-and-node-js-with-real-example-43ei

MERN
https://johnhopkins.bootcampcontent.com/john-hopkins-university/jhu-bal-fsf-pt-04-2020-u-c/tree/master/21-MERN/01-Activities/03-Stu_AJAXBooks 
