# Spreadsheet basics

* SUM(cell range) – returns the sum of the specified cells
* AVERAGE(cell range) - returns the average of the specified cells
* MEDIAN(cell range) - returns the median value of the specified cells
* STDEV(cell range) - returns the standard deviation of the specified cells
* MIN(cell range) - returns the minimum value of the specified cells
* MAX(cell range) - returns the maximum value of the specified cells
* Many functions require two or more input parameters. 
  *	For example, the function QUARTILE(cell range, value) returns the 0th, 25th, 50th, 75th, or 100th percentile value in a range of cells. 
  *	It requires two input values: the cell range and a value specifying whether you want the 0th percentile (0), 25th percentile (1), 50th percentile (2), 75th percentile (3), or 100th percentile (4). 
  * This function is handy to understand the shape of a distribution. For example, =QUARTILE(C2:C11,2) will return the 50th percentile value of the Quantities - note that this is the same thing as the Median value.
* Interquartile is the 75th percentile value minus the 25th percentile value
* Coefficient of variation
  *	The CV is equal to the standard deviation divided by the mean
* The function SUMPRODUCT(cell range, cell range) does what it is called - that is, summing up the product of two arrays.  It has two input values, each a range of numbers of the same number of elements.
* The IF function provides additional logic functionality based on certain conditions being met.  The format is =IF(test, then_value, otherwise_value)
