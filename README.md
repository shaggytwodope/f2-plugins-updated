Fixes for various tf2 comp plugins, originally made by F2
## Fixes:
#### general fixes
* included newest curl extension in repository because it's annoyingly hard to find * cleaned up in general, converted tabs to spaces, removed xtra whitespace (will likely be restyling in the the 
future for better readability) * updated update to the one in this github * updated to latest sourcemod syntax * updated stocks/incs to most recent versions * compiled on latest sourcemod
#### logstf:
* Fixed logstf cutting off server hostname for no apparent reason * Removed deprecated descriptors for cvars (FCVAR_PLUGIN)
###### todo: replace morecolors.inc with [color-literals.inc](https://github.com/nosoop/stocksoup/blob/master/color_literals.inc) for less of a memory footprint on servers
##### medicstats:
* fixed log spam when picking up healthpacks
#### supstats2:
* fixed log spam when picking up healthpacks
##### more coming soon
## Installation:
* clone repository * drag folders into your `/tf/addons/sourcemod/` directory
## Known bugs:
* i don't know. i have only done light testing, but so far things seem fine
