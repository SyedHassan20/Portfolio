## 1. Correlation and Regression Analyses for Birth Weights in North Carolina

This project presents an in-depth statistical analysis of birth data from North Carolina, focusing on the relationship between gestation periods and infant birth weights. The key technical components include:

- **Dataset Analysis**: The study utilizes data from 150 births in North Carolina, examining the relationship between the duration of gestation (in weeks) and the birth weight of infants (in pounds).
- **Correlation Analysis**: Pearson's correlation coefficient is calculated to assess the strength and direction of the linear relationship between gestation period and birth weight. A correlation coefficient of approximately 0.68 indicates a moderately strong positive relationship.
- **Linear Regression Modeling**: A simple linear regression model is developed to predict infant birth weight based on gestation weeks. The model includes the calculation of the slope β1 and intercept β0, with the regression equation derived as:
Weight (lbs) = 0.37 × Weeks − 7.3.
- **Statistical Significance**: The significance of the regression model is tested using a t-test, yielding a p-value significantly below the 0.05 threshold, leading to the rejection of the null hypothesis. This suggests a statistically significant linear relationship between the gestation period and birth weight.
- **Model Fit**: The model's goodness-of-fit is evaluated using R-squared, which in this case is 0.467, indicating that approximately 46.7% of the variance in birth weight can be explained by the gestation period.

## 2. Medial Temporal Lobe Inferential Statistics Report

This report explores the relationship between anxiety levels and physical activity using data related to the medial temporal lobe (MTL). The analysis is grounded in inferential statistics, and key technical elements include:

- **Dataset Description**: The dataset includes observations from 33 individuals, focusing on two key variables: Hamilton Rating Scale for Anxiety (Ham_a) and self-reported sitting time as a proxy for physical inactivity.
- **Hypothesis Testing**: The study performs a difference of means test to compare sitting durations between individuals with high and low anxiety levels. The null hypothesis posits no difference in sitting duration between the two groups.
- **Confidence Intervals**: Confidence intervals are constructed for both the overall sample and the difference in means, providing a range of plausible values for the population parameters.
- **Effect Size**: Cohen’s d is calculated to assess the practical significance of the observed differences. Despite failing to reject the null hypothesis, the effect size calculation reveals a small practical difference in sitting durations between the two anxiety groups.
- **Assumptions and Conditions**: The analysis critically examines the assumptions underlying the t-test, including sample size adequacy and the applicability of the Central Limit Theorem (CLT) given the sample characteristics.

## 3. Ambulance Dispatch Analysis and Matching Optimization

This notebook focuses on analyzing ambulance dispatch data and optimizing the matching of ambulances to emergency cases. The technical highlights include:

- **Data Collection:** Gathered real-time data on ambulance dispatches at fifteen-minute intervals between 3 pm and 6 pm.
- **Variable Analysis:** Examined the number of ambulances dispatched as a discrete variable to understand emergency response frequency.
- **Simulation:** Developed and ran simulations to model and optimize ambulance response times and resource allocation.
