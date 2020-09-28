# Yandex.Practicum
Training Projects

## Project 5 - Exploring the Patterns that Determine the Success of a Video Game *Integrated Project 1*


### Description
Being provided data by an online store selling video games I conducted a market analysis and found the present most popular (or best selling) platforms and genres by region to define what the best groups of products, i.e. video games to advertise are.

### Summary
The following findings were established by the video game market analysis of more than 16 thousand titles.
- A console exists 7-10 years prior to getting taken off the market, but the growth reaches its peak within the first 5 years. The selected actual period of the analysis is 2012-2016 (the sales records for 2016 are not of the whole year).
- Top 5 platforms of the actual period by video game sales: PS4, PS3, X360, 3DS, XOne. 
- There is no linear correlation between sales and user scores but there is a positive one of 42% between sales and critic scores.
- Most of the games come out in the Action genre, but on average they pay less than Shooters, while there are almost three times less Shooters than Action games.
- Best-selling genres: Action, RPG, Sports and Shooters. Worst selling genres: Adventure, Strategy, Puzzle.
- The ESRB rating affects sales in certain regions, it most likely depends on the number of consumers in different age groups and their preferences.
### Hypothesis Testing:
- Mean user scores on XBox One and PC are the same.
- Mean user scores of action and sports genres are different.

#### 3. Exploratory Data Analysis
- Plot: Release numbers throughout the years (Since 1980 to 2016)
- Plot: Revenue Among Top 10 Platforms by Video Game Sales Throughout the Years
- Plot: Top 10 Platforms by Total Sales
- Plot: Video Game Global Sales by Platform
- Plot: Correlation between Sales and User/Critic Scores
- Plot: Game Distribution by Genre and Sales
- Summary
#### 4. Creating User Profile for Each Region
- Differences in Sales Ratio of Top 5 Platforms
- Plot: Top 5 Most Popular Platforms by Region / World Sales Ratio
- Plot: Top 5 Most Popular Genres by Region / World Sales Ratio
#### 5. Statistical Hypothesis Testing
- Mean user scores on XBox One and PC are the same
- Mean user scores of action and sports genres are different


### Applied Tools and Concepts
Preprocessing: pivot tables \
Visualization: pie chart, bar chart, scatter plot, box plot \
Hypothesis Testing: Welch's t-test 

Libraries: 
- pandas
- numpy 
- matplotlib
- scipy
