# bitinfochartscraper
Scrapes bitinfocharts data into csv files

# Instructions

1. The attached notebook is designed to be run in google colab - it has all the relevant installs etc at the top of the script

2. Using the Async code takes about 6 minutes to run the entire script (get all data for all coins - 61 last time I ran it)



# TODO
- [x] remove the 'null' from CSV's as they are being saved
- [] add a 'start date' to return only results from that date onwards
- [] make the html response --> pandas df result extraction function more efficient
- [] use nbdev to build script that can be auto run once a day to get the latest numbers and add it to datastore
