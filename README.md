# Instagram followers and bio scraper

This is a modified version of the Instagram parser used for scraping followers.

## Changes

1. Fixes implemented to support selenium 4.21.0.
2. Added code for pop-up window scrolling (adapted from this code: https://github.com/chenchih/Python-Project/tree/main/Selenium/Instagram-crawl/1.GetFollowing_FollowerList).
3. The option to set a specific number of followers you want to scrape was removed.
4. Added functionality for scraping Instagram account bios.

## Followers scraper -- Updated 18 June 2024

The script parses Instagram profiles and collects their followers (or following accounts) in the txt file.

## Bio scraper -- Needed to be updated due to changes in Instagram code

This script checks whether the account bio (profile description) or the link in bio contain words from your list.
To begin, you should edit the list with the words you are interested in. Then run the script using the following command: python bio-scraper.py. You will be prompted to input the Instagram usernames you wish to scrape.
Any users whose bios or links contain matching words will be automatically appended to a CSV file.

## Project Context
This project is made for academic use.
