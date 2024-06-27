# How to Scrape Websites with Node.js and Cheerio
This repository contains the code and guide on how to scrape websites using Node.js and Cheerio. It covers the process of extracting data from web pages, specifically focusing on scraping country codes from a Wikipedia page using Cheerio.

## Prerequisites
Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) installed on your machine.
- A text editor such as [VSCode](https://code.visualstudio.com/) or [Atom](https://atom.io/).

## What is Web Scraping?
Web scraping is the automated process of extracting data from web pages. It enables you to gather data that might not be accessible through APIs.

## What is Cheerio?
Cheerio is a fast and flexible library for parsing HTML and XML data in Node.js. It provides a subset of jQuery's core functionalities, making it easy to navigate and manipulate the DOM.

## Project Setup
To get started with scraping using Cheerio, follow these steps:
### Step 1 - Create a Node Project in your directory
```
npm init -y
```

### Step 2 - Install Dependencies
Install the necessary dependencies using npm:

```
npm install axios cheerios fs
```
This will install axios, cheerio, and fs (for file system operations).

### Step 3 - Understanding the Project Structure
app.js: This is the main file where the scraping logic resides.
countries.json: The output JSON file where scraped data will be stored.

### Step 4 - Scrape Data from Wikipedia
To execute the scraping script:
```
node app.js
```
This script fetches the HTML, parses it using Cheerio, extracts country names and codes, and stores them in countries.json.

### Ethical Considerations
Ensure you have permission to scrape data from any website to avoid legal issues. Respect the terms of service and the site's robots.txt file.

### Resources
Cheerio Documentation
Node.js Documentation

### References
https://www.freecodecamp.org/news/how-to-scrape-websites-with-node-js-and-cheerio/

### Conclusion
Thank you for exploring this repository! Feel free to dive deeper into web scraping and Cheerio by checking out the resources provided. If you have any questions or feedback, please reach out.
