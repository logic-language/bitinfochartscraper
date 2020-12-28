# bitinfochartscraper
Scrapes bitinfocharts data into csv files

# Instructions

1. The attached notebook is designed to be run in google colab - it has all the relevant installs etc at the top of the script

2. Using the Async code takes about 6 minutes to run the entire script (get all data for all coins - 61 last time I ran it)




# TODO
- [x] remove the 'null' from CSV's as they are being saved
- [ ] add a 'start date' to return only results from that date onwards
- [ ] make the html response --> pandas df result extraction function more efficient
- [ ] use nbdev to build script that can be auto run once a day to get the latest numbers and add it to datastore

# Results Summary

Values is a count of the total fields of numerical data in each spreadsheet.  Also available in sumamry.csv

| full_name        | coin            | values |
|------------------|-----------------|--------|
| bitcoin          | btc             | 36708  |
| litecoin         | ltc             | 30004  |
| dogecoin         | doge            | 22697  |
| dash             | dash            | 22538  |
| vertcoin         | vtc             | 20239  |
| reddcoin         | rdd             | 19494  |
| blackcoin        | blk             | 19319  |
| feathercoin      | ftc             | 18740  |
| ethereum         | eth             | 15315  |
| ethereum classic | etc             | 14422  |
| monero           | xmr             | 13469  |
| zcash            | zec             | 11990  |
| bitcoin gold     | btg             | 11227  |
| bitcoin cash     | bch             | 11107  |
| xrp              | xrp             | 6646   |
| bitcoin sv       | bsv             | 6406   |
| potcoin          | potcoin         | 3979   |
| syscoin          | syscoin         | 3864   |
| digibyte         | digibyte        | 2610   |
| vericoin         | vericoin        | 2508   |
| unobtanium       | unobtanium      | 2230   |
| viacoin          | viacoin         | 1886   |
| siacoin          | siacoin         | 1644   |
| whitecoin        | whitecoin       | 1175   |
| einsteinium      | einsteinium     | 1103   |
| stealthcoin      | stealthcoin     | 1025   |
| execoin          | execoin         | 407    |
| savecoin         | savecoin        | 139    |
| ghostcoin        | ghostcoin       | 68     |
| namecoin         | nmc             | 0      |
| novacoin         | nvc             | 0      |
| batcoin          | batcoin         | 0      |
| hotcoin          | hotcoin         | 0      |
| suncoin          | suncoin         | 0      |
| bitconnect       | bitconnect      | 0      |
| topcoin          | topcoin         | 0      |
| navajocoin       | navajocoin      | 0      |
| polcoin          | polcoin         | 0      |
| worldcoin        | worldcoin       | 0      |
| betacoin         | betacoin        | 0      |
| isracoin         | isracoin        | 0      |
| socialcoin       | socialcoin      | 0      |
| phoenixcoin      | phoenixcoin     | 0      |
| badgercoin       | badgercoin      | 0      |
| elacoin          | elacoin         | 0      |
| iconomi          | iconomi         | 0      |
| paycoin          | paycoin         | 0      |
| jackpotcoin      | jackpotcoin     | 0      |
| netcoin          | netcoin         | 0      |
| urocoin          | urocoin         | 0      |
| cloakcoin        | cloakcoin       | 0      |
| quebecoin        | quebecoin       | 0      |
| cornerstonecoin  | cornerstonecoin | 0      |
| bitstar          | bitstar         | 0      |
| leafcoin         | leafcoin        | 0      |
| ybcoin           | ybcoin          | 0      |
| minerals         | minerals        | 0      |
| bitcoinscrypt    | bitcoinscrypt   | 0      |
| stories          | stories         | 0      |
| zetacoin         | zetacoin        | 0      |
| aircoin          | aircoin         | 0      |
| shadowcoin       | shadowcoin      | 0      |
