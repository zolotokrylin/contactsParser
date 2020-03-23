# How to use parser

## Preparing environment

- Open Terminal on Mac and go to this folder (example `cd ~/Development/twitter_parser`)
- Run in Terminal `python -m SimpleHTTPServer & open -a Google\ Chrome http://localhost:8000/twitter_search.html`

## Parsing

1. Open Postman and make `GET` request to people-search API (https://api.twitter.com/1.1/users/search.json?q=`${keyWordsPhrase}`&include_entities=false&page=`${pageNumber}`)
2. Copy output and replace the content of JSON file (`twitter.json`) located in this folder
3. Open HTML page, refresh, and see the results
4. Copy result in spreadsheet (https://docs.google.com/spreadsheets/d/1Nd_9ne8-NCOUZtWm5NTwN6W_fNadMPRghNbHk64TGWM/edit#gid=391018449) in the cell which will be parced by relevant formula
4. Repeat 1-3 spect to get a new data in HTML file