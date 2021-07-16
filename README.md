# WebScrape_GridConditions
Web Scrape of ERCOT's real-time Grid Conditions

In Texas, the winter storm in February 2021 wreaked havoc on the electricity grid. Many complaints were filed to the Electricity Reliability Council of Texas (ERCOT) the grid operator. One of the main complaints was the "lack of communication" on how the grid got so bad, so quickly. Since then, ERCOT has taken steps to make data more readily available.

ERCOT has revamped their homepage to show "current electric grid conditions" in real-time. This data is updated dynamically as information about the status of the grid comes in. 

This repository includes notebooks for web scraping code to gather that data, as well as CSVs of those results. The notebook runs the webscrape only for 1-minute, however a 15-minute CSV has been included to show how that data changes over more time.