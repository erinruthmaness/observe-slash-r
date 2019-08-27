# The Charlotte Observe/r
This is a web app that lets users view and leave comments on the latest news out of the Charlotte area according to reddit users.  The app uses axio, Mongo, and Cheerio to scrape the latest reddit posts submitted to r/Charlotte, runs on an express node server, and displays information with handlebars.  You can visit the fully-deployed site on Heroku here: 

# Overview

Whenever a user visits the Charlotte Observe/r, the app scrapes the latest popular posts from r/Charlotte and displays them for the user. The headline and URL of each scraped article is saved to the application database.

Users are able to leave comments on the articles displayed and can revisit them later. The comments are saved to the database and associated with their articles. Users are able to delete comments left on articles. All stored comments are visible to and deletable by every user.