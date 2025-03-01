# From Paws to People: A Statistical Assessment of the Impact of Demographic Factors on Health Outcomes in Companion Dogs

## Description

Companion dogs share robust genetic and environmental traits with humans, yet breed-specific health risks remain underexplored, and veterinary studies often lack replication. This study identifies the prevalence of common health conditions in mixed-breed and purebred dogs and analyzes their correlation to demographic factors like sex, neuter status, size, and age.

A ‘replication crisis’ plagues many scientific fields—novelty is emphasized over replicability/reproducibility. Thus, using The Dog Aging Project’s open-source data, this study partially replicates “Lifetime prevalence of owner-reported medical conditions in the 25 most common dog breeds in the Dog Aging Project pack” by Forsyth et al. (2023), comparing results with a Jaccard index of 0.7576, indicating high similarity and reinforcing findings.

Then, this project utilizes Python packages to perform original mathematical analyses to further study the importance of demographic factors. A binomial model with logit link was employed to calculate log-odds ratios, with an α=0.05 significance threshold for hypothesis testing and Bonferroni correction to adjust for multiple comparisons. Incorporating domain-specific knowledge, the model was refined to three independent interaction terms for predicting key health outcomes. 

Purebreds showed higher susceptibility to 19 conditions and mixed-breeds to 11. Age is statistically discernible in predicting 13 conditions, size in 6, and neuter status in none. These results inform health professionals and owners of breed/size/age/sex-specific risks, allowing for personalized medicine. 

This study addresses the ‘replication crisis’ in applied statistics and advances understanding of canine health, enabling more preventive ‘Medicine 3.0’ for canines. As companion dogs share genetic traits and environments with humans, studying their health trajectories also holds potential in expanding our knowledge of human aging.

## Requirements

pip install -r requirements.txt

## Authors

Sophie Zeng

## Acknowledgments

My deepest gratitude to Hui Xin for taking me under her wing and inspiring me to pursue this project! 
