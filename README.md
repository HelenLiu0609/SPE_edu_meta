# SPE_edu_meta
## About 
The current repo contains materials, datasheets and scripts used to generate the results in the article "The Effectiveness of Self: A Meta-analysis of Using Self-Referential Encoding in Education".
## R environment 
R studio Version 1.4.1717

- tidyverse: 1.3.1  #for data pre-processing 
- esc: 0.5.1 #calculate effect size and variance from given data
- irr: 0.84.1 #calculate the proportion of overall agreement of two raters
- metafor: 3.4-0 # perform ramdom effect model of effect size
- meta: 5.2-0 # confirm the results with metafor package,perform sensitivity analysis, test for publication bias and subgroup analysis
## Datasheets description 
- [codebook&summary](https://github.com/HelenLiu0609/SPE_edu_meta/blob/main/datasheets/summary%20%26%20codebook_final.xlsx) #coding sheet of the current study
- [effect_size](https://github.com/HelenLiu0609/SPE_edu_meta/blob/main/datasheets/effect_size.csv) # pre-calculated effect size for each independent sample & targeted moderators 
## Scripts description
- [overall_agreement.Rmd](https://github.com/HelenLiu0609/SPE_edu_meta/tree/main/scripts) #used to calculate the proportion of overall agreement of two raters invloved in the coding procedure
- [EffectSizeCaculating.Rmd](https://github.com/HelenLiu0609/SPE_edu_meta/blob/main/scripts/EffectSizeCaculating.Rmd) #used to calculate effect size for each independent sample
- [formal_analysis.Rmd](https://github.com/HelenLiu0609/SPE_edu_meta/blob/main/scripts/formal_analysis.Rmd) #used to perform ramdom effect model of effect size, sensitivity analysis, test for publication bias and subgroup analysis

# Main results
The analysis was based on data from 20 independent samples, including 1082 students from 13 primary studies identified through a systematic literature search. Results from random effect models show that incorporating self-referential encoding improved learning outcomes (g = 0.40, 95% CI [0.18, 0.62]). 
![Forest plot](https://github.com/HelenLiu0609/SPE_edu_meta/blob/main/figures/forest_overall.jpeg)

Note: The effect sizes (Hedges' g) and confidence intervals are shown by points and lines, respectively. The diamond on the bottom depicts the overall effect size, with the width indicating the corresponding confidence interval.
