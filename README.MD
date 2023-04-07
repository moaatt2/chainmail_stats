# Chainmail Stats

## Overview

The purpose of this project is to answer questions about chainmaille using data from the [Maille Artisans International League website](https://www.mailleartisans.org/), in addition to generating a dataset for others to if they wish.

## Responsibility

Looking at [M.A.I.L.'s robots.txt](https://www.mailleartisans.org/robots.txt) private use bots are allowed to request the weave article pages with a 10 second delay between each request.

## Steps

1. Determine what questions to answer.
    * What are the most commonly used Aspect ratios.
        * How does this change with regard to having articles made / single AR weaves only.
    * What tags are the most popular?
    * How many new weaves came out over time? 
2. Determine what information to get from the pages to answer those questions.
    - [x] The name of each weave.
    - [x] The aspect ratios for the weaves.
    - [x] The number of articles submitted about the weave.
    - [x] The tags for each weave.
    - [x] The upload/edit dates for each weave.
3. Find a set of articles to use as a test case and build scraping of desired data.
4. Get the desired data for all articles.
5. Use the gathered data to answer the questions.

## Future Improvements

* Improve parsing of web-scraping to avoid improper strings in Min AR values.