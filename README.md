#BU username: mwayne@bu.edu

For this HW assignment, I decided to analyze the tag submission time of day of the top 100 tags. So for any tag, there are 24 possible submission hours and I summed up all the submissions. I used cosine similarity to analyze the similarities between two tag time series. I wanted to see what tags were used at the same times and also not used at the same times. I believe that it is best to use cosine similarity to check the orientation of the vectors because some tags were used much less than others, but they still were popular at certain times of day scaled to how popular they are in general. 

I used euclidian distance to analyze the data because I want to see if there are any tags that are used at the same rate and at the same time as eachother. This did make the distance between a very popular tag and a less popular tag greater than cosine similarity. The two metrics are very different from eachother and that is alright because I have two different goals of analyzing similarity.
