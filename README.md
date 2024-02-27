# startup
Startup Application for CS 260

This is a readme file for the startup application for CS 260 Web Development Class
I am really looking forward to using different tools for this class and making a cool application

# **My Startup Application: Chat DewPT**
### **The Elevator:**
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

### **Layout Preview:**


![Sketch of the planned layout of Chat DewPT, added in markdown, with general sketches of 
text and icons, and their arrangement. Before and after the login would technically be different pages, but it will look similar to appear cohesive](https://github.com/NyiajNpis/startup/blob/main/StartupSketch.jpg)


### **Key Features:**

- Authenticated User Accounts over HTTPS
- Display of current posts
- Post updates including changes, current upvote count, and new posts shown in real time
- User posts containing text showing a location and attached list selected from available flavors
- Ability for Users to interact with other posts to upvote them
- Ability for admin to delete offensive or inaccurate posts

### Class Technologies:
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





### HTML Startup Work Checklist
- Review and deploy Simon HTML
  - Clone the HTML Simon repository to your development environment.
  - Open the project in VS Code and examine the application's use of HTML.
  - Execute in your development environment using the VS Code Live Server extension.
  - Debug using the browser's dev tools to examine the loading of the HTML on the Network tab, and the HTML in the Elements tab.
  - Deploy to your production environment using the deployment script so that it is available with your domain's simon subdomain.
- Create the HTML deliverable of your startup application. Make sure your name is displayed in the application and that there is a link to your GitHub repository.
- Represent all of the content and structure that your final application will need.
- Include placeholders for all of the technology that your application will eventually represent.
- Make sure your main HTML file is named index.html so that it will load by default.
- Periodically commit and push your code to GitHub.
- Periodically update your startup repository's notes.md file to reflect what you have learned and want to remember.
- Push your final version of your project to GitHub.
- Deploy your startup application to your production environment (your server).
- Make sure your application is available from your production environment.
- Upload the URL to your startup application to the Canvas assignment.

























