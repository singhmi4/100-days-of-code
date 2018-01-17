# 100 Days Of Code - Log

### Day 6 January 17, 2018

**Today's Progress**: Introduced to .ejs files for creating html templates that have javascript logic built in

**Thoughts:** 

*Web Development:*

EJS is simply an html file that has javascript logic built in. I need to get used to using the <%= %> tags for javascript code and the differences for adding content to the page and when it is simply logic based like if statements and loops. Moreover, I learned about the <code>res.render()</code> method which takes in the .ejs page as the first arg and then passes in a variable to the .ejs file that you would like to manipulate. For example, res.render("home.ejs", {variableExpress: variableEJS}). Also, I was re-introduced to objects in arrays and forEach loops which was a great refresher because I forgot how the syntax works for those variables.

**Link to Work:** Nothing yet

### Day 5 January 16, 2018

**Today's Progress**: Setup navigational meshes and learned about raycasting in Unity

**Thoughts:** 

*Video Game Development:*

I started off my Unity Game Dev Course session by setting up a navigational mesh that constrained the player's movement which is very important when designing levels. It was a very simple process of adding in the mesh through a few menu clicks. I then moved on to setting up a crosshair and created logic to allow the player to identify the object they are clicking by using RayCasting. The logic for raycasting was very straightforward where you use the ray cast method to collect hit detection data, the distance to extend your ray cast to, etc.

**Link to Work:** Nothing yet

### Day 4: January 15, 2018

**Today's Progress**: Learned about Express.js framework and built my first 3 apps following the Web Developer Bootcamp course.

**Thoughts:** 

*Web Development:*

It was super cool learning about installing Express and how to handle requests by sending information to the user back on the webpage. I was a little confused in the repeating word challenge in the Express Exercise because I was getting an error when I tried to use res.send() in the loop. I found out that I can only send (as of right now), one res.send() back to the user, so to show that the string repeated x times, I needed to build a new string in a for loop and finally res.send(newString) to the user after the loop is complete.

**Link to Work:** Nothing yet

### Day 3: January 12, 2018

**Today's Progress**: Installed a few NPM packages and created javascript from the content.

**Thoughts:** 

*Web Development:*

It was a very simple process installing NPM packages in the CodeAnywhere SSH Terminal. The main exercise was to generate a random list of products and prices using an NPM package called faker which generates a host of random data. The exercise was very straightforward as in I simply needed to make a for loop which printed out the randomly generated product and price using the pre-defined functions that came with the NPM package.

**Link to Work:** Nothing yet

### Day 2: January 11, 2018

**Today's Progress**: Defined 3D Character movement and camera rotation in Unity. Created javascript files in CodeAnywhere and ran them in server using Node.

**Thoughts:** 

*Unity Game Development:*

Creating character movement in Unity was a lot simpler than expected. However, character camera rotation was slightly more challenging. Adding the Y rotation camera movement to the Player GameObject directly caused the Player to move forward/backward. The script caused the player to rotate in the Y direction thus affecting the velocity in the Y direction. The solution to this, pointed out by the Unity instructor, was to create a GameObject specifically for pivoting along the x-axis and nest it within the Player object and nest the Main Camera in the new GameObject. This didn't cause the Player itself to rotate when the camera was rotated about the x-axis.

*Web Development:*

Learned what Node.js does and how to run in the commandline for the server I've created. It was very cool knowing that I can run Javascript using Node in the commandline. The exercises were a little tricky since I hadn't made functions and loops using JS in awhile. What had me stuck for a moment was that returning a value in javascript did not show up in the commandline when ran with node. In order for it show was to console.log the returned value to make it show in the commandline. Very good to know moving forward.

**Link to Work:** Nothing yet

### Day 1: January 10, 2018

**Today's Progress**: Completed the CommandLine section in Web Development Bootcamp on Udemy.
Installed CodeAnywhere, installed the node.js and mongoDB files, learned basic command line actions

**Thoughts:** I did not know too much about back-end developing before installing CodeAnywhere application. However, I feel a lot better after installing the application, learning the basic command line actions, and getting a better understanding about what Node.JS is and why it is used

**Link to Work:** Nothing yet
<!--
##### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)
##### **Today's Progress**: Fixed CSS, worked on canvas functionality for the app.
**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.
**Link(s) to work** [Calculator App](http://www.example.com)
### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)
**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.
**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.
**Link(s) to work**: [Calculator App](http://www.example.com)
### Day 1: June 27, Monday
**Today's Progress**: I've gone through many exercises on FreeCodeCamp.
**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.
**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)
-->
