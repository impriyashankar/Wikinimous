# Wikinimous - anonymous Wiki-like app  

> An app where anyone can create a new article or update an existing one.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)


## General Information
The app loads a feed of random articles(through `faker` gem). The user can select any article, update or delete - and also create new articles to be appended to the feed.


## Technologies Used
- Ruby on Rails


## Setup

1. Generate the Article model through the  Rails generator
2. Add the faker gem to your `Gemfile` and run `bundle install`. Seed 10 fake articles.
3. Geneenerate controller and use `resources` to implement actions.
4. Implement front-end
