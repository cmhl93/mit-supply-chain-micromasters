# Unit 2: Discrete Distributions

##  Characterizing Uncertainty

  * Several ways to characterize a distribution:
    * Central Tendency – what is the “most likely” value?
    * Spread – how much do the observations “differ”?

  * Central Tendency Metrics
    * Mode – value that appears most frequently
    * Median – value in the “middle” of a distribution
      * value separating the lower from the higher half
    * Mean – sum of values divided by the total number of observations (average)
      * sum of values multiplied by their probability (expected value)
      * Expected Value - average probability

  * Spread Metrics
    * Range – maximum value minus minimum value
    * Inner Quartiles – the 75th percentile value minus the 25th percentile value
    * Variance – expectation of the squared deviation around the mean 
      * Also called the Second Moment around the mean

  *  Standard Deviation – Square root of the variance
    * In same units as the mean! 
  * Coefficient of Variation – Ratio of standard deviation to the mean
    * Standard measure of variability

## Discrete Probability Distributions

  *  Probability Distributions
    *  Where do they come from?
      * Empirical – based on actual data
      * Theoretical – based on a mathematical form
      
  * Discrete Theoretical Distributions
    * Discrete Uniform Distribution
      * N possible values
      * Each value has equal probability, i.e., 1/N
      * Ex: Rolling a die
    * Poisson Distribution
      * Probability of seeing x events within a certain time period
      * Example: Random arrivals to a customer service desk
  * Discrete Uniform Distribution
    * Notation: U(a, b)
      * a = Minimum
      * b = Maximum
      * n = # of values = b – a + 1
    * Metrics
      * Mean = (a + b) / 2
      * Median = (a + b) / 2
      * Mode N/A
      * Variance = ((b-a+1)2 – 1)/12
