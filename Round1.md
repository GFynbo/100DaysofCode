## Day 1 - December 7th, 2017
Today I worked on adding the form to allow users to add a restaurant to a list of matches. It currently is failing and needs to figure out how access the profile model and just update the existing user in the database. After accessing the list of restaurants it then needs to iterate through the top 10 and load them into the matches page.
***
*Slow progress, more tomorrow*

## Day 2 - December 8th, 2017
I worked on implementing the relational part of the model to display matches for the user. I now understand how to add an object however I need direction on how to pass and object through a form or something so the user can see exactly which restaurants they are matched with.
***
*Medium progress, more tomorrow*

## Day 3 - December 9th, 2017
Continued progress on models and briefly touched on display.
***
*Slow progress, more tomorrow*

## Day 4 - December 10th, 2017
Today I got a lot done. I implemented a ID system for the restaurants in order to maintain a unique ID for URL making and increasing the ease in which you can access your matches. In the future I plan to pass the ID through in order to add the match to the User's list. Great progress today and will pick up tomorrow.
***
*Good progress, more tomorrow*

## Day 5 - December 11th, 2017
The match models is proving to be quite a headache. I seemed to have implemented it, however I somehow broke the registration process. Going to look into removing some of the old migrations and refreshing the database to see if resolves the issue.
***
*Decent progress, more tomorrow*

## Day 6 - December 12th, 2017
Finished the match modeling! Add the matches page to generate user specific matches so you can see what you have matched with. Added partial functionality to home page for adding matches. No option to deny a match yet and it is not dynamically showing all restaurants. Matches page and index have been updated.
***
*Awesome progress, more tomorrow*

## Day 7 - December 13th, 2017
Absolutely insane progress today. Managed to take what I've learned from implementing the Match system and deploy a Deny system to keep track of the restaurants that the user has said no to. Additionally, I added a second form for the home page and used the action component of the button to submit to a separate view to allow functionality of the deny button. This also adds to the users match pages and checks that they haven't already denied this restaurant. In the future I will implement a method that automatically purges old denies to give those another chance when the user feels so inclined.
***
*Insaneeeee progress, more tomorrow*

## Day 8 - December 14th, 2017
Not as much time to work on GoudaTime today, but still got a few things done. I was able to fix the navbar to allow for active link styling and updated the profile page. I allow the user to edit there profile via a modal from the profile page and update via post request to a different view.
***
*Okay progress, more tomorrow*

## Day 9 - December 15th, 2017
Short day today due to finals and studying. It may have been short but it was actually incredibly productive. I was able to implement the delete feature on the matches page and update the about page to make working contact buttons. Additionally, I updated the modals to change for each restaurant thanks to javascript. Also in a huge but surprisingly easy step, I removed the deny model and manager and replaced it with a single field in the existing match model. This should reduce database calls and simply the process of keeping track.
***
*Efficient progress, more tomorrow*

## Day 10 - December 16th, 2017
Not as much big picture stuff today, mostly messing with existing styles and pages. However, I also managed to add a new dependency called django-bootstrap-3 for easier implementation of bootstrap features such as icons and forms. The new django-boostrap also allows pretty/good form validation allowing for a significantly improved signup/login form.
***
*Decent progress, more tomorrow*

## Day 11 - December 17th, 2017
Again, busy with finals and studying today so progress is definitely slower. I managed to move the database from sqlite3 to postgresql relatively painlessly. I also added django-map-widgets as a package for the website for planned location functionality in the future.
***
*Decent progress, more tomorrow*

## Day 12 - December 18th, 2017
With the last day of finals looming large on my mind, I had to stop mid-corrections on the styling of the home page and site as a whole. Tomorrow after my finals I will fix the styling and move on with getting current location and updating the user model to reflect that.
***
*Pretty good progress, more tomorrow*


## Day 13 - December 19th, 2017
Finished finals, tried to wrap up some stuff, but am exhausted. Removed google maps in the background and in general because it takes a lot of time and was messing up the styling of the entire site. Instead I have moved forward with trying to implement the geocoding portion of the Google Maps API. Tomorrow I will try to figure that out.
***
*Good progress, more tomorrow*

## Day 14 - December 20th, 2017
Updated the design and information on the readme to be current and usable by outside developers. Also added the env requirement for pip as to allow easy cloning and building of the development code. I was also able to add the map for choosing your location and updated both the user and the restaurant models in order to allow for location. I also fixed the form for adding your location as well as changing the navbar and adding a logo.
***
*Goudaaaa progress, more tomorrow*

## Day 15 - December 22nd, 2017
Very little progress, attempted a little work on the maps thats about it.
***
*Very little progress, more tomorrow*

## Day 16 - December 23rd, 2017
Finally back home today, sat down for about an hour and was able to implement the geolocation feature I have been trying to implement for a couple days. I allowed the user to click a button and have the browser find their location and update the hidden form so if the user wants to save it they can. Canceling it still leaves your former address in the database. I also added a button to the profile so the user can see their address and link back to the home page to change it.
***
*Very efficient progress, more tomorrow*

## Day 17 - December 24th, 2017
Little slower progress today with minimal development. Although I didn't get as much done, it was still productive and my understanding of the google maps api and javascript and expanding. Productive!
***
*Productive progress, more tomorrow*

## Day 18 - December 25th, 2017
Just updated the looks of the profile page today as it is Christmas.
***
*Little progress, more tomorrow*

## Day 19 - December 26th, 2017
Updated models and moved them all to individual files in the models/ directory to allow easier editing and manipulation of models in the future.
***
*Better progress, more tomorrow*

## Day 20 - December 27th, 2017
Got a little work done on the beginning of a command to cleanse the database of matches that are more than a day old. Also added new features to be created such as the javascript needed for adding a large number of new places into the database for use by the app.
***
*Decent progress, more tomorrow*

## Day 21 - December 28th, 2017
Started working on a simple Java recipe manager to practice and implement Java styles and concepts.
***
*Different progress, more tomorrow*

## Day 22 - December 29th, 2017
Updated the home page for showing your address and removed the update address button in the profile as it was confusing. Now started the work on sending a confirmation email upon signing up.
***
*Good progress, more tomorrow*

## Day 23 - December 30th, 2017
Got a little aesthetic work done on the home page of GoudaTime and was also able to start moving forward with my RecipeManager project in Java. I will add some more touch-ups to GoudaTime tomorrow, but the heavy lifting will be on RecipeManager.
***
*Decent progress, more tomorrow*

## Day 24 - December 31st, 2017
Updated the classes for all of the parts of the recipe and tested them briefly in the main function.
***
*Decent progress, more tomorrow*

## Day 25 - January 1st, 2018
Updated and added the GUI form on Intellij to display and add recipes in the future.
***
*Slow progress, more tomorrow*

## Day 26 - January 2nd, 2018
Stuck on a plane for six hours today may as well make the most of it. In addition to other updates I managed to create an initial model for groups and added an html page with updated views and urls. I also managed to add a fairly functional version of the directions in class for the RecipeManager. Rome wasn't built in a day, tomorrow the grind continues.
***
*Superb progress, more tomorrow*

## Day 27 - January 3rd, 2018
Updated the form on the group page and added a view for the post function and updated urls and the website still needs a new form added under forms.
***
*Decent progress, more tomorrow*

## Day 28 - January 4th, 2018
Updated every class in the entire RecipeManager application giving the variables private types and return functions to give the strings. Also added a custom print function in the Recipe class for easy viewing of existing recipes.
***
*Fun progress, more tomorrow*

## Day 29 - January 5th, 2018
Added the JFrame and many fields to the tabbed pane to allow users to create and view recipes easily.
***
*Good progress, more tomorrow*

## Day 30 - January 6th, 2018
Continued work on the gui and added the JList functionality to display the recipes in the given list.
***
*Good progress, more tomorrow*

## Day 31 - January 7th, 2018
Switched from traditional Swing and AWT to JavaFX which seems to be much more versatile and better looking. Managed to create a main window and add a menu, but functionality needs to be added. Mostly RecipeManager today.
***
*Fun progress, more tomorrow*

## Day 32 - January 8th, 2018
Worked on a hard programming challenge today that ate two hours of my time, however after that I was able to work a little more on the GUI for RecipeManager.
***
*Eh progress, more tomorrow*

## Day 33 - January 9th, 2018
Made great progress on the GUI for RecipeManager today. I added labels with IDs and a listener for the ListView to allow the updated list to display correctly, and on selection of an item it would display the appropriate information.
***
*Great progress, more tomorrow*

## Day 34 - January 10th, 2018
Worked on the second screen for the JavaFX/GUI of the RecipeManager. Next the functionality for switching screens needs to be implemented.
***
*Decent progress, more tomorrow*

## Day 35 - January 11th, 2018
Little progress today since traveling. However, I was able to add the ingredients on to the GUI recipe selection scene.
***
*Slow progress, more tomorrow*

## Day 36 - January 12th, 2018
Terrible progress today, just updated the styling of the profile card on the profile page for GoudaTime.
***
*Slow progress, more tomorrow*

## Day 37 - January 13th, 2018
Updated and fixed the ingredients label in the GUI of the RecipeManager application.
***
*Mediocre progress, more tomorrow*

## Day 38 - January 14th, 2018
Updated the group, index and profile templates for minor changes to the styles and the shown characters.
***
*Mediocre progress, more tomorrow*

## Day 39 - January 15th, 2018
Did a lot of work on the GUI today. Managed to change what was displaced on the VBox the is the majority of the screen. Additionally, I added functionality to disable the menu while making a new recipe and adding some spacing for style.
***
*Good progress, more tomorrow*

## Day 40 - January 16th, 2018
Added a back button to allow the user to back out of the create recipe screen and a second recipe to allow functionality testing on the GUI. Also switched the pane to a scroll pane to allow the user to see the whole screen without having to extend the window size.
***
*Decent progress, more tomorrow*

## Day 41 - January 17th, 2018
Lotta work done today. I managed to finish creating the functionality of the new recipe button such that a user can now add any recipe they want. This required the updating of many classes to string values rather than int and arrays. Additionally, I am in the beginning steps of creating persistent storage for the recipes for users to continue to use the app to manage their recipes after closing.
***
*Great progress, more tomorrow*

## Day 42 - January 18th, 2018
Decent work today. Finished a big and important step in Recipe Manager as the data persistence is now functional. When you create a recipe and close the app it will save all the recipes in JSON using GSON to a tmp location.
***
*Good progress, more tomorrow*

## Day 43 - January 19th, 2018
Did a lot of work on the README today to update all the work and progress I've made on the app. I also added a separator to make the recipe display more aesthetically pleasing.
***
*Good progress, more tomorrow*

## Day 44 - January 20th, 2018
Didn't spend as much time today as I would have liked, but I manage to add and implement the Delete feature for existing recipes pretty quickly.
***
*Fun progress, more tomorrow*

## Day 45 - January 21st, 2018
Was able to implement a functional version of an edit button for the recipes pretty quickly. The edit function allows you to change all aspects of the existing recipes and once the app closes it saves these changes as well.
***
*Quick progress, more tomorrow*

## Day 46 - January 22nd, 2018
Less progress today, but was still able to get things going by fixing an annoying edit button bug that would only allow the user to edit the very first item (recipe) in the list.
***
*Meh progress, more tomorrow*

## Day 47 - January 23rd, 2018
Just updated the readme today to reflect progress.
***
*Sloth-like progress, more tomorrow*

## Day 48 - January 24th, 2018
Tweaked the size and fitting of the FlowPane.
***
*Sloth-like progress, more tomorrow*

## Day 49 - January 25th, 2018
Added a label to the find friend feature.
***
*Sloth-like progress, more tomorrow*

## Day 50 - January 26th, 2018
Added Profile text to the profile page of GoudaTime
***
*Sloth-like progress, more tomorrow*

## Day 51 - January 27th, 2018
Working on the display of the RecipeManager so that the recipes fit on the page without horizontal scrolling.
***
*Okay progress, more tomorrow*

## Day 52 - January 28th, 2018
Worked on the GUI for RecipeManager to at least bring the GUI back to a functional state and allows the user to see the whole recipe.
***
*Meh progress, more tomorrow*

## Day 53 - January 30th, 2018
Missed yesterday due to a long day. Today I started reading YDKJS (You Don't Know JS) and began a Node project to mess around.
***
*Decent progress, more tomorrow*

## Day 54 - January 31st, 2018
First day with progress in a while! Today I reviewed and modified the Group model in GoudaTime and added forms for functionality after the migration. Additionally, I setup and played around with Node.js and Express.
***
*Great progress, more tomorrow*

## Day 55 - February 1st, 2018
Did some work on a Spanish Scraper to get all the new Spanish words from our Wiki.
***
*Decent progress, more tomorrow*

## Day 56 - February 2nd, 2018
Did a little work on Node and JS in general.
***
*Okay progress, more tomorrow*

## Day 57 - February 3rd, 2018
Worked on and wrote a Python script with regular expressions and Pandas to clean and rename thousands of CSV files.
***
*Good progress, more tomorrow*

## Day 58 - February 4th, 2018
SUPERBOWL!! Wrote a little javascript to prevent users from seeing the users screen on express/node without logging in.
***
*Decent progress, more tomorrow*

## Day 59 - February 5th, 2018
Today was a sad, sad day. Patriots lost and the world is barely turning. However, I did add a simple nav bar in Node.
***
*Meh progress, more tomorrow*

## Day 60 - February 6th, 2018
Today I learned a little more about javascript and added a todolist page on my Express and Node application. Doesn't do much right now, but I have big future plans!
***
*Good progress, more tomorrow*

## Day 61 - February 7th, 2018
Just did a little touchup on the menu to add the todolist I made yesterday.
***
*Bad progress, more tomorrow*

## Day 62 - February 8th, 2018
Updated the review class for the recipe manager so that the user can also enter a written review, I plan on adding a GUI feature to implement this soon.
***
*Decent progress, more tomorrow*

## Day 63 - February 9th, 2018
Just added a little menu to the footer of the Node.js/Express messing around application.
***
*Slow progress, more tomorrow*

## Day 64 - February 10th, 2018
Worked on adding a receive emails option to the user profile on GoudaTime. This includes the ability to change and update it on the profile page. It is incomplete as it stands right now, the modal does not update the database.
***
*Good progress, more tomorrow*

## Day 65 - February 11th, 2018
Just fiddled with the forms and models in GoudaTime to try and use the checkbox for receiving newletter emails.
***
*Bad progress, more tomorrow*

## Day 66 - February 12th, 2018
Fiddled and played with Node and just ended up changing the menu a little.
***
*Bad progress, more tomorrow*
