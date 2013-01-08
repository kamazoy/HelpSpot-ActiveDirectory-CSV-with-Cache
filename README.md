HelpSpot-ActiveDirectory-CSV-with-Cache
=======================================

Allows HelpSpot to read a text file to search for Live Lookup information instead of making a connection to the domain controllers each time and asking the DCs (this way is much quicker). Plus a script which should be run via cron to refresh the info.