# startup
Startup Application for CS 260

This is a readme file for the startup application for CS 260 Web Development Class
I am really looking forward to using different tools for this class and making a cool application


# Elevator Pitch:
## My Startup Application: Chat DewPT
### The Elevator:
College is hard, in fact **_life_** is hard. But one of the beautiful things that makes 
both of those things easier is the divine elixir known as Mtn Dew. Not only is it 
delicous and full of life giving caffeine, but it comes in a flavor fit for any mood. 
But sometimes it is hard to know where to find just the right one. Introducing 
Chat DewPT, the fastest way to find your favorite fix. Chat DewPT is a community driven 
platform where you can submit, browse, and verify vendors for all your favourite 
flavors of that delicious, bubbly brew. Users create verified accounts, submit locations 
and flavor options available there, and other users can confirm on that post that it is 
accurate. All of these submissions will be kept 
current with constant live updates so they won't EVER be sent on a wild Dew chase.

> Chat DewPT, Doing the Dew in the right place.

### Layout Preview:


![Sketch of the planned layout of Chat DewPT, added in markdown, with general sketches of 
text and icons, and their arrangement. Before and after the login would technically be different pages, but it will look similar to appear cohesive](https://github.com/NyiajNpis/startup/blob/main/StartupSketch.jpg)


### Key Features:

-Authenticated User Accounts over HTTPS
-Display of current posts
-Post updates including changes, current upvote count, and new posts shown in real time
-User posts containing text showing a location and attached list selected from available flavors
-Ability for Users to interact with other posts to upvote them
-Ability for admin to delete offensive or inaccurate posts

## Class Technologies
- **HTML** - Basic structure and organization of icons and information. Three pages, one for login, one for adding new post, and one for viewing and interacting with existing posts
- **CSS** - Styling and animating of Mtn Dew related text and icons, and animation of user interactions (changing button colors or adding likes
- **JavaScript** - Interactivity to go through the login process, add posts, and interact with existing posts
- **Service** - Endpoints for:
  - retrieving current posts
  - retrieving current dew flavors
  - submitting likes
  - retrieving current like status
  - aproximate location of user ip - https://www.abstractapi.com/api/ip-geolocation-api
- **DB/Login**  Store users, flavor options, posts, and likes in database. Register and login users. Credentials securely stored in database. Can't post or interact unless authenticated.
- **WebSocket** - As each user posts or likes, those interactions are updated to all other users.
- **React** - Application ported to use the React web framework.







