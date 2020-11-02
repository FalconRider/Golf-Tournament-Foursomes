
A Leap Experiment. GOLF TOURNAMENT FOURSOMES 

A Satellite Constellation Model Derivation.  
It's time again for the annual golf tournament at a 12 person start up.

You want evenly skilled teams so that everyone has a chance at the team prizes.

After all it's supposed to be a company wide  team building day. 
So you make inquiries about golf skills and ask
"What percentage of the time do you make par?"  No one lies. 

Each player gets a code number 0 to 11 (12 players) and you make a new json in the ame style. 

You set the thingie in the json to 3 to get 3 teams and add the data.

Call it golfers.json

And I want to run it on the hss so in the Leap IDE teminal you type - 

python satellite golfers json hss

Run a number of times to get possible foursomes that are even skilled. 

Note that there's a minimum skill threshold in the formula left at .4 but  could be changed in the runner program.
I left labels as in the original "satellite" version here.

I wrote a py generator for the json pairs and it's included. 
This way you could try 1,200 golfers although the documentations says the 39 pairs example
would be a noticeable slowdown. 

This is an experiment. Notes and Obsevations below:

Problem: pairs generator extra last comma.
Deleted manually.
Typos satellite.py and golfer.json fixed and it ran.
Pairs generator needs "s I used 's .Adjusted manually to fix.

Possible problem - got exact same answer 4 tines. will look at.

Original small.json inclused just so could see I tried with my pairs.
