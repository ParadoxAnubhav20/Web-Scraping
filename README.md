# GitHub Web Scraping Project

## Objective
The goal of this project is to scrape data from GitHub's topics and repositories, including topic titles, URLs, descriptions, repository names, usernames, stars, and repository URLs. We will organize this data into CSV files for further analysis and use.

## Data Extraction Process

### Step 1: Scraping Topics

- We will scrape [GitHub Topics](https://github.com/topics) to get a list of available topics.
- For each topic, we will extract the following information:
  - Topic Title
  - Topic Page URL
  - Topic Description

### Step 2: Scraping Top Repositories within Each Topic

- For each topic, we will follow the topic page URL to access the top repositories within that topic.
- For each repository, we will collect the following details:
  - Repository Name
  - Username
  - Stars
  - Repository URL

### Step 3: Organizing Data into CSV Files

- For each topic, we will create a separate CSV file to store the repository data.
- The CSV files will be named after the respective topics.
- Each CSV file will have the following columns:
  - Repository Name
  - Username
  - Stars
  - Repository URL
