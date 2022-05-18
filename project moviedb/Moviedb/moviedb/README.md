# moviedb

![moviedb](https://moviedb.web.app/readme.png)

> Movies Reviewed by people, for people

moviedb is a movie review website which is focussed on various aspects of films and help people find the best film to watch next.

[moviedb.web.app](https://moviedb.web.app)

[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/5985/badge)](https://bestpractices.coreinfrastructure.org/projects/5985)

## Overview

![moviedb Desktop](https://raw.githubusercontent.com/gorakhnathy7/moviedb/master/Images/desktop.JPG)

## How To Use?

You Need to create an account in order to post reviews and add new movies to the list.

To log in, click on the "log in" button, it only supports Google Sign-in, user details and email will be taken from Google.

It allows only single session per user, so, if you log in, all other sessions will be logged out.

Once you log in, you will be able to add new movie, to add new movies, Search for it in the search bar,

![moviedb Search](https://raw.githubusercontent.com/gorakhnathy7/moviedb/master/Images/search.JPG)

If you click on any movie, it will be added to the list if not already present, and, you will be redirected to the movie page.

On the movie page, you can post reviews, and a 5-star rating. You can only post 1 review per movie.

![moviedb Search](https://raw.githubusercontent.com/gorakhnathy7/moviedb/master/Images/review.JPG)

All your reviews will appear on your user page.

## Tech Stack

* Node.JS
* PostgreSQL
* React.JS

## Entity-Relationship Diagram

![moviedb Search](https://raw.githubusercontent.com/gorakhnathy7/moviedb/master/Images/ERD.png)

## Try Locally

Go to `web/moviedb` and run,

```sh
npm install
npm run start
```
