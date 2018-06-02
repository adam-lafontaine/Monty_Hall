# Monty_Hall

This was an exercise for me to show that the odds of success when changing your choice in the Monty Hall problem are in fact 1/2 instead of 2/3 as believed.  The reason being is that you have a choice of two doors and only one can have the prize.

I've found that the odds are in fact 2/3 in favor of switching because your first choice has only a 1/3 chance of being correct.  And since only a door without the prize can be opened afterwards, the odds of the remaining closed door having the prize is higher.  In fact the odds are (n-1)/n in favor of switching (n = # of doors).

This html file has one script tag containing all of the code.  You only need to download it and run it in a browser.  You will need an Internet connection to access the Bootstrap CDN.

It has a table demostrating the (pseudo) randomness of Javascript's Math.random() function.  The other section is for running the simulation choosing the number of doors and iterations to run.