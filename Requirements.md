4. Requirements (in traceable (and measurable) format)
==========================================================

4.1 Functional requirements

Authentication:

 * Login: By entering username or password to get access to user areas. For admins, he will be forwarded to dashboard where he can manage the site.
 * Sign-up: By filling up personal information, users can gain the right to be registered users. From that they can comment in some posts.
 * Change password: change passwords while logged-in
 * SSH connection: is secure connection to secure data communication between user and server.

Post view:

 * Content: Get the title, date, author and content of the post from the server
 * Admin managing tool: Get the most common tasks that admin can edit on the post including edit post, delete post
 * Comment: Get comment from data and show the comment if users want choose it. Also, there are fields that users can fill in so that registered users can comment 
 

Dashboard:

 * Edit page: Where admin can add, edit or delete pages from his site
 * Edit post: Where admin can add, edit or delete posts from his site
 * Edit theme: Where admin can edit theme for his site (including background color, font-style, font-size)
 * User managing: Where admin can view the list of users and delete spam users.
 * Category: to make categorise the posts from others so that it is easier for retrieving.


Page-view:

 * Show pages: Show the pages fetched from databases
 * Admin tool bar: show the most common tool that admin needs when logged in (add new post,  new comments,etc)
 * Show posts: show the posts in certain category 


4.2 Non-functional system requirements
-------------------------

4.3 Usability: how do you ensure that your system is easy to use?
-------------------------

To make the system easy to use, the mock-ups and design must work as expected, which means that the system feels 
natural to use. All of the buttons are where expected, main page is easy to find, and all is all we have to design 
the system in a way that is used in other softwares too, so even if the user is using it for the first time, 
it's easy to assume where different options and functions can be found. So in addition to the standard placing of the
elements the colors are used as guidelines, separating options from each other.


4.4 Reliability: how do you ensure that your system is reliable? List the possible system failures and how the system reacts to them
-------------------------

Some possible system failures: The network connection is not available or the system crashes

The network connection is not available: The user cannot open the system.

If the user has the connection, but looses it in the middle of using the system, the page will stay as it was until the network connection is back, unless another page is opened or the system is closed. All unsaved changes will be lost.

System crashes: If the system crashes, the result is pretty much the same as the network connection would be lost.


4.5 What other non-functional requirements should be documented?
-----------------------------------------------------------------


Efficiency
--------------

The application is downloaded to every users phone, so it shouldn't crash because of too many users at the same time. 
What might cause some problems, is the poor working of the wireless access points in the school area. If the access 
points don't work well, it affects the application also, and might cause a "bottleneck-effect", which means that the 
requests get lined-up, and are handled in chronological order. If the request is taking too long, it is aborted, then
the user has to resend the request.


Metrics
-----------

In our software, we should definitely keep track on bugs per line of code, code coverage, number
of lines of code and program execution time, load time and size.

Our code coverage would be high, because we will have to do a lot of testing, to prevent bugs from appearing in the final version and updates. When executing the test suite, we calculate the code coverage with the percent of program subroutines and the percent of program statements. We have to try to find all of the bugs, so that the application doesn't crash, freeze, give errors or allow a user to obtain unauthorized privileges. 

Source lines of code (SLOC) then is used to estimate the programming productivity and maintainability. The lines also 
reduce the size of the code, and so affect the program execution and load time.
