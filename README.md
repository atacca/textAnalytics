# textAnalytics
Place to dump my R code for text analytics stuff. Blurb for each item below.


#### TEMPLATE WEBPAGE SCRAPER ####
This is an unsophisticated webpage scraper using rvest. At the moment it simply reads in 30 URLs from a txt file that you need to set up beforehand, then scrapes those pages based on the rvest::html_nodes() you've set—you'll need to inspect the webpages beforehand to determine the most applicable node for that site.

It's constrained to 30 URLs, no more no less—if you're doing multiple sites, it'll be using the values from the previous iteration/webpage assigned to that variable, which adds duplicate data. You could simply cut out excess pages you don't need, or add extras, but I'll need to change this into a loop that iterates through each supplied URL (I just need to work out how to do that).

