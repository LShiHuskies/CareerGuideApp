# Career Guide App

<img width="400" height="400" alt="screen shot 2018-08-13 at 3 29 42 pm" src="https://user-images.githubusercontent.com/34640293/44053808-c7ca3438-9f0e-11e8-965b-a3d5879505cf.png">

The objective of this project is to enlighten programmers a search tool and application to provide software developers information of programming languages and jobs available based on programming languages and the average salaries for the jobs and programming languages.

To start, When you create an account, there are certain validations in place to ensure the username and password meet the specifications required for this app. If the username and password are valid, the account will be created and the user will be prompted to the login page where he or she will login.

User can edit their profile, add or delete a programming language of their choice. For this project, we utilized Adzuna API to allow users to search for developer jobs in the New York area by querying with different sets of criteria. Users can click a link to visit the apply page for each job, save jobs for later, and view educational resources about their selected languages of interest.

# How to Install & Run Program

1. Fork and clone this repository to your local environment.
2. Navigate to the file directory from your terminal.
3. Run 'bundle install' to install all required gems.
4. Run 'rails db:migrate' to set up database.
5. Run 'rails db:seed' to seed the database.
6. Run 'rails s' to start the server.
7. Navigate to http://localhost:3000/
8. Click 'Sign Up' if it is your first time using the app, enter your information, and select your languages of       interest. Click 'Login' if you are a returning user.

<div display="inline">
<img width="400" height="300" margin-right="10px" alt="screen shot 2018-08-13 at 3 33 08 pm" src="https://user-images.githubusercontent.com/34640293/44053629-423cde2e-9f0e-11e8-8ea8-6b1adcb25ceb.png">

<img width="400" height="300" alt="screen shot 2018-08-13 at 3 34 39 pm" src="https://user-images.githubusercontent.com/34640293/44053697-716f41b4-9f0e-11e8-81ea-cbbb76e73e1a.png">
</div>


9. Click 'Job Search' to execute searches and save desired jobs.
10. Click 'My Profile' to view your saved jobs and educational resources about your selected languages.
11. To edit your information, click 'Edit Profile', make your desired changes, type in your password, then click 'Edit'.
12. When you are done browsing, click 'Log Out'.




To see an example of user workflow, watch the tutorial at https://www.youtube.com/watch?v=m0CuCJgi1cM&feature=youtu.be.

# API Reference

We use Adzuna API (https://developer.adzuna.com/). Please feel free to register and create your own account.

# Credits

Inspired by Linkedin and Indeed
Collaborators: Jeffrey Hwang, Ryan Ghaida, Sydney Garay and Louis Shi
