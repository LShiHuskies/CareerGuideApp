# Career Guide App
________________________________________________________________________________________________________________________

The objective of this project is to enlighten programmers a search tool and application to provide software developers information of programming languages and jobs available based on programming languages and the average salaries for the jobs and programming languages.

To start, When you create an account, there are certain validations in place to ensure the username and password meet the specifications required for this app. If the username and password are valid, the account will be created and the user will be prompted to the login page where he or she will login.

User can edit their profile, add or delete a programming language of their choice. For this project, we utilized Adzuna API to allow users to search for developer jobs in the New York area by querying with different sets of criteria. Users can click a link to visit the apply page for each job, save jobs for later, and view educational resources about their selected languages of interest.


# How to Install & Run Program
________________________________________________________________________________________________________________________

1. Fork and clone this repository to your local environment.
2. Navigate to the file directory from your terminal.
3. Run 'bundle install' to install all required gems.
4. Run 'rails db:migrate' to set up database.
5. Run 'rails db:seed' to seed the database.
6. Run 'rails s' to start the server.
7. Navigate to http://localhost:3000/
8. Click 'Sign Up' if it is your first time using the app, enter your information, and select your languages of       interest. Click 'Login' if you are a returning user.
9. Click 'Job Search' to execute searches and save desired jobs.
10. Click 'My Profile' to view your saved jobs and educational resources about your selected languages.
11. To edit your information, click 'Edit Profile', make your desired changes, type in your password, then click 'Edit'.
12. When you are done browsing, click 'Log Out'.
