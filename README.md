Lab5- Assignment-Seaborn1

dataset : restaurant

Using this dataset, answer the following questions by creating appropriate visualizations with Seaborn:

Question 1: Distribution of Tips Across Different Days
•	Visualize how tips are distributed across the different days of the week (day). Use box plots or violin plots to show the spread and central tendency of tip values.
•	Is there a significant difference in the tip distribution between different days?

Question 2: Relationship Between Total Bill and Tip
•	Visualize the relationship between the total bill and tip. Use a scatter plot with a linear regression line overlaid.
•	Include the hue parameter to color the points based on the time (Lunch vs. Dinner). Does the relationship between the total bill and tip vary between lunch and dinner?

Question 3: Correlation Between Numeric Variables
•	Calculate the correlation between the numeric variables (total_bill, tip, and size), and visualize this correlation using a heatmap.
•	Annotate the heatmap with the correlation coefficients, and adjust the color palette for better visualization.

Question 4: Impact of Party Size on Tip
•	Investigate how the party size affects the tip amount. Use a catplot (e.g., bar plot or box plot) to compare the average tip given for different party sizes.
•	Include a hue based on whether the customer was a smoker. Does the smoking status influence the tip amount for different party sizes?

Question 5: Pairwise Relationships Between Variables
•	Use pairplots to visualize the relationships between multiple numeric variables: total_bill, tip, and size.
•	Add a hue based on the time of the meal (Lunch vs. Dinner) to see if the relationships change across different meal types.
•	What insights can you gain from the pairwise relationships, especially in relation to meal time?

Question 6: Predicting Tip Amount Based on Total Bill
•	Fit a linear regression model to predict tip based on total_bill using lmplot.
•	Plot the regression line and include a hue for the time (Lunch vs. Dinner).
•	How well does the regression model explain the relationship? Are there noticeable differences between lunch and dinner?

Question 7: Analyzing the Effect of Smoking on Tips
•	Investigate whether smoking status (smoker vs. non-smoker) affects the tip amount. Use a violin plot to show the distribution of tips for smokers and non-smokers.
•	Add the time as a hue to analyze if the effect of smoking on tips differs between lunch and dinner.

Question 8: Exploring Multivariable Relationships Using FacetGrid
•	Use FacetGrid to explore how the relationship between total_bill and tip varies by day and time. Create scatter plots for each combination of day and time.
•	What patterns emerge when comparing different days and times?

