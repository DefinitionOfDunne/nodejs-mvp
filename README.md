# Better Buddy Description:

* An app that allows users to make an account with the Better Buddy service. Users can create lists of important family and friends, set communication goals for each person listed, receive reminders based on their intended communication goals, and receive weekly summaries based on their "performance" of the previous week.

* User Experience:

* -User should be able to visit the site and create an account.
-User should be able to login in.
-User should be able to create a list of family AND a list of friends.
-User should be able to add or remove people for these lists at any time.
-User should be able to assign goals for communication (phone calls, text, email, social media interaction) for each listed person as a monthly template.
-User should be able to check off each communication goal once acheived.
-User should receive feedback each week (email?) with a report of percentage communication completed.

* NPM Modules:

* -Express
-nodemon
-MongoDB
-Mongoose
-Mocha
-Chai
-body-parser
-Passport

* Steps:

1. Specification of the project
2. Define database model 
3. Authentication (passport)
4. Build a simple API that serves specific data
5. Optionally use web sockets for some specific part (BONUS)
6. Your API should serve data from mongoDB using mongoose so you need mongoose models e.g. User
7. Write as many tests as possible.

* Screens That Users Will See:
1. base page: log in and sign up
2. user homepage: user profile with family and friend portals
3. stats page: # of contacts, breakdown of weekly scheduled talks, 		last weeks results
4. calendar page: shows weekly calendar of scheduled communications

* User Journey



* -comes to landing page

	if login then authenticates info
		if correct then prompted to /users:username page
		if incorrect then informed and access denied
 	if sign up then enters info
 		if successful then prompted to /users:usnername page

 -arrives at user homepage, can view:
 		1. family portal with members and friends portal with members
 			-buttons to add & remove members from each portal
 			-when adding member, prompted to form for communication frequency and type goals
 		2. weekly scheduled in daily calendar form
 			-just a display with data uploaded
 		3. stats section with totals and last weeks results
 			-just a display with data uploaded
