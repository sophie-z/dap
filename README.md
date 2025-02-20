# From Paws to People: A Statistical Assessment of the Impact of Demographic Factors on Health Outcomes in Companion Dogs

## Description

This study identifies the prevalence of common health conditions in mixed breed and purebred dogs and analyzes their correlation to demographic and health factors like sex, neuter status, size, and age.

A ‘replication crisis’ affects many scientific fields—novelty is emphasized over reproducibility. Thus, this study leverages the open-source Dog Aging Project and partially replicates a cross-sectional study: “Lifetime prevalence of owner-reported medical conditions in the 25 most common dog breeds in the Dog Aging Project pack” (Forsyth et al. 2023).

Then, this project utilizes Python packages to perform original mathematical analyses of numeric data to further study the relationship between the most common health conditions and demographic factors. A binomial model with logit link was employed to calculate the log-odds ratios of common medical conditions, and a significance threshold of α = 0.05 was applied for hypothesis testing with Bonferroni correction to adjust for multiple comparisons. Incorporating domain-specific knowledge, the model was refined to include three one-way interactions for predicting key health outcomes. 

Results show purebreds are more susceptible to 19 of 30 conditions, while mixed breeds are more prone to 11. Age is statistically significant in predicting 13 conditions, size in 6, and neuter status in none. These results inform health professionals and owners of breed/size/age/sex-specific risks, allowing for personalized medicine. Some concerns require study design changes and further data collection.

This research addresses the ‘replication crisis’ in applied statistics and advances understanding of dog health, enabling more preventive ‘Medicine 3.0’ for our furry friends. Because companion dogs share genetic traits and environments with humans, studying their health trajectories also holds future potential in expanding our knowledge of human aging.

## Requirements

pip install -r requirements.txt

## Authors

Sophie Zeng

## Acknowledgments

My deepest gratitude to Hui Xin for taking me under her wing and inspiring me to pursue this project! 
