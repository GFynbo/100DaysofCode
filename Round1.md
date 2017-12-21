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
