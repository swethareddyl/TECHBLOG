# 14 Model-View-Controller (MVC): Tech Blog

## Your Task

Writing about tech can be just as important as making it. Developers spend plenty of time creating new applications and debugging existing codebases, but most developers also spend at least some of their time reading and writing about technical concepts, recent advancements, and new technologies. A simple Google search for any concept covered in this course returns thousands of think pieces and tutorials from developers of all skill levels!

Your task this week is to build a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. You’ll build this site completely from scratch and deploy it to Heroku. Your app will follow the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## User Story


As a developer who writes about tech,I want a CMS-style blog site so that I can publish articles, blog posts, and my thoughts and opinions


## Acceptance Criteria


Given a CMS-style blog site
When I visit the site for the first time,then I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
When I click on the homepage option,then I am taken to the homepage
When I click on any other links in the navigation,then I am prompted to either sign up or sign in
When I choose to sign up,then I am prompted to create a username and password
When I click on the sign-up button,then my user credentials are saved and I am logged into the site
When I revisit the site at a later time and choose to sign in,then I am prompted to enter my username and password
When I am signed in to the site,then I see navigation links for the homepage, the dashboard, and the option to log out
When I click on the homepage option in the navigation,then I am taken to the homepage and presented with existing blog posts that include the post title and the date created
When I click on an existing blog post,then I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
When I enter a comment and click on the submit button while signed in,then the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
When I click on the dashboard option in the navigation,then I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
When I click on the button to add a new blog post,then I am prompted to enter both a title and contents for my blog post
When I click on the button to create a new blog post,then the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
When I click on one of my existing posts in the dashboard,then I am able to delete or update my post and taken back to an updated dashboard
When I click on the logout option in the navigation,then I am signed out of the site
When I am idle on the site for more than a set time,then I am able to view comments but I am prompted to log in again before I can add, update, or delete comments


## Mock-Up

The following animation demonstrates the application functionality:



## Github-Link
