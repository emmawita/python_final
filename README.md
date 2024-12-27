# MUSA 550 Final Project


#### Study Abstract 
Machine learning (ML) is an invaluable tool for crime analysis and prediction, providing law enforcement with data-driven insights to enhance crime prevention. This project aims to forecast assault incidents across Chicago neighborhoods using Poisson regression, which is ideal for modeling count data like crime occurrences.

We utilize a variety of geospatial and socioeconomic factors to uncover spatial trends and key assault risk predictors. By integrating geospatial risk models with socioeconomic indicators and local crime reports, our model identifies areas with high crime probabilities. The Poisson regression model, fitted with 1,098 grid cells, shows a log-likelihood of -9330.8, signifying a good fit. Deviance and Pearson chi-square values (14,511 and 19,500 respectively) highlight the model’s explanatory power, with a pseudo R-squared value of 0.9994 indicating robust data variability capture.

All predictors are statistically significant (p < 0.001). Notably, non-functional streetlights (coefficient: 0.1229) and ShotSpotter-detected incidents (coefficient: 0.0333) have strong positive associations with assault counts. Liquor retail stores (coefficient: 0.0015) and graffiti incidents (coefficient: 0.0010) are also significant contributors.

These findings underscore the importance of urban infrastructure and crime detection technology in understanding and preventing assaults. Our predictive framework facilitates efficient resource allocation and targeted interventions in high-risk areas, aiding law enforcement in proactively mitigating criminal incidents. Through data-driven strategies, we aim to enhance community safety and improve crime prevention efficacy.


Website: https://emmawita.github.io/python_final/
