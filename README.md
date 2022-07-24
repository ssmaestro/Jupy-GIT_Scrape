# Jupy-GIT_Scrape
A web Scraping project to fetch the top 30 repository on GitHub
INTRO -

Web scraping is the process of extracting and parsing data from websites in an automated fashion using a computer program. It's a useful technique for creating datasets   for research and learning.
GitHub: It is a hosting site where developers and programmers can upload the code they create and work collaboratively to improve it. An important feature of GitHub is its version control system. The version control lets coders tweak software—potentially fixing bugs or improving efficiency—without affecting the software itself or risking the experience of any current users.

    In this project we are using the scraping technique to scrap GitHub for the top 30 repositories.
    Tools Used - Python,Beautiful soup,Pandas

Here are the steps i will follow:

    We're going to scrape https://github.com/topics.
    We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description.
    For each topic, we'll get the top 30 repositories in the topic from the topic page.
    For each repository, we'll grab the repo name, username, stars and repo URL.

    For each topic we'll create a CSV file in the following format: Repo Name,Username,Stars,Repo URL

        Example:

        three.js,mrdoob,180700,https://github.com/mrdoob/three.js

        libgdx,libgdx,20300,https://github.com/libgdx/libgdx

