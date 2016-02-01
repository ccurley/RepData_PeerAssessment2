# RepData_PeerAssessment2
Source material for the the second assignment in the producible research course. 

Note: I started this project late due to fiscal planning priorities, so it's a rush job. There are deliberate problems with the way I completed this exercise, because I cut corners to get the assignment done on time. Proceed at own risk.

Hint: would the averages have been the same if I'd adjusted one partiular miscoded "B" for the correct code "M"? 

However, as an etude for reference, there's an example of the string and computational transformations for reference. 
- Why did I use gsub instead of grep? I find the code for gsub easier to read. Otherwise, no reason.
- Why did I use dplyr to summarize instead of using aggregate? Personal prefrerence -- I like the nomecrature for dplyr when dealing with data frames.
- Why did I keep prop and crop in two difference categories and aggregate health impacts for fatalities and injuries into one variable? No reason. I had a max of three charts in the assignment, so something needed to be combined and health impacts is where I started since I was putting off the exponent transformation due to laziness.
- Why averages instead of cumulative sums? I didn't like the variation between catestrophic events and widespread weather conditions.

I do think that the assignment should have included putting system information, since platform and version could be significant for reporducibility. But, that's just me.

Also, I never got around to dealing with tables, which I wanted to learn better. So, that's something I'll have to sort out later.