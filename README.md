# ca-fires-history

Tracking fire data from [www.fire.ca.gov/incidents](https://www.fire.ca.gov/incidents)

## As-of June 28th 2023

The scraped data is stored in [incidents-june-2023-format.json](incidents-june-2023-format.json)

## Up to March 2rd 2023

The scraped data was stored in [incidents.json](incidents.json)

Background on this project: [Git scraping: track changes over time by scraping to a Git repository](https://simonwillison.net/2020/Oct/9/git-scraping/)

-----

We should probably transform this data to our own public database of mosques in the uk 

We can find duplicates through the lon and lat being within range of an existing record

There is no benefit to keeping the files in csv format we would rather they be in sqlite format
