# Community Tech Blog

## Description
For this assignment we were tasked to make a blog where the user can signup/login, post, comment, and edit/delete the comments and posts. The dashboard is were you are able to view and comment on other users post if you do not have an account you will be redirected to the login page. This assignment was very tough for me, however the finished product was worth it and I did learn a lot in the end.

## Table of Contents
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Deployed Link](#deployed-link)
* [Usage](#usage)
* [Tech](#tech)
* [Example](#example)
* [Screenshots](#screenshots)
* [Notes](#Notes)
* [Questions](#questions)

## User Story
```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```
## Acceptance Criteria
```
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view posts and comments but I am prompted to log in again before I can add, update, or delete posts
```
## Deployed Link
No link :(

## Usage
1. Open terminal
2. Run `mysql -uroot -p` then enter password :)
3. Type `quit`
4. Create a `.env` file, contain the following:
```
DB_NAME=''
DB_USER=''
DB_PASSWORD=''
DB_SESSION_SECRET=''
```
5. Run `Server.js`
6. Open `localhost:3001`
7. (Less fun way) Skip all this and use the deployed link
## Tech
```
- Javascript
- Node.js
- Heroku
```
### NPM Packages
```
- Express
- Dotenv
- Mysql2
- Sequelize
- Bcrypt
- Connect-session-sequelize
- Express-handlebars
- Express-session
```
## Example
https://watch.screencastify.com/v/Po58vNFoxYMZ3TMsIrJU

## Screenshots
<img width="1439" alt="Screenshot 2023-06-23 at 10 48 00 PM" src="https://github.com/TianPnce/Community-Blog/assets/122128252/e0fc6cb0-fe2b-4978-8dc0-094299aa80e2">
<img width="1439" alt="Screenshot 2023-06-23 at 10 48 14 PM" src="https://github.com/TianPnce/Community-Blog/assets/122128252/9e4d2039-4e2d-4796-8595-4913b16e16cd">

## Notes
I did have a pretty hard time with this assignment, mainly with deploying with Heroku that I am still having issues with deploying. Everything was trial and error, and I am proud of the outcome.

## Questions
[TianPnce](https://github.com/TianPnce)
