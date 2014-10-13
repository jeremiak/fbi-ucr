tools to scrape and parse tables from the FBI's Uniform Crime Report site

currently only scrapes data for the "one year of data" option. resurrecting this and
the parser isn't working yet.

i did this just to get more practice with mechanize. code quality isn't great.

## usage

`python get.py` and it will download all the data into a file per year per state.

## installation

all you need is `mechanize` so you can either `pip install mechanize` or `pip install -r requirements.txt`
