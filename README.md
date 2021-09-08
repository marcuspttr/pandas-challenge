# pandas-challenge
Working with Pandas strategize for the Heroes of Pymoli game and help the City schools with their finances.

Started up work at school (I'm a teacher) this past week. With the craziness of the first week I haven't been able to work on or update as much.
- Worked on both the PyCitySchools and HeroesOfPymoli problem sets.
- Got a rough work through on both; however, couldn't figure out how some of the Averages were being calculated for the HeroesOfPymoli sample.
- Had an initial commit last week and updated the README file, but these changes were overwritten? Possibly an error as I was modifying and pushing changes from multiple computers (home and work laptop)?
- Cleaned up the formatting on the PyCitySchools, added basic #notes for clarity.

Current outstanding issues:
- Some of the table outputs are not translating from Jupyter to the online preview.
- HeroesOfPymoli has a few incorrect calculations for Total Avg Purchase Per Person. Couldn't figure out what they were asking for here.
- Had another issue on HeroesOfPymoli when sorting for Most Profitable Item. After doing the sort, the column was correctly sorting the values. It was listing a middle value and then resorting mid-way. Ran out of time to figure out what was happening.

Trends analysis for PyCitySchools:
1) When looking at the % passing rates throughout the data it can be seen that mathematics provides a strong predictor for the overall passing rate among the same group. Explaining further if you saw a high % math score then generally overall would have a similar higher % value, same held true for lower values. Meanwhile looking at passing rates for reading they seemed more independent - some skills would have higher or lower % reading rates, but would not neccessarily be reflected in the overall rates. What does it mean? Mathematics is almost a gatekeeper for overall passing rate of schools so if they want to improve overall, they should start with their math tests.

2) Another trend is that all the schools fit within a tight range for their budgets within the district and it was not a relevant predictor for how they would do. Rather the school type seems to have a large impact on performance. When sorting by top 5 the best schools were all charter and the bottom 5 of performance were all district. School size also saw relevant changes in performance, with size having an inverse effect (the smaller the better.)
