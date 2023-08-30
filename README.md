
<h1 align="center">Story Blog</h1>

Story Block is a full stack web application for writing, storing, and sharing stories. Users can create accounts to write and organize their own stories or browse and engage with stories from other users.

The app allows users to perform the following actions:

Create, update, and delete their own stories
Organize stories into categories
Like and comment on other users' stories
View stories in their entirety or previewed on the homepage
Filter stories by different categories, name, keywords
Search for specific stories


## Features
### Navbar
The navbar located at the top of every page allows users to navigate between the home page which displays the latest stories, feeds page showing all new stories posted by followed users, liked page to view all stories the logged in user has liked, sign out option to log out the current user and redirect to login/registration, and profile page to view details of the logged in user including their name, bio, followed/following counts and all their posted stories along with editing profile options, with the active navbar item styled differently to indicate the current section being viewed and providing a simple consistent exploration of the different areas of the blog.

### Home page 
- The home page of our Stories Blog is designed to provide users with a captivating and immersive experience. where individuals can share their unique narratives, insights, and experiences. 
These stories cover a wide array of topics.

- Users can explore these stories, read them in detail, and engage with the authors through comments and likes.
- To enhance user engagement, the home page prominently features a "Most Followed Profiles" section. Users can discover and follow these profiles to stay updated with their latest stories and insights.
- Additionally, the home page incorporates a convenient categorization system, allowing users to explore stories based on their preferred topics of interest. 


### Create Post page 
The create post page allows authenticated users to publish new stories on the platform. It provides a simple form to enter the story title, select a category from a dropdown including options, main content, and upload an image to feature with the story. Published stories become immediately visible on the home page feed and can be accessed via category listings and search. 


### Post Details Page
- The post detail page displays the full content of a single story that was published. It includes the title, content body along with any featured image. For authenticated authors of the story, additional action to edit or delete the post. Editing enables updating any part of the story while deleting removes it permanently from the site.

- Other logged-in users will be able to like and comment on the post. Each time a user likes and comments, the number of likes and comments will go up.

- The comment owner can see the three dots icon button at the top of the comment they made, and by clicking the pencil icon, they can edit their comments. They can also click on the trash icon button to remove their comment from the post.


### Followings Feed Page
  A "Popular Profiles" component is displayed on all major pages of the site. For desktop screens, the top 10 most followed profiles will be featured. On smaller mobile devices, only the top 4 profiles will be shown due to limited screen space.

### Profile Page
The profile page displays a user's public profile information including their image, name, brief bio, count of followers and profiles they follow. For profile owner, additional options are visible in a dropdown menu triggered by a "..." icon to edit the profile details. This allows customizing the bio, changing the profile image, or updating other account settings.

### Liked Page
At this page the users can view all the stories they have liked. It serves as a personalized collection of their favorite content, allowing them to easily revisit and engage with the stories that resonated with them.


### Sign up Page
- The sign up page allows new users to create an account on the platform. It contains a simple form to enter the required details including username and password. and after successfully registering, users are directed to the sign in page.

- The user does not have to sign up if they already have an account; they can just sign in with their existing credentials

### The Sign in Page
The sign in page allows registered users to log into their account on the platform. It contains a simple form to enter the username and password that was used during registration. 


## Technologies Used

The following technologies were used throughout the development of the project:

- ### Language Used

  - [HTML](https://www.w3schools.com/html/)
  - [CSS](https://www.w3schools.com/css/)
  - [Javascript](https://en.wikipedia.org/wiki/JavaScript)

- ### Libraries/Framework Used

  - [React-Bootstrap4](https://react-bootstrap.github.io/)
  - [React js](https://getbootstrap.com/)

- ### Other Technologies

  - [Stackoverflow](https://stackoverflow.com/)
  - [Git](https://git-scm.com/)
  - [Github](https://github.com/)
  - [Gitpod workspace](https://gitpod.io/workspaces)
  - [Heroku](https://dashboard.heroku.com/apps)
  - [Flowchart](https://lucid.app/documents#/documents?folder_id=home)
  - [Font Awsome](https://fontawesome.com/)
  - [Google Fonts](https://fonts.google.com/)
  - [Slack](https://slack.com/intl/en-gb/)
  - [Am i responsive](https://ui.dev/amiresponsive)
 
## Components

- ### The following components have been implemented in this project and reused throughout the app:
  - **Asset:** Using this component, spinners are loaded throughout the site and user messages are displayed if search results are not found.
  - **Avatar:** Users can identify each other more easily with the help of this component, which is used throughout the site for user profile images.
  - **MoreDropdown Page:** In the app, this component is used to edit posts and profiles by users/owners.
  - **SideNavBar:** This component is present on every page of the application. The user can access most site features in one place, from any page, which improves UX. It also collapses into a sidenavbar menu for screen sizes medium and below.
  - **LoggedInIcons:** Using this component, logged in users will be able to access all app links from the sidenavbar.
  - **LoggedOutIcons:** Using this component, guest users will be able to access all app links from the sidenavbar.
  - **NotFound:** Invalid urls were handled by this component. If users try to input invalid urls, they will see a page not found message.
  - **UseRedirect:** When users access a page they shouldn't be viewing, this component redirects them to their home page.
  - **UseClickOutsideToggle:** This component helps collapse a sideNavBar menu by clicking any link within the menu or by clicking outside the menu to collapse it for a smooth UX. Which By default, you must click on each link in the sidenavbar menu and then press the hamburger icon again to collapse it.
 
### User Stories

These are the user stories that were completed within the projects first release, by Epic.


- Navigation
	*  As a user, I want to be able to navigate between different sections of the app so that I can easily find and access the different features and content

- Routing
	*  As a user, I want navigate through pages quickly so that I can view content seamlessly without page refresh

- Authentication - Sign up
    * As a new userI want to create an account easily so that I can start using the app's personalized features.

- Authentication - Sign in
    * As a user I can sign in to the app so that I can access functionality for logged in users

- Authentication - Refreshing access tokens
    * As an authenticated user I want my session to automatically extend so that I can remain logged in without interruption over extended periods of activity

- Navigation: Conditional rendering
    *  As a role I want certain navigation options or screens to change based on my role or permissions so that I am only shown relevant information
 
- Avatar
    *  As a role I want to customize my profile with an avatar so that I can represent myself visually in the app

- Create posts
    *  As a a logged in user I want to be able to make new posts so that I can share my thoughts, content or information with others.

- View a post
    *  As a role I want to be able to open and view details of any post so that I can learn more about shared content items or discussions

- Like a story
    *  As a logged in user I can I can like a post so that I can show my support for the posts that interest me



- View most recent stories
    *  As a user I want to easily see the latest updates so that I can quickly catch up on what's new

- Search
    *  As a role I can search for posts with keywords so that I can find the stories and user profiles I am most interested in

- View liked posts
    *  As a user I want to easily see all the stories I've liked before so that I can revisit interesting or relevant content

- View posts of followed users
    *  As a logged in use I want to see recent stories from profiles I follow so that I can stay updated on their shared content and discussions

- Post page
    *  As a role I want to able to open any post in a full-screen page so that I can view and engage with content in more detail

- Edit post
    *  As a post owner I can edit my post title and description so that I can make corrections or update my post after it was created

- Create a comment
    *  As a logged in user I can comment on any stories so that I can engage in discussion, share feedback and have conversations around shared content.

- Comment Date
    *  As a user I want comment timestamps so that I can understand when feedback, discussions or conversations took place over time.

- View comments
    *  As a user I want easily see any comments on a story so that I can engage with associated discussions and feedback.

- Delete comments
    *  As a owner of a comment I want the ability to remove my own comments so that I can edit discussions and potentially retract statements over time

- Edit a comment
    *  As an owner of a comment I want to modify my comments so that update or correct any feedback, statements, or thoughts over time as needed
 
- Profile Page
    *  As a user I can view other users profiles so that I can see their stories and learn more about them

- Most followed profiles
    *  As a user I want to see a list of the most followed profiles on the site so that I can see which profiles are popular

- User profile - user stats
    *  As a user I can view statistics about a specific user: bio, number of posts, follows and users followed so that learn more about them

- Follow/Unfollow a user
    *  As a logged in user I want to be able to follow or unfollow other users from their profile page so that I can see and remove stories by specific users in my posts feed



- View all stories by a specific user
    *  As a role I can view all the stories by a specific user so that I can catch up on their latest stories, or decide I want to follow them



- Edit Profile 
    *  As a a logged in user I want to be able to edit my profile information such as name, bio, profile picture from my profile page so that that I can change my profile picture and bio



- Update username and password
    *  As a logged in user I want to be able to update my username and password from my profile settings page so that I can change my display name and keep my profile secure


- get stories by category
    *  AAs a user I want to be able to retrieve all stories that are tagged with a specific category so that I can view relevant content.





## Testing
- Manual testing was performed consistently app-wide to ensure a smooth and positive user experience.


## **Deployment**
1. Installing project requirements.
In the terminal run commands pip3 install 
- Green unicorn, server used to run Django on Heroku: *gunicorn*
- PostgreSQL libraries:
*dj_database_url*
*psycopg2*

Create the *requirements.txt* via command in the terminal:
*pip3 freeze --local > requirements.txt*

2. Add env.py
In the main repository create a new file called *"env.py"* in order to store sensitive information. 

In the *env.py file*: import operating system (os) and add following variables: *SECRET_KEY, DATABASE_URL*.
In *settings.py* find a variable called *SECRET_KEY* and cut its value. Paste the value into *env.py*.
Then in the *settings.py* refer to this value via function: *os.environ.get()*

3. Create a heroku app via CLI.
- At first, you have to create an account on *Herokuapp*.
  
4. Create a database on Heroku.
- In the *"Resources"* Tab find *"Heroku Postgres"* and add it to your app.
- Go to *"Settings"*, click on: *"Reveal Vars"* and copy the value of *DATABASE_URL* key.
- Go back to your workspace. In the *env.py* file paste value into the variable *DATABASE_URL*.
- In the *settings.py* file: comment out the *DATABASE* settings and set the *DATABASE* to the Postgres database accessible via *DATABASE_KEY*
- import *dj_database_urls*
- run migrations
You will see that all the migrations are happening because of the database connection. Now the project is using the Heroku database as backend.

5. Prepare your environment
- From the *env.py* copy the value of *SECRET_KEY* variable.
- Go to Herokuapp --> Settings/ reveal and add the following Vars:
SECRET_KEY (value: paste)
HEROKU_HOSTNAME - the url of your heroku app
PORT - 8000
DISABLE_COLLECTSTATIC

6. Create a Procfile
In the *Procfile* (make sure the name is starting with capital letter) you need to specify the commands that are executed by the app on startup. 

7. Commit and push.
In my case, that was the first commit since creating the Django project. In other cases, I would have to make some changes which would allow me to run the push command.
- Commit all changes.
- Push the commit into: origin main
- Push the commit into: heroku main

8. At this stage your app should be correctly deployed on Herokuapp.

9. Connect Github to Heroku
In order to avoid deploying changes in the terminal twice, you can connect your project on Heroku to your Gitpod.
In order to do so - in the *"Deploy"* tab scroll down and click the button *"Connect to GitHub"*. Then set: *deploy automatically*. You can also disable automatic deployment and run your deployment manually at your own chosen time.

10. Final deployment
Before the application will be handeled to the client in the realise 1.0 stage, there are two very important steps to be taken:
- delete DISABLE_COLLECTSTATIC from your confiv VARS in Heroku
- in the setting.py file, set the **DEBUG=False** in order to protect sensitive information - *IMPORTANT!*








<h1 align="center">Story Blog API</h1>

The [Story Blog API](https://story-blog-24bc3af065de.herokuapp.com/) a simple blog application built with Django Rest Framework where users can post their stories. The application provides API endpoints for creating, retrieving, updating, and deleting stories.

## Features
- profiles
- followers
- stories
- likes
- comments
- categories


## __Technologies Used__

### ***Languages Used***

-   [Python](https://en.wikipedia.org/wiki/Python_(programming_language))

### ***Frameworks, Libraries & Programs Used***
1. [Django:](https://www.djangoproject.com/)
    - Django was used to create the web application.

1. [Django Rest Framework:](https://www.django-rest-framework.org/)
    - The Django rest framework was used to simplify the process between the back and front ends.

1. [ElephantSQL:](https://www.elephantsql.com/)
    - ElephantSQL was used to host the database.

1. [Git:](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.

1. [Heroku:](https://heroku.com/)
    - Heroku was used for the deployed application.

## __Testing__

### ***Manual Testing***

- Manual testing was performed throughout development, ensuring the database was being updated as expected when creating, reading, updating or deleting data, where appropriate.

- Screenshots are provided for the Profiles app, testing was carried out equally for all other apps, and is noted below. 

#### **Profiles App**
- List View (Read if logged in):
    ![List View](./docs/readme/images/testing/manual_testing_profiles_list_logged_in.png)
- List View (Read if not logged in):
    ![List View](./docs/readme/images/testing/manual_testing_profiles_list_not_logged_in.png)
- Detail View (Read, Update if owner):
    ![Detail View](./docs/readme/images/testing/manual_testing_profiles_detail_owner.png)
- Detail View (Read if not owner):
    ![Detail View](./docs/readme/images/testing/manual_testing_profiles_detail_not_owner.png)
- Detail View (Read if not logged in):
    ![Detail View](./docs/readme/images/testing/manual_testing_profiles_detail_not_logged_in.png)

#### **Followers App**
- List View (Read, Create if logged in)
- List View (Read if not logged in)
- Detail View (Read, Delete if owner)
- Detail View (Read if not owner)
- Detail View (Read if not logged in)

#### **Stories App**
- List View (Read, Create if logged in)
- List View (Read if not logged in)
- Detail View (Read, Update, Delete if owner)
- Detail View (Read if not owner)
- Detail View (Read if not logged in)

#### **Likes App**
- List View (Read, Create if logged in)
- List View (Read if not logged in)
- Detail View (Read, Delete if owner)
- Detail View (Read if not owner)
- Detail View (Read if not logged in)

#### **Comments App**
- List View (Read, Create if logged in)
- List View (Read if not logged in)
- Detail View (Read, Update, Delete if owner)
- Detail View (Read if not owner)
- Detail View (Read if not logged in)


### ***Fixed Bugs***

#### Event Date Bug:
- When editing an event on the front-end app via the EventEditForm the date field was not populated with the existing date previously created by the user via the EventCreateForm. 

- On further inspection in the console, this error was caused by the date format not being the same as the form required, as I had applied a DATE_FORMAT in the back-end API settings to make the date more human-friendly and readable e.g. 01/05/2023. 
![Event Dates Bug](./docs/readme/images/testing/bug_date_events.png)

- As [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/date) states, this format comes from the browser and can not be changed. 

- In order to avoid this issue, the date format was reverted to the required `yyyy-MM-dd` format. As a future implementation, a workaround could be to convert the format from one to the other with JavaScript as required.

#### Database Bugs:
- I had recurring bugs with my database, with there being a disconnect between the migrated models and existing data in the database.

- As an example, I would get a ProgrammingError, saying that `content` on `polls` didn't exist:
![Programming Error Bug](./docs/readme/images/testing/bug_programming_error.png)

- However, when checking the database, the `content` field on `polls` did indeed exist:
![Database Existing Fields](./docs/readme/images/testing/bug_exisitng_fields.png)

- The solution ultimately was to either reset the database on [Elephant SQL](https://www.elephantsql.com/) or delete it entirely, create a new instance and connect it up to the API via env.py and Heroku config vars. Followed by migrating all the models again, and deploying to Heroku. 

- This re-ocurring issue caused a lot of time to be wasted both on having to reset the database and recreate the lost data.

### ***Known Bugs***

#### Default Image Bug
- When creating an event there is an error on the front-end regarding the default image. When a user tries to create an event but doesn't upload an image, the default image specified on the back-end should apply. However, the form throws an error:
    ![Default Image Bug Front End](/docs/readme/images/testing/bug_default_image_front_end.png)

- However, this error doesn't occur on the back-end and the default image is applied without issue:
    ![Default Image Bug Back End](/docs/readme/images/testing/bug_default_image_back_end.png)

- Despite using the identical code as on the Moments Walkthrough on posts, checking that Cloudinary was connected up properly, searching on Google and Slack, and asking tutor support, no solution was found.

- The workaround was to include an image required info text on the form to ensure users would always select an image.

#### Poll and Discussion Bug
- A poll and discussion model were created on the back-end to be used with events. Though the back-end functionality exists and doesn't cause any issues, the front-end functionality was impossible to implement. My assumption was that the choice fields on polls was causing an issue and that my front-end code was not correct. However, when implementing the discussion on events, which is identical to comments on posts, the same error appeared and nothing could be done about it.

- Recurring front-end TypeError:
    ![Poll Bug Error](/docs/readme/images/testing/bug_poll_error.png)

- Front-end displaying data correctly when created in the back-end:
    ![Poll Bug Back End Data](/docs/readme/images/testing/bug_poll_back_end_data.png)

- Ability to create the data in the back-end: 
    ![Poll Bug Back End Functionality](/docs/readme/images/testing/bug_poll_back_end_functionality.png)

- Ultimately the poll and discussion functionality was therefore removed.

[//]: <> (Deployment section taken from Dave Horrocks, and credited in the Content section of the Credits)
## __Deployment__

### ***Heroku***

1. Navigate to your [Heroku dashboard](https://dashboard.heroku.com/apps)
2. Click "New" and select "Create new app".  
  ![New heroku](./docs/readme/images/deployment/heroku-new.png)
3. Input a meaningful name for your app and choose the region best suited to
  your location.  
  ![Create new app](./docs/readme/images/deployment/heroku-create.png)
4. Select "Settings" from the tabs.  
  ![Settings tab](./docs/readme/images/deployment/heroku-settings.png)
5. Click "Reveal Config Vars".  
 ![Config vars button](./docs/readme/images/deployment/heroku-config-vars.png)
6. Input all key-value pairs as necessary from the `.env` file. **Ensure DEBUG
   and DEVELOPMENT are not included**.
   ![Config vars](./docs/readme/images/deployment/heroku-config-var.png)
7. Click "Add buildpack".  
 ![Add buildpack](./docs/readme/images/deployment/heroku-add-buildpacks.png)
8. Add "python" from the list or search if necessary, remember to
 click save.  
 ![Select buildpacks](./docs/readme/images/deployment/heroku-select-buildpacks.png)
9. Select "Deploy" from the tabs.  
![Settings tab](./docs/readme/images/deployment/heroku-deploy-tab.png)
10. Select "GitHub - Connect to GitHub" from deployment methods.  
 ![Select GitHub](./docs/readme/images/deployment/heroku-select-github.png)
11. Click "Connect to GitHub" in the created section.  
 ![Connect to GitHub](./docs/readme/images/deployment/heroku-connect-github.png)
12. Search for the GitHub repository by name.  
13. Click to connect to the relevant repo.
14. Either click `Enable Automatic Deploys` for automatic deploys or `Deploy
 Branch` to deploy manually. Manually deployed branches will need
 re-deploying each time the repo is updated.  
 ![Heroku deploy branch](./docs/readme/images/deployment/heroku-deploy-branch.png)
15. Click `View` to view the deployed site.  
    ![Heroku view](./docs/readme/images/deployment/heroku-view.png)
16. The live site can also be accessed from your repo in GitHub from the
    environments section of the repo.

The site is now live and operational

## __Credits__

### ***Code***

- The following were used as references to help with writing the HTML, CSS, JavaScript and Python code:
  - [Code Institute LMS](https://learn.codeinstitute.net/ci_program/diplomainsoftwaredevelopmentadvancedfrontend), in particular the [Django Rest Framework Walkthrough](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+DRF+2021_T1/courseware/f775d54df4da44d18309888b3fe884f7/bc5fbada70104d489aa0363a03d8bda8/)
  - [W3Schools](https://www.w3schools.com/) 
  - [Stack Overflow](https://stackoverflow.com/)
  - [MDN Web Docs](https://developer.mozilla.org/en-US/)
  - [Django Rest Framework Documentation](https://www.django-rest-framework.org/)

### ***Content***

- The Deployment section in the README was taken from the masterful [Dave Horrocks](https://github.com/DaveyJH), who put it so much better than I could! 

### ***Acknowledgements***

Massive thanks to: 

- My mentor, [Lauren-Nicole Popich](https://github.com/CluelessBiker), for guiding me and giving me helpful feedback and advice - and for giving me confidence when I didn't believe in myself!

- My fellow Code Institute students and friends for their help, generous feedback, and incredible knowledge:
  
  - [Abi Harrison](https://github.com/Abibubble)
  - [Dave Horrocks](https://github.com/DaveyJH)
  - [Emanuel Silva](https://github.com/manni8436)
  - [Kera Cudmore](https://github.com/kera-cudmore)
  - [Megan Vella](https://github.com/Medusas71)
  - [Monika Hrda](https://github.com/monika-hrda)
  - [Natalie Alexander](https://github.com/natalie-kate)
  - [Sandra Atino](https://github.com/Atinos31)
  - [Suzy Bennett](https://github.com/suzybee1987)

- Tutor Support, Student Care and the Slack Community at [Code Institute](https://codeinstitute.net/global/) for their support.

- And last but not least, my husband [Antoine Masson](https://www.linkedin.com/in/antoine-masson-55b65094/) for helping me through the stressful moments and for supporting us financially while I make this big career change. 
