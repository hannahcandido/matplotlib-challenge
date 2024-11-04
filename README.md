# matplotlib-challenge
Methodology
In this analysis, I used Pandas for data manipulation, SciPy for statistical analysis, and Matplotlib for data visualization.
First, I loaded the datasets into DataFrames using Pandas' pd.read_csv() function, which allowed me to perform various data manipulations, such as merging datasets and cleaning or removing duplicates.
I also conducted several statistical analyses using the SciPy library, including calculating the mean, median, mode, variance, standard deviation, and standard error of the mean.
Finally, I used Matplotlib to visualize the findings by creating multiple charts to better understand the data distribution and relationship

Data Analysis
Intent is to analyze a set of spreadsheets containing information that tests the efficacy of certain drugs at reducing tumor sizes in mice.
Bar Charts
This shows the drug regimen in relation to the count. Capomulin has the highest count followed closely by Ramicane. Propriva has the least count.
Pie Charts
Shows the gender spread of the dataset. The dataset shows a nearly even distribution of gender, with male and female counts being closely matched.
Statistical Analysis
The mean and median are closely aligned for each individual drug regimen. However, the variance for Ketapril, Naftisol, Placebo, and Stelasyn is relatively high, indicating significant data dispersion.
Box plot shows 
Both the Capomulin and Ramicane drug regimens exhibit a smaller interquartile range compared to Infubinol and Ceftamin, with Infubinol showing the presence of an outlier. Additionally, Ramicane appears to be more evenly distributed than Capomulin, as indicated by the median line being more centrally located within its box plot.
Scatter Plot
Capomulin Drug Regimen- Case Study
The scatter plot of mouse weight versus average tumor volume indicates a positive correlation: as mouse weight increases, the average tumor volume also tends to increase. This relationship is further supported by the correlation coefficient and the linear regression model.
