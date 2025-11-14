**Steps I Followed to Auto-Generate the API (using LoopBack)**



1\. Create a new LoopBack project  --> lb4 app

2\. Generate the Book model --> lb4 model

&nbsp;	Model: Book

&nbsp;	Properties: id: number (auto-generated)

&nbsp;		    title: string (required)

&nbsp;		    author: string (optional)

3\. Create an in-memory datasource --> lb4 datasource

&nbsp;	Datasource: db

&nbsp;	Connector: In-memory db

4\. Generate the repository --> lb4 repository

&nbsp;	Repository: BookRepository

&nbsp;	Model: Book

&nbsp;	Datasource: DbDatasource



5\. Auto-generate the CRUD controller --> lb4 controller

&nbsp;	Controller Type: REST Controller with CRUD functions

&nbsp;	Base path: /books



LoopBack generated all API endpoints automatically.





**How to Run the API**



1\. Install dependencies --> npm install

2\. Start server --> npm start

API Runs



**API Endpoints (Auto-Generated)**



**Method	Endpoint	Description**

GET	/books/count	Count books

GET	/books	Get all books

POST	/books	Create a book

GET	/books/{id}	Get a book by id

PATCH	/books/{id}	Update a book

PATCH   /books          Update multiple books

PUT	/books/{id}	Replace a book

DELETE	/books/{id}	Delete a book


