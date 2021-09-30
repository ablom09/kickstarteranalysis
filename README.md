# kickstarteranalysis

Overview:

I utilized existing Kickstarter data to map the success of various performances, plays in particular, based on their launch dates and their funding goals.

Analysis and Challenges: as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.

In order to properly arrange the data that I wanted, i had to take existing data that captured when the Kickstarter projects launched and ended and convert them into a readable format. To do this, both the DATE() and later YEAR() function were used to generate my data in column S,T and U respectively. From this point, data could be filtered through the subcategories I had formed from the various types of Kickstarter projects to create Pivot Tables and graphs where most of my findings were illustrated from. From said pivot table a graph was made that mapped successful, failed, and cancelled plays. Later, a new set of data was created by examining via various Kickstarter Goal ranges. Data was gathered using COUNTIFS() and SUM() functions before a graph was generated to visualize the findings.

Conclusions:

The most success for Kickstarter Plays can be found if it is launched in May. Projects are more likely to succeed than fail year round, even in December when counts of success vs. failed are much closer than other months of the year.

A general negative trendline can be viewed looking at success relative to scope of goal. In other words, the more funding a project is requiring the less likely it is to succeed. More modest goals show high likeliness to succeed, whereas projects that are more expensive are less likely to reach their goals. 

Limitations:

The data, in particular for the subset category "plays" could be too vague. It may be that various genres of plays perform remarkably different to each relative to each genre, for example, a comedy might generally be a more successful Kickstarter project than a drama. If possible, tightening this scope could yield more precise analysis.

Suggestions:

Another graphical possibility I would include might be a box and whiskers plot for its usage in illustrating where, if applicable, our data is skewing.
