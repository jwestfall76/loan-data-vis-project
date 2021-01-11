Dataset: I decided to go with the Prosper Loan Dataset

Overview:

    I loaded the dataset and looked at what variables I wanted to explore.
    Out of the 80 different columns, I narrowed it down to 13 columns.
    I wrangled the dataset to combine credit score columns, remove duplicates,
    and to change values in the IsBorrowerHomeowner column.
    After I wrangled the dataset, I did univariate, bivariate, and multivariate
    analysis on the dataset focusing on variables that affect
    a borrower getting a specific interest rate for their loan.

Main Findings from my Exploratory Analysis:

    My main variable of interest is finding out how different
    borrowers get assigned an interest rate.  I chose to
    look at the distribution of interest rate and the variable
    I suspected would have the largest impact: credit score.

    I did some further exploration to see if I could find any
    other relationships within the data columns I chose.  Most of the
    columns I explored resulted in dead ends that their plots didn't have
    any correlation present.

    Using bivariate analysis I chose to use the relationship between interest
    rate and homeownership.  At first, using the violin plot, I thought the
    comparison was obvious as homeowners should have been assigned a lower
    interest rate compared with a non-homeowner.  However, when adding credit
    score in addition to those two, it showed something different.  It showed
    when a homeowner and a non-homeowner are in the same credit range, the
    homeowner has a slightly higher interest rate than the borrower that
    does not own a home.

    The final element I put in the explanatory analysis was adding Income range
    in comparing credit score and interest rate.

Key Insights:  As suspected, the biggest factor in a borrower getting a specific
    interest rate is their credit score.  I used this relation as a baseline
    to explore a couple of other relationships in the explanatory analysis:
    If the borrower is a homeowner and income range.

Sources for my project:

    I had to use the knowledge forum to get the slide conversion to work
    correctly to omit the code cells.

    I referenced some code from the Visualization lesson to get some
    visualizations set up in the exploratory part to look at their relationships

    Otherwise, I used web searches to get some ideas or to find some parameters
    to add in certain methods to get them to work the way I wanted them to.
