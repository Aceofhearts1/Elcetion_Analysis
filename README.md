# Election_Analysis
## Election Overview
Our purpose in this election was to determine the winner and summary of the election. The twist was, we received a large amount of data. The data came in a .csv file. After having opened it, you could see that the data was tremendously long. That could be intimidating but luckily we have just the code to deal with this. So I set out to find the winner of the election. As well as some other important statistical information such as the percentage of votes and largest county turnouts.
## Election_Audit Results
- There were 369,711 total votes cast.
Total Votes
### County Votes:
- Jefferson: 10.5% (38,855)
- Denver: 82.8% (306,055)
- Arapahoe: 6.7% (24,801)
  - This tells you that Denver County contributed the most to the results of the election. So if you wanted an idea on where to start your campaign, the data tells you to start with Denver County.
Candidate Results
- Charles Casper Stockham: 23.0% (85,213)
- Diana DeGette: 73.8% (272,892)
- Raymon Anthony Doane: 3.1% (11,606)
### Winner Breakdown
- Winner: Diana DeGette
- Winning Vote Count: 272,892
- Winning Percentage: 73.8%
## Election-Audit Summary
So as you can see, our script was able to take a lot of trouble off of the hands of regular people. Imagine if someone had to go through all of that data themselves. Our script makes this an easy process. The best part is, the variables and open lists and dictionaries we used, allows us to use this script for more elections. As long as the format of the .csv file doesn't change, we can handle more elections. With modifications we could potentially use this program even with different .csv file formats. We could write our loops and condtionals to check the headers and find if it is the row we're are looking for instead of assuming the county will be in column 2 or the candidates will be in column 3. To speed up the process, we could eventually use modules such as pandas but lets not get ahead of ourselves. Also, it would be more manageable and easier on the eyes if we changed our script to use a dictionary of lists instead of a list of dictionaries.
