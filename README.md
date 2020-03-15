# What factors have an impact on infant mortality?
 

## Project aims
To do a statistical analysis verifying findings from the literature using a small dataset. 
 
This project aims to understand what factors influence the infant mortality rate (IMR) (nb. infants typically refer to children under 1).  I am interested in investigating which macroeconomic variables are related to infant mortality. This is a useful start to understand where countries should prioritise their efforts to reduce infant deaths. I use a time series dataset from country X (anonymous source) and I look at the following variables: gross domestic product per capita, public spending on health and education. All my data is in real terms and in the local currency.
 
I start with the following hypotheses:
1.	Wealthier countries are expected to have lower IMR
2.	Public spending on health and education is expected to reduce IMR
There is a literature supporting these hypotheses:
•	Higher income per capita is related to higher household spending on nutritious foods and health services [Baird et al., 2011].
•	Health expenditure targeting the causes of infant death is effective in reducing infant mortality [Baird et al., 2011].
•	Educational spending increases mothers’ awareness of hygiene and nutritional practise [Meegama, 1980; Gortmaker; 1997].


## Methods
 
To test my hypotheses in the data, I use simple correlation analysis and I run a multiple linear regression. I estimate the relationship between IMR (Y) and the explanatory variables (X). I make a simple prediction using the regression coefficients and I test the statistical significance of my findings. I also re-estimate my regression equation by dropping/adding some of the explanatory variables. I do this to check whether there is omitted variable bias. My best regression model explains 93.6% of the variation in infant mortality.
 
## Findings
 
The hypotheses are verified: GDP per capita and public spending on health and education are negatively related with the IMR. However, this analysis does not explain the dynamics between the IMR and the explanatory variables (i.e. there is no causal link).

## Limitations

The sample size is very small (n = 31), which might bias the regression coefficients and their significance. The origin and the country-context of my data is anonymous, which largely restricts the scope for reproducibility and external validity. The length of the time series is also limited. There may be more important factors that affect infant mortality which are not included (e.g. geography, gender of the child).
