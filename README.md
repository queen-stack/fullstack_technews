<h1 align="center">Tech News Blog</h1>
  
<p align="center">
    <img src="https://img.shields.io/badge/javascript-yellow" />
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/sequelize-purple"  />
    <img src="https://img.shields.io/badge/handlebars-red"  />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
    <img src="https://img.shields.io/badge/license-MIT-black.svg" />
</p>
   
## Description

🔍 A mysql database and CMS-style Blog built using Model View Controller (MVC) paradigm. 
  <br>Built using MySQL2, Express, Sequelize, Handlebars and dotenv. <br>
   A tech news website where users can post, upvote, and comment on links to news articles.<br>
   Users who are logged in will be able to update and delete their existing posts through a dashboard UI.

**[Deployed Application](https://_)**
  
💻 Below are screenshots of the application:
  
![create sign up: news blog](./public/stylesheets/images/create_acct.png)
![login: news blog](./public/stylesheets/images/login.png)
![homepage: newsblog](./public/stylesheets/images/homepage.png)


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
```
   
## Table of Contents
- [Description](#description)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
💾   
  
`npm init`

`npm install`
  
## Backend Usage
💻   
  
Run the following command at the root of  project and answer the prompted questions:

`mysql -uroot -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm start`

## Frontend Usage
💻 
`required login to create a blog: username, password`

`Homepage displays all stories with title.  User can select to create a post, navigate to dashboard of all blogs user has created.  User can Comment on other Users Blogs. `

`Dashboard allows user to edit post, save edits made or delete post.`
`If a deletion is done from the blog - this is not able to be reversed! Blogger beware!`

## Testing
* see test file for TDD testing

## Contributing
:octocat: [Jenifer Queen](https://github.com/queen-stack)

## Questions
✉️ Contact me with any questions: [email](mailto:jenf_queen@yahoo.com) , [GitHub](https://github.com/queen-stack)<br/>

