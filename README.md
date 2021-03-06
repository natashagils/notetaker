# Note Taker

# Synopsis

This is an application that can be used to write, save, and delete notes. This application uses an express backend and saves and retrieves note data from a JSON file.

Deployed to Heroku at: https://notetaker-uoft.herokuapp.com/notes


# User Story
AS A user, I want to be able to write and save notes
I WANT to be able to delete notes I've written before
SO THAT I can organize my thoughts and keep track of tasks I need to complete


# Screenshot 
<img width="1199" alt="Screen Shot 2020-06-13 at 1 42 42 PM" src="https://user-images.githubusercontent.com/56641651/84575540-c2dbf880-ad7b-11ea-8372-212926d60df9.png">

<img width="1218" alt="Screen Shot 2020-06-13 at 1 42 56 PM" src="https://user-images.githubusercontent.com/56641651/84575550-cbccca00-ad7b-11ea-8ee1-26426a0a691b.png">


# Acceptance Criteria 

* Application should allow users to create and save notes.

* Application should allow users to view previously saved notes.

* Application should allow users to delete previously saved notes.


# Sample Code


app.use(express.json());
app.use(express.urlencoded({ extended: true }));
app.use(express.static("public"));
app.use(compression());
app.use("/api", apiRoutes);
app.use("/", htmlRoutes);

 
  
  
 # Installation
To use this portfolio, log into your GitHub account (if you don’t have a GitHub user profile, create one at https://github.com/join) and open this link in your browser: https://github.com/natashagils/notetaker. Then click on the "Fork" button at the top right corner and wait until the repo is forked. 

 # Use
 To use this application, begin with installing node (npm install node) in your CLI and then view the application in your localhost (port 3000). 
