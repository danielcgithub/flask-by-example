# Flask by Example

## Introduction

Building a Flask app that calculates word-frequency pairs based on the text from a given URL. <br>
Full Stack.

## Breakdown of parts

+ Part One: Set up a local development environment and then deploy both a staging and a production environment on Heroku. <br>
+ Part Two: Set up a PostgreSQL database along with SQLAlchemy and Alembic to handle migrations.<br>
+ Part Three: Add in the back-end logic to scrape and then process the word counts from a webpage using the requests, BeautifulSoup, and Natural Language Toolkit (NLTK) libraries.<br>
+ Part Four: Implement a Redis task queue to handle the text processing.<br>
+ Part Five: Set up Angular on the front-end to continuously poll the back-end to see if the request is done processing.<br>
+ Part Six: Push to the staging server on Heroku – setting up Redis and detailing how to run two processes (web and worker) on a single Dyno.<br>
+ Part Seven: Update the front-end to make it more user-friendly.<br>
+ Part Eight: Create a custom Angular Directive to display a frequency distribution chart using JavaScript and D3.
