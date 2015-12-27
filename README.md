# SteamMarketTool
Steam Market Tool (TamperMonkey)

This is first public version of the Steam Market Tool.

Included are the following features:

1. Filtration of results based on the following criteria:

  * Wallet Balance

  * Game 

  * Keywords

2. A "Viability" index with projected profits

3. Hotkeys for accepting TOS, and refreshing the list

##Installation Instructions

Install Tampermonkey (https://tampermonkey.net/).

Copy and paste the contents of the .js file into a new Tampermonkey script.

## Usage Instructions and Controls

Navigate to the Steam Community Market in your browser (http://steamcommunity.com/market/)

* Press R to filter list
* Press E in buy menu to auto-accept ToS

##Known Bugs

1. ~~There is a bug where after a yellow result (moderate price) appears, a refresh may return the same result but as a green result.~~
  ~~There is still no indication as to how this is occurring, and it is rare enough that i has not yet affected my own buys.~~
  ~~Will look into it soon.~~

2. There is a bug where the page does not load quickly anough and results are not filtered. This occurs 4-7% of the time.

3. There is a bug where the server will not let you buy the item (xmlHttpRequest Error). From what I can tell, it's a Steam issue.
4. There is a bug where there is an xmlHttpRequest Error when requesting info for price comparison. From what I can tell, it seems to be an anomaly, occurring in less than 1% of tests.
