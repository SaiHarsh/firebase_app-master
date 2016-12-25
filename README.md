Introduction:-
This is simple text editor blog, the special feature in this blog is that we can add style to text and upload a single image.
-------------------------------------------------------------------------------------------------------
Server and database used: - Firebase and deployed this application in it. URL: - https://blog-733f2.firebaseapp.com/


Languages: - HTML, CSS, Bootstrap, AngularFire, AngularJs, Jquery
-------------------------------------------------------------------------------------------------------

File Description: -
database.rules.json:- This rules followed by application to upload in Firebase Database.

firebase.json:- This file is used to deploy the application in Firebase.If you open you can see for hosting it's using public folder which is the default folder used by the Firebase and when index.html will be called when the application is started.

404.html:  - This file is called by Firebase server when specific file is not found in the directory 

View_posts.html: - This is the HTML file for view all posts according to time. this will take 1-3 seconds to load all the posts.

In CSS all the style files are available for all HTML files.

JS folder.
1. ServerSide.js: - This is used to upload data to Firebase server.
2. test.js: - To retrieve the data from the Firebase database.
3. texteditor.js: - Script for text editor for styling.