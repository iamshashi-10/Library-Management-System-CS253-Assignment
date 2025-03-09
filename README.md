# Library-Management-System-CS253-Assignment

To run the system, type the following commands:
g++ main.cpp -o main
.\main

The system has the following three csv files which serve as databases-
* users.csv: (stores name,user id, password, type of user) The type of user '1' is for student, '2' is for faculty and '3' is for the librarian. Each row shows the detail of one user.
* books.csv: stores name of book,author,publisher,isbn code, is_issued. stores the details of all books in the library.  The is_issued field is 1 if the book has been issued by a user and zero otherwise. One row in the file stores the data of one book.
* issued_books_data.csv: (stores user id,name of book,isbn code, time) The user id is the id of the user who issued the book and timenstores the time when the user issued the book.

I have assumed that to reserve a book means deleting it from the database hence making it available only to physically read in the library itself. Only the librarian has the power to reserve a book.
initially there is no data in the issued_books_data.csv since no book is issued initially. 
in the users.csv i have created a librarian as Arnav.
