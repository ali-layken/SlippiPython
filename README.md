# SlippiPython
Downloads sets from smash.gg then allows for extraction of whatever statistics. killAnalyze.py has examples.


## How to use:

-run DownloadStats.py and follow the directions

# Ouput:
kill.txt & stats.txt are examples of what the output will look like.

## How to develop:
-make a pickle and open the pickle created by DownloadStats.py

everything that you need to extract new stats like maybe stage win% or somthing will be conatianed in the pickle.



### The pickle is a list with 2 things:

-ALL of the set data as a dict

-a dict with info about every game so u dont have to loop over and grab it before doing whaetever stat
