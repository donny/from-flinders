# from-flinders

A Node.js CLI app to show the next train departures from Flinders Street Railway Station (Melbourne).

Install:

    $ npm install -g from-flinders

Usage:

    $ from-flinders --help

    Usage: node from-flinders [options]

    Options:
       -n NUM, --next NUM     Show the next NUM departures  [5]
       -l NAME, --line NAME   Show the next departures from line NAME  [Werribee]
       -j, --json             Display the data as JSON  [false]

    $ from-flinders
    🚂  From Flinders at 22/10/2014, 11:31:41
    Werribee
      11:39:00 Footscray
      11:41:00 Werribee
      11:51:00 Newport
      11:59:00 Footscray
      12:01:00 Werribee
