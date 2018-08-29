# textAnalytics
Place to dump my R code for text analytics stuff. Blurb for each item below.


#### CORPUS ANALYSIS ####
The goal with this is to automate a lot of the initial analysis of a corpus and output it to a multi-tab spreadsheet (plus some plots). It's an active work in progress, so I'm updating it fairly regularly. Requires a folder of files* ready to go, and then a bit of iterative hands-on to build up the custom stopwords file. At the moment it's set up for PDFs only, which might be a little questionable to some. It's ok for me as that's what I'm currently working with, but that requirement will change before too long. Eventually I'll set it up to look for several formats in the folder.

*Note: I name my corpus files by a specific convention (institution_docName_type_country_year). Those elements become the docvars.


#### TEMPLATE WEBPAGE SCRAPER ####
This is a straightforward scraper, set as a function and looped. Required is a list of URLs and a node common between them. Writing to the output file is set as append, so if there isn't one common node, you can iterate through as many times as you like. There's no sophistication to this, so it should be pretty easy to use.
