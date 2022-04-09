# Vertigo-Theatre
Hosts snippets of code created during a 2 week internship



**Photo Storage:**
Showcases a method that was implemented to allow a photo to be stored as a byte array when a new user is added.
1. The **addImage** method is shown on lines 135 - 148 of the ProductionMembersController.
2. The **create** method utilizes the photo uploaded, as a parameter in this method, which then gets passed into the **addImage** method when called. This starts on line 52 of ProductionMembersController.
3. The index.cshtml file shows how we deal with a user not choosing a photo. I discovered that an exception would get thrown if that was the case. This is on lines 45 - 53. It also shows how we are able to convert an image stored as a byte array back to an image that can appear on the screen
4. The edit.cshtml and create.cshtml showcase the HTML and CSS used to allow a user to choose a photo from the front end. These are on lines 90-95.



**Text Helper:**
Showcases a method that was created to limit text shown in a string input.
1. Includes an ouput image which shows what "Hello World" would look like if it was limited by a chosen amount of character




**Model:**
Showcases the database that was built using code first.
1. Includes all CRUD pages created based off that model.


**Style Page:**
Showcases the page view for the create and edit CRUD pages using CSS.
