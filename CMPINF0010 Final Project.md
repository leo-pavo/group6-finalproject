# CMPINF0010 Final Project

Group Name:  Ok Boomers



How do we define the best neighborhood?

Two of us aren't actually natives of Pittsburgh, so there's something more important to us than just the quality of a neighborhood in terms of something like crime rate or education. See, every now and then we have to travel around off campus, or our parents come to visit us from back home. Sometimes, driving can be a major pain, especially if you constantly have to deal with traffic lights, speed bumps and... dare I say it... BOOMERS. Our definition of the best neighborhood is how easily you can travel through it. If you don't have to stop or slow down often, then it's a good neighborhood. But if you're constantly stopping for lights, bumps, or boomers, then it's not a fun place to travel through.

What are the metrics?

We have three datasets we're using: Pittsburgh Traffic Signals, Pittsburgh Speed Humps, and the SNAP census/population data. Each metric will be given a weighted point value, and each neighborhood will accrue point as each metric is added up. Each speed bump is weighted to 20 points, a traffic light is 4 points, and an elderly person is worth 0.5 points. This works like a game of golf, the neighborhood with the fewest points wins the best neighborhood designation.



First off: the speed bumps.



There was surprisingly little data on these in the dataset that we found, so because of that the weight on them has to be a lot higher than any of the other (also due to personal preference). We simply sorted the data by neighborhood, and then counted up the number of times a bumps was designated in a neighborhood. Here's the potential reasoning for the small number of speedbumps: either the person who made the list hasn't compiled data from every neighborhood yet, this data doesn't include bumps in places like parking lots and garages (since those are privately maintained), or this city really doesn't have that many bumps, which is... strange? Whatever the case, a higher weight was assigned to these because of the lack of data on them.



Next: street signs.



This definitely has more data on it than the speed bumps. We mainly focused on the two major types of signs though: wayfaring and warning signs. Wayfaring signs exist to help guide drivers, and aren't actually an inhibitor to driving (unless you count the time it takes to look at them). Warning signs are the real focus here, as they are the ones that are actually meant to slow you down. 



Finally: the elderly.



This data was a two step process. First, we took the percentage of the population that were considered elderly (60+) in a neighborhood. Then, we multiplied that by the actual population of the neighborhood to get an approximate number of actual elderly people. 

