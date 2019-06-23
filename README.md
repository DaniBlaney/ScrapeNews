# ScrapeNews 📰

Use Mongoose and Cheerio to scrape news

https://fake--news.herokuapp.com/

### Overview

This website is focused on providing a single page application for a user to visit a variety of news articles. Additionally, readers will be provided a platform where they are free to share their feelings towards each article they read by submitting comments for the rest of our commmunity to see.

### Before You Begin

- Use `git clone` https://github.com/DaniBlaney/ScrapeNews.git the repository onto your own machine.

- Run `npm install` while in the repository inside of your terminal/git bash. This will load of the necessary npm packages in order for your server to run error-free. This project relies on the following dependencies:
    - axios
    - cheerio
    - express
    - express-handlebars
    - mongoose
    - morgan

- Then run `nodemon server.js` and visit `localhost:3000` in your browser
- Next you will visit `localhost:3000/scrape`
- Once scrape is complete you will go back to `localhost:3000` to view the scraped articles
- If you visit `localhost:3000/articles` you will see json pretty printed of scraped articles
