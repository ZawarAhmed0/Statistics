A portfolio of statistical analysis labs. Each lab demonstrates data analysis, visualisation, and statistical inference using R.

## Labs

### Lab 1: Introduction to R and Data Visualisation
**Dataset:** UK Household Income Data (Family Resources Survey)  
**Skills:** Data exploration, `ggplot2` visualisation, wide vs long data formats, scatter plots, histograms with `facet_grid`  
**Key tasks:**
- Compared wide and long data formats (`frs_bracket1_wide` vs `frs_bracket1_long`)
- Produced scatter plots showing income trends over time by ethnicity
- Created faceted histograms of income distributions by ethnic group
- Wrote a headline summary interpreting income inequality patterns

### Lab 2: Exploratory Data Analysis
**Dataset:** CDC Behavioural Risk Factor Surveillance System (20,000 observations)  
**Skills:** Mosaic plots, box plots, data wrangling with `mutate`, grouped summaries  
**Key tasks:**
- Constructed mosaic plot of smoking status by gender using `ggmosaic`
- Created BMI variable and analysed its distribution by exercise status
- Explored the relationship between current weight and desired weight
- Analysed gender differences in weight perception using side-by-side box plots

### Lab 3: Sampling Distributions
**Dataset:** Ames Housing Data (2,930 homes)  
**Skills:** Sampling, simulation, Central Limit Theorem, sampling distributions  
**Key tasks:**
- Compared sample distributions to the population distribution
- Demonstrated that sample means converge to the population mean (Law of Large Numbers)
- Built sampling distributions of the mean with 5,000 replications
- Investigated how sample size affects the centre, spread, and shape of the sampling distribution
- Explored the sampling distribution of the sample variance (chi-squared distribution)

### Lab 6: Inference on Proportions
**Dataset:** Annual Population Survey — Scottish Labour Force Unemployment  
**Skills:** Hypothesis testing for proportions, confidence intervals, success-failure conditions  
**Key tasks:**
- Tested whether unemployment rates differ significantly between ethnic groups in Scotland
- Evaluated whether statistical significance implies causal claims (employer bias)
- Controlled for education level to investigate confounding effects
- Visualised the relationship between population proportion and margin of error

## Skills Demonstrated

- **Statistical Methods:** Hypothesis testing (z, t), confidence intervals, sampling distributions, Central Limit Theorem, proportions inference
- **R Programming:** tidyverse, ggplot2, dplyr, ggmosaic, infer, janitor
- **Data Visualisation:** Histograms, scatter plots, box plots, mosaic plots, faceted plots
- **Statistical Communication:** Interpreting results in context, writing headline summaries
- **Reproducible Research:** R Markdown reports with integrated code and analysis

## Tools & Technologies

- R / RStudio
- R Markdown
- tidyverse (ggplot2, dplyr, tidyr)
- ggmosaic, infer, janitor
- LaTeX (mathematical notation)
