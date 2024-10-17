# Scraping Websites with R
21 October 2024

A workshop covering the basics of collecting data from the Internet using web scraping in R.

## Getting ready
You'll need to install the SelectorGadget extension for the Chrome browser in addition to making sure you're able to access the University's Noteable service. 

### Installing SelectorGadget
1. Open the Chrome browser. If you don't have Chrome, you can install it [here](https://www.google.com/intl/en_uk/chrome/dr/download/?brand=GBSK&ds_kid=43700079594422197&gad_source=1&gclid=CjwKCAjw68K4BhAuEiwAylp3kjjhQbHyA1O0gttd5L0f0a48baOHb_zDWgZlWXotXEhTdnld7o1szRoCRSoQAvD_BwE&gclsrc=aw.ds).
2. Log in to the Chrome browser with your Google account. If you don't have a Google account, you'll need to sign up for one.
3. Follow [this link](https://chromewebstore.google.com/detail/selectorgadget/mhjhnkcfbdhnjickkkdbjoemdmbfginb?hl=en) to download the SelectorGadget browser extension.
4. Make sure SelectorGadget is enabled in your Chrome extension toolbar by clicking on the 'Customize and control Google Chrome' icon in the top righthand corner of your browser pane. Mouse over to 'Extensions' on the dropdown menu and select 'Manage Extensions.' Make sure SelectorGadget is toggled 'on.'

### Accessing R On Noteable

1. Open the login page [here](https://noteable.edina.ac.uk/login).
2. Login with your EASE credentials.
3. Select RStudio as a personal notebook server and press start.
4. Go to File > New Project> Version Control > Git
5. Copy and Paste this repository URL [https://github.com/DCS-training/web-scraping-R-2024](https://github.com/DCS-training/web-scraping-R-2024) as the Repository URL. (The Project directory name will be filled in automatically, but you can change it if you want your folder in Notable to have a different name).
6. Decide where you'd like to store the folder. By default, it will be located in your home directory.
7. Select 'Create Project'.
   
Congratulations! You have now pulled the content of this repository to your Notable server space.

## Overview
This intermediate workshop will teach you how to scrape data from the Internet using R. We will start with a theoretical introduction to web scraping and specific approaches to scraping static websites with a focus on HTML tags. Then, we will practice using rvest to scrape data from a webpage. Finally, we will discuss methods for scraping information from webpages with a more complex structure.  

This is an intermediate-level course. Students must have a basic background in R. This includes understanding the basic data types in R; how to install and load packages; and how to use functions, pipes, and apply/map functions. Alternatively, the 'Introduction to Programming with R and RStudio' course counts as a prerequisite. 

## Schedule
14:00-15:00 

Introduction & housekeeping
Review of web scraping, HTML/CSS, and webpage structure
Hands-on tutorial: scraping a static webpage 

Break

15:10-16:00

Hands-on tutorial: scraping content using an API
Additional methods for web scraping and further resources



## Additional resources
[Reddit community](https://www.reddit.com/r/webscraping/) focused on web scraping

Programming Historian, [Fetching and Parsing Data from the Web with OpenRefine](https://programminghistorian.org/en/lessons/fetch-and-parse-data-with-openrefine) and [Automated Downloading with Wget](https://programminghistorian.org/en/lessons/automated-downloading-with-wget)

University of Southampton [Web Data Research Assistant](https://www.southampton.ac.uk/~lac/WebDataResearchAssistant/)

[Public APIs](https://github.com/public-apis/public-apis) GitHub repo

[Tutorial for browser automation](https://www.youtube.com/watch?v=HpL6EX2kjq4) in Python using Selenium



## License 
All material here collected is free to use but it is covered by a [![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/) license

