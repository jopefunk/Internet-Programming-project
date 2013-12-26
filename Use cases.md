2. Use cases
================
2.1 Definition of the user groups
--------------------------

**Guest user**

Guest users are those who use the site without logging in. 
They can browse the site and read the posts. Guest users can log in or create an account.


**Administrator**

Administrator can access everything on the site. Administrator is able
to do everything on the site. He or she can access all the user information and manage the content.


2.2 Use case diagrams
-------------------------

[Use Case Diagram](https://users.metropolia.fi/~rosas/usecase.png)

2.3 Use case scenarios 
---------------------------

**"User wants to login"**

* Initial state:
User is not logged in.

* Normal flow:

1. User opens the site.
2. User click the link to the Login page.
3. User sees the page with the username and password form and the "Login" button.
4. Then he/she enters the username and password and clicks "Login".
5. The user is redirected to the front page and is now logged in.

*	What can go wrong:

The user mistypes the username or password.

*	Other activities going on at the same time:

Database checks the match with the username and password.

*	End state:

The user is logged in.

**"User wants to log out"**

*	Initial state:

User is logged in and on the main page.

*	Normal flow:
i.	User sees the log out button and clicks it.
ii.	The front page is refreshed and the user is now logged out.

* What can go wrong:
No user errors exist for logging out.

*	Other activities going on at the same time:
Database logs the user out from the account.

*	End state:
The user is logged out.

**"User wants to browse the site”**

*	Initial state:
User is on the main page.

*	Normal flow:
i.	User sees a list of the summaries of the latest articles.
ii.	User clicks the heading of the article he or she wants to read.
iii.	User is redirected to the full version of that article.

* What can go wrong:
The link to the article might be wrong.

* Other activities going on at the same time:
The browser redirects the user to the next page.

* End state:
User is reading the full version of an article.

**”User wants to comment”**

* Initial state:
User is reading the full version of an article..

* Normal flow:
i.	User sees the comment form at the end of the page.
ii.	User enters the comment into the comment box.
iii.	User enters his name to the name field.
iv.	User clicks the send button.

* What can go wrong:
The entered information is not valid.

*	Other activities going on at the same time:
The database checks if the entered text is appropriate. If it is it is published as a comment. 

*	End state:
User is on the same page, but sees his or her comment on top of the list of the comments.

**”User wants to edit a post”**

*	Initial state:
User is on the dashboard page. 

*	Normal flow:
i.	User sees the edit page link.
ii.	User clicks the link and is redirected to the 'edit page' page.

**“User wants to delete a post”**



**“User wants to edit blog”**
**“User wants to delete comment”**
**“User wants to create page”**
**“User wants to edit page”**
**“User wants to delete page”**


2.4 Depiction of one use case as a flow chart
-----------------------
[Flow chart](https://users.metropolia.fi/~susannark/flowchart.png)
