# Descriptive Statistics
Descriptive statistics refers to a set of methods used to summarize and describe the main features of a dataset, such as its central tendency, variability, and distribution. These methods provide an overview of the data and help identify patterns and relationships.

## Measures of central tendency
 - Mean: The mean is the average or the most common value in a collection of numbers. In statistics, it is a measure of central tendency of a probability 
   distribution along median and mode. It is also referred to as an expected value. It is a statistical concept that carries a major significance in finance.
 - Median : In statistics, the median is the middle value of a set of numbers when they are arranged in order. It's a measure of central tendency, along with the 
   mean and mode. 
 - Mode : The mode is the value that appears the most frequentyly in your data set. The mode is the higher bar in a barcbhart
   5, 23, 6, 9, 5, 4, 9, 5
   Mode: 5
 - Percentile : A number denoting the position of a data point within a numeric dataset by indicating the percentage of the dataset with a lesser value. For 
   example, a data point that falls at the 80th percentile has a value greater than 80 percent of the data points within the dataset.
 - Quartiles (Q1, Q2, Q3) : In statistics, quartiles are values that divide a set of data into four equal parts. They are a type of quantile and percentile. 
  First quartile (Q1): Also known as the lower quartile, this is the 25th percentile.
  Second quartile (Q2): Also known as the median, this is the 50th percentile.
  Third quartile (Q3): Also known as the upper quartile, this is the 75th percentile.
 - Interquartile range (IQR = Q3 - Q1)
 - Min
 - Max

## Finding outliers using Quartiles
 - Lower Bound (Q1-1.5*IQR)
 - Upper Bound (Q3+1.5*IQR)
 - Outliers: values lower than LB or higher than UB

## Measures of dispersion
 - range : The difference between the maximum and minimum values in a dataset.
Formula:
Range = Maximum Value − Minimum Value
Use Case: Simple and quick measure of spread, but sensitive to outliers.
Example: For the dataset 
2 , 5 , 7, 10 , 12
2,5,7,10,12, the range is  12 − 2 = 10

 - variance: The average of the squared differences from the mean. It measures how far each data point is from the mean.
   
   ![Screenshot 2025-0-03 195159](https://github.com/user-attachments/assets/28e5f3bf-4215-4524-b176-de182dcd5914)


 - standard deviation : The square root of the variance. It measures the average distance of data points from the mean in the same units as the data.

 - ![Screenshot 2025-03-03 195849](https://github.com/user-attachments/assets/9b6979e9-f891-44a2-89cf-cd594a33d52d)

 - z-score (used for standardization):  A measure of how many standard deviations a data point is from the mean. It is used to standardize data for comparison.

   ![Screenshot 2025-03-03 195838](https://github.com/user-attachments/assets/537707f9-24ae-4914-9c41-286be90b1294)

 - Confidence Interval (CI) :  A range of values that is likely to contain the true population parameter (e.g., mean) with a certain level of confidence (e.g., 95%).

![Screenshot 2025-03-03 195823](https://github.com/user-attachments/assets/8178326e-76f5-4060-ad7a-8d08ed376240)

## Correlation coefficient (-1 to 1)
A "correlation coefficient" is a statistical measure that indicates the strength and direction of a relationship between two variables, and it always falls within the range of -1 to 1;
 - Pearson correlation coefficient : The "Pearson correlation coefficient" specifically measures the strength of a linear relationship between two variables
 - Sphearman's rank correlation : While "Spearman's rank correlation" measures the strength of a monotonic relationship, both also falling within the -1 to 1 range.

   
## Scatter plot (Bivariate analysis)
 - Visually inspecting correlation bw two varialbes

## Box plot
 - Shows median(Q2), Q1, Q3, Lower bound, upper bound, outliers

## Histograms
 - Frequency/relative frequency

## Probability density function
## Cumulative density function
 - Advantage compared to PDF
