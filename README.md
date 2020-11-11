# The Exoplanet Project

The Exoplanet Project, named Other Words, is a simple app that represents a quick guide to exoplanets - planets outside our solar system.

## UX

### Project Goals

The app is designed as a simple to use guide to exoplanets. The main goal is to provide the user the possibiliy to have her/his own list where she/he can add their prefered exoplanets in order to keep track of them as they are officially confirmed by NASA, ESA, .. and many others authorized entities, and also to add any of these exoplanets to their favourites list. To kick things off, a list with 12 of the most relevant exoplanets confirmed up date will be provided. From there, the user is free to add any of the planets to her/his list. To make things a bit more interesting, the user will also have the possibility to check her/his weight on any of the exoplanets added, if ever, hypothetically (or not), will have the chance to end up on one of them.

### User Goals

* An app that serves as a guide to relevant confirmed exolanets.
* Possibility to add any new prefered exoplanet to her/his own list.
* Possibility to delete any new prefered exoplanet from her/his own list.
* Possibility to have the planets displayed in the list depending on some of their different properties (eg. type, size).
* Navbar available across and throughout all sections for a quick and easy navigation on the website.
* A way to follow the developer on social media for the latest updated.
* Responsive interaction with the website on desktop, table and mobile.

### User Stories

* As a user, I would like to be able to find out what's the app about and how to use its features.
* As a user, I would like to have a clear and clean display of the items (exoplanets).
* As a user, I would like a navbar that it's always available on all section, for me to easily navigate at any section of the app from everywhere.
* As a user, I would like clean and visible action buttons at every section.
* As a user, I would like my own section (list) where I am able to store my items (exoplanets).
* As a user, I would like the possibility to remove at any point any item I wish from my list.
* As a user, I would like an intuitive and easy way to add items to my list.
* As a user, I am expecting guidance where necessary; especially working with exoplanets and precise data about them, that might require some research on where the specific data can be found.
* As a user, I would like to be notified (via clear messages displayed on the screen) when some specific action cannot be performed and the reasons why.
* As a user, I would like to be able to sort my items depending on some of its most important properties.
* As a user, I am looking for an app that will also keep me on some level entertained while I'm using it.

### App Owners Goals

* Providing a dynamic app to act as a guide to exoplanets, where the user would be able to have its own section where she\he can add any exoplanet they wish, thus being a good tool to keep track of all the newly discovered exoplanets.
* Providing the user a default list of exoplanets to get things started and act as a guide on what type of data can be stored about the exoplanets.
* Keeping the user entertained by allowing her/him to calculate its weight on each exoplanet from her/his list. This will encourage the user to insert more items in her/his list, thus the time spent on the app will increase.

## Design Choices

I have chosen dynamic fonts for the entire app, to keep the user entertained; also they might remind the user of the colors of space dust on some of the best known nebulae.

### Main Background Image:

The main background image of the app is a representation of the recently confirmed exoplanet **Trappist 1 e** and it has been designed by [NASA](https://www.nasa.gov/) within their [SPACE TOURISM](https://solarsystem.nasa.gov/resources/682/space-tourism-posters/) program. Please see at the [Credits](#credits) section the source where the image in the app was taken from. I have chosen this image because it represents the travelers' excitement upon arrival on a foreign planet, with them browsing through the window of their space ship. In my opinion, this can as well represent the users' excitement when browsing through exoplanets in the app.

### Exoplanets' Images:

I have used images representing each exoplanet from the main list in order for the user to have a better representation of the specific exoplanet. It also adds dynamicity to the app, also by zooming in the image upon hovering. Please see at [Credits](#credits) section the sources where the images have been taken from.

### Default Images Within The App:

A default image will be added automatically when manually adding an exoplanet to your list. There are 2 images, each representing a common rocky planet and resepctively a common gas giant. 

### Fonts:

I chose to use [ABRIL FATFACE](https://fonts.google.com/specimen/Abril+Fatface?query=abril) as the font for all the main titles as I believe it's thickness and clean shape provide good readability and would be a good match for all of the app's sections. Please see at [Credits](#credits) section the sources where the images have been taken from.

I chose to use [LATO](https://fonts.google.com/specimen/Lato?query=lato) as main font as I believe it provides a good readability and looks proffessional.

I chose to use [ROBOTO SLAB](https://fonts.google.com/specimen/Roboto+Slab?query=roboto) for all action buttons as I believe it provides one of the best readability (which is always important for action buttons) and in the same time it can give the app a more futuristic aspect.

### Icons:

No icons have been used for the app.

### Colors: 

* Primary: **See Through Red** rgba(112, 16, 3, 0.8). I chose this color as background for all sections that contain text (including flash messages), as I believe it offers a not so strong contrast with the main image (in this case the main image will still be visible), but in the same time a good enough contrast for the text to be readable. 

* Secondary **Indigo** rgb(60, 10, 125). I chose this color for the action buttons and navbar as it matches some of the colors found in the main background image, and also I believe it provides a very good contrast between them and the rest of the app making them more visible, which is very important in order to provide a good user experience. 

* Tertiary Color: **Light Grey** #e5e5dc. I chose this color for the text as overall it gives a good contrast with all backgrounds used in the app. I chose this in the detriment of plain white as I believe it is also a bit warmer color, being a better fit for the overall design choices used throughout the app.

* Register Button: **Candy Apple Red** rgb(196, 23, 0). I chose this color for the Register button as it stands out on the navbar, urging the user to register if she/he hasn't done it so far. Also it is similar to the overall colors in the main background image. This color is not used anywhere else in the app.

## Wireframes:

I've built the wireframes for this project using [BALSAMIQ](https://balsamiq.com/). I've started creating the basic structure, basically the display of the items (exoplanets) and building on that afterwords. I have built wireframes for all multiple devices, which speeded up the process altogether.

Please view my wireframes for this project [here](https://github.com/Astig-1982/The-Exoplanet-Project/tree/master/wireframes). You can also see my wireframes on gitpod in the 'wireframes' directory.

## Features:

* Register an account form, Log-in & Log-out functionality.
* Adding manually any preferred exoplanet into the user's favourites list.
* Adding a default image of a rocky or gas giant planet, depending on the type of planet inserted by the user. 
* Adding to favourites feature any exoplanet from the main list provided in the app.
* Advanced item information, providing users with some of the exoplanet's most important properties.
* Possibility to filter the exoplanets by type: rocky planets or gas giants.
* Possibility to sort the exoplanets depending on their mass, from smallest to largest and other way around. 
* Possiblity to calculate the user's weight on each exoplanet added to her/his favourites list, either from the main list or those manually added.
* Profile section that will display the number of exoplanets the user has in her/his favourites list; also displays the number of rocky planets and number of gas giants in the favourites list.

### Register an account form, Log-in & Log-out functionality:

I chose to use this feature because it is one of the main features that defines the purpose of the app - each user to have her/his own favourites list where to add any preferred exoplanet.

#### Implementation:

I've created a Register/Log In section that it's connected to a login function in the app.py file. The login function will look for the user's username and passwords in the users collection in the database and if the password enteres mathces with the one in the database, the user's username will be put in a session variable. If the username is not found in the database, the user will be advised to go to the register form, where her/his username and passwords (once inputed in the relevant fields) will be saved into the users collection in the database and the user's username will be put in a session variable. Upon adding the first exoplanet to the favourites list, a collection with the name of the user's username will be created in the database.

### Adding manually any preferred exoplanet:

I chose to use this feature because, similar to the first feature, it is one of the main features that defines the porpuse of the app - to add any exoplanet as their discovery is cofirmed to the favourites list, in this case the user will be up to date to the lates discoveries in terms of exoplanets.

#### Implementation:

I've created a form with the fields representing the exoplanet's properties. The function created in app.py file will take the user's input and added into a variable 'new_planet' that will be inserted into the user's collection in the data base.

### Adding a default image of a rocky or gas giant planet:

I chose to use this feature as I believe it is good and useful for the user to have some sort of representation of the exoplanet inserted. In the nearest future I will develop this feature in order to give the possibility to the user to upload her/his own image of the exoplanet.

#### Implementation:

In the function created in app.py file to insert an exoplanet, I simply used an if statement with the outcome of defining a variable 'default_image', depending whether the type of exoplanet inserted by the user is rocky or gas. The 'default_image' variable will be inserted as a value for 'exoplanet_image' key in the user's collection.

### Adding to favourites list:

As mentioned above, this feature is on of the core features that defines the purpose of the app.

#### Implementation:

I've created a function in app.py file, that based on its id, will find the respective exoplanet in the 'exoplanets' collection in the data base and insert the same exoplanet in the user's collection (favourites list).


### Advanced exoplanet information:

I chose to feature in order to display in details some of the exoplanet's most relevant properties. For any exoplanet enthusiast, the info displayed in regards to the exoplanet in this section is essential when thinking of almost any celestial body (distance from earth, start system, etc.).

#### Implementation:

I've simply created a function in app.py file that, based on its id will find the exoplanet in either the 'exoplanets' collection or user's collection in the database and diplay all of its key-values in a separate section (page).

### Possibility to filter the exoplanets by their type:

I chose to use this feature as I believe any exoplanet enthusiast will be interested in filtering the exoplanets based on one their most important characteristics - their type of composition.

#### Implementation:

I've created functions in app.py file that will find in the respective collection ('exoplanets' or user's collection) only items (exoplanets) with the value of either 'rocky' or 'gas' for the key 'type'. 

### Possibility to sort the exoplanets depending on their mass:

I've created this function as the mass is one of the most important properties in a celestial body. The user will be most likey interested to check which exoplanet is more massive than the other. This feature, together with the one above (filtering by type), in my opinion will keep the user more enternained when using the app, resulting in more time spent on the app.

#### Implementation:

By simply creating a function in app.py file that will find all exoplanets in a respective collection ('exoplanets' or user's collection) and applies sort() method to them before rendering them onto either the main list section or favourites list. 


### Possiblity to calculate the user's weight on each exoplanet:

This feature was created in the spirit of keeping the user excited and also making the user adding more exoplanets to her/his favourites list - as only on the surface of the exoplanets added to favourites list can the weight be calculated. It also, in my opinion, contributes to app's dynamicity. 

#### Implementation:

I've created a function in app.py file that will take the user's input (her/his weight) from a form created html, and parse it into a float number. It also finds, based on its id, the respective exoplanet in the user's collection, take its 'mass' and parse it also into a float number. Afterwords it multiplies the mass and the user's input and the result (representing her/his weight on the respective exoplanet) will be rendered onto a new page.

### Profile section that will display the number of exoplanets in the favourites list:

I chose to use this feature as I believe it's good for the user to have a quick reminder of the items in her/his favourites list everytime when she/he logs in. 

#### Implementation:

In the function created in app.py file for displaying the profile, I've used count() method on the items from the the user's collection.












