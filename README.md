# Bitburner-scripts

Here are some of my Bitburner (https://store.steampowered.com/app/1812820/Bitburner/) game scripts that I use. Feel free to share or fork as you please.


hacknet-upgrades.js


-------------

**hacknet-upgrades.js**

Credit to [Jrpl](https://github.com/Jrpl/Bitburner-Scripts) for this script.

Purchases the number of requested hacknet nodes and upgrades based on a percentage of your current money.
The script will calculate whether or not buying a server or purchasing an upgrade has a better return on investment.
If purchasing an upgrade is better, it will then determine which type of upgrade is best for each server and purchase upgrades accordingly.
Takes two arguments:

pct: The percentage of your money you want to use as a threshold for buying nodes and upgrades. The percentage is converted to a decimal for the calculations. There are currently no checks in place to see if you are outside the bounds of what is feasible so passing in zero, a negative number, or a number greater than 100, will result in the script not working as intended.
maxNodes: The maximum number of nodes you want to purchase and upgrade.
