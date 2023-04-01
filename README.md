# Scraping Top Repositories for Topics on GitHub

This is a project to scrape the top repositories for topics on GitHub. The purpose of this project is to obtain a list of the top 25 repositories for each topic on GitHub and save the results in a CSV file. 

## Steps to Follow

1. We're going to scrape https://github.com/topics
2. We'll get a list of topics. For each topic, we'll get topic title, title page URL and topic description
3. For each topic, we'll get the top 25 repositiories in the topic from the topic page
4. For each repository, we'll grab the repo name, username, stars and repo URL
5. For each topic, we'll create a CSV file in the following format: Repo Name, Username, Stars, Repo URL.

## Technologies Used

- Python 3
- Beautiful Soup
- Requests
- Pandas


