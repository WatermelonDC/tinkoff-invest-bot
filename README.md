# tinkoff-invest-bot

ML Bot for Tinkoff Investment.

## Configure

Project runs  with Python 3.8+.

### Python requirements

Install required libraries with command: `pip3 install -r requirements.txt`.

### Tinkoff token

Add token for Tinkoff Open API into file `token.txt` in root folder.


## Structure

* global_rank_parser - tool for parsing top X companies from Forbes rank.
* candles_loader - tool for load historical data for top X companies from global_rank_parser export.
