# smalladi-assignmnet-7
## New Additions to the Webpage

This assignment extends the previous work by adding functionalities for **hypothesis testing** and **confidence intervals**. Here’s a breakdown of the new features:

### Data Generation Inputs
In addition to previous inputs, users can now specify:
- **Intercept (β₀)** and **Slope (β₁)** of the regression line.

These values are used in data generation, following the formula:

$$
Y = \beta_0 + \beta_1 \cdot X + \mu + \text{error}
$$

### Hypothesis Testing Section
Users can perform hypothesis tests on the slope or intercept of the regression line after data generation. Options include:
- **Parameter to Test**: Choose either Slope or Intercept.
- **Type of Test**: Choose between Greater than (`>`), Less than (`<`), or Not equal to (`≠`).

The application calculates a **p-value** for the hypothesis test, displaying whether the observed slope or intercept is statistically significant based on the user’s input.

### Confidence Interval Section
Users can calculate confidence intervals for the slope or intercept after data generation. Options include:
- **Parameter for Confidence Interval**: Choose either Slope or Intercept.
- **Confidence Level**: Select from 90%, 95%, or 99%.

The application calculates the confidence interval using the simulated slopes and intercepts, providing insight into the range within which the true parameter is likely to fall with the selected confidence level.
