<h1 align="center">EV Car Dealer</h1>

[View the live project here.](https://ev-car-dealer-project.herokuapp.com/)

Site creation is part of the milestone three project for the Code Institute, focusing on the newly acquired backend development skills of CRUD using HTML, CSS, jQuery, JavaScript, Python, Flask and MongoDB. 

<h2 align="center"><img src="#"></h2>

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        

    -   #### Returning Visitor Goals

        

    -   #### Frequent User Goals
        

-   ### Design
    -   #### Colour Scheme
        -   
    -   #### Typography
        -       -   #### Imagery
        -   

*   ### Wireframes

    -   Home Page Wireframe - [View](https://github.com/PhilipWilliams0/ev-car-dealer/tree/main/static/wireframes)

## Features

-   Responsive on all device sizes

-   Interactive elements

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - 
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - 

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

   

-   #### Returning Visitor Goals

  

    

-   #### Frequent User Goals

   

### Further Testing

-   

### Known Bugs

-   

## Deployment

### Local Deployment

- I have created EV Car Dealer using Github, from there I used VSCODE to write my code. Then I used commits to git followed by "git push" to my GitHub repository. 

- This project can be run locally by following the following steps: You will need to adjust them depending on your IDE. You can find more information about installing packages using pip and virtual environments [here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)


### Clone this project:

-  From the application's repository, click the "code" button and download the zip of the repository. Alternatively, you can clone the repository using the following line in your terminal: git clone https://github.com/PhilipWilliams0/ev-car-dealer
-  Access the folder in your terminal window and install the application's required modules using the following command: pip3 install -r requirements.txt
-  Sign-in or sign-up to MongoDB and create a new cluster
-  Within the Sandbox, click the collections button and after click Create Database (Add My Own Data) called ev_car_dealer
-  Set up the following collections: users, products and reviews. Click to see the exact Database Structure
-  Under the Security menu on the left, select Database Access.
-  Add a new database user, and keep the credentials secure
-  Within the Network Access option, add IP Address 0.0.0.0
-  In your IDE, create a file containing your environmental variables called env.py at the root level of the application. It will need to contain the following lines and variables: import os

-

     os.environ  ["PORT"] = "5000"
     os.environ  ["SECRET_KEY"] = "YOUR_SECRET_KEY" 
     os.environ  ["DEBUG"] = "True"
     os.environ  ["MONGO_URI"] = "YOUR_MONGODB_URI"
     os.environ  ["MONGO_DBNAME"]= "DATABASE_NAME"


- Please note that you will need to update the SECRET_KEY with your secret key, as well as the MONGO_URI and MONGO_DBNAME variables with those provided by MongoDB. Tip for your SECRET_KEY, you can use a Password Generator to have a secure secret key.
- I recommend a length of 24 characters and exclude symbols. To find your MONGO_URI, go to your clusters and click on connect. Choose to connect your application and copy the link provided. 

- Don't forget to update the necessary fields like password and database name. If you plan on pushing this application to a public repository, ensure that env.py is added to your .gitignore file.

-	The application can now be run locally. In your terminal, type the following command python3 app.py.
To deploy your project on Heroku, use the following steps:
-	Login to your Heroku account and create a new app. Choose your region.
-	Ensure the Procfile and requirements.txt files exist are present and up-to-date in your local repository.

### Requirements:
    - pip3 freeze --local > requirements.txt

### Procfile:

    - echo web: python app.py > Procfil

- The Procfile should contain the following line:

      - web: python app.py

- And then:
	- Scroll down to the "deployment method"-section. Choose "Github" for automatic deployment.
	- From the inputs below, make sure your GitHub user is selected, and then enter the name for your repo. Click "search". When it finds the repo, click the "connect" button.
	- Scroll back up and click "settings".
	- Scroll down and click "Reveal config vars".
	- Set up the same variables as in your env.py (IP, PORT, SECRET_KEY, MONGO_URI and MONGODB_NAME):!You shouldn't set the DEBUG variable is under config vars, only in your env.py to prevent DEBUG from being active on the live website.

	     - PORT = 5000
	     - SECRET_KEY = YOUR_SECRET_KEY
	     - MONGO_URI = YOUR_MONGODB_URI
	     - MONGO_DBNAME = DATABASE_NAME

•	Scroll back up and click "Deploy". Scroll down and click "Enable automatic deployment".
•	Just beneath, click "Deploy branch". Heroku will now start building the app. When the build is complete, click "view app" to open it.
•	To commit your changes to the branch, use git push to push your changes.
## Credits

### Code

-   The full-screen hero image code came from this [StackOverflow post](https://stackoverflow.com)


-   [MDN Web Docs](https://developer.mozilla.org/) : For Pattern Validation code. Code was modified to better fit my needs and to match an Irish phone number layout to ensure correct validation. Tutorial Found [Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/tel#Pattern_validation)

### Content

-   All content was written by the developer.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   All Images were created by the developer.

### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   Tutor support at Code Institute for their support.