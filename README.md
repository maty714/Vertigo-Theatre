# Vertigo-Theatre
Hosts snippets of code created during a 2 week internship


**Photo Storage**
Showcases a method that was implemented to allow a photo to be stored as a byte array when a new user is added.
1. The **addImage** method is shown on lines 135 - 148 of the .
2. The **create** method utilizes the photo uploaded, as a parameter in this method, which then gets passed into the **addImage** method when called. This starts on line 52 of ProductionMembersController.
3. The index.cshtml file shows how we deal with a user not choosing a photo. I discovered that an exception would get thrown if that was the case. This is on lines 45 - 53.
4. The edit.cshtml and create.cshtml showcase the HTML and CSS used to allow a user to choose a photo from the front end. These are on lines 90-95.
