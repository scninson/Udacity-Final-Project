# Udacity-Final-Project
# Loan Data From Prosper
## by Isaac Ninson


## Dataset

>  The dataset present loan information for borrowers on a loan platform. Dataset consist of 113,937 cases with 81 columns. I decided to narrow the dataset to my main features of interest as well as other selected features to enable me investigate my main interest. Upon getting my new dataset, I perform wrangling and data cleaning since I noticed data quality and structure issues upon performing visual and programmatic checks on the new dataset. Before data cleaning, the new dataset had 113,937 rows and 14 columns but after data cleaning, the cleaned dataset had 61482 rows and 14 columns. The rows drastically reduced due to the removal of null values in one of my main features of interest which was Prosper Rating. According to the Dataset's variable description, Prosper Rating was applicable for loans originated after July 2009.Therefore loan originating before the said date didn't have ratings. Since Prosper Rating is one of the main features of interest for me, It was justifiable for me to remove such cases since it wouldn't present a fair findings during the data exploration.


## Summary of Findings

> From the Exploration, I found out that Prosper Rating had a positive relation with Loan Amount but a negative relation with Borrower APR. This mean that Borrowers who had high ratings secured high Loan Amount but low Borrower APR. It was also discovered that Borrowers with high ratings were more of Homeowners than Non-homeowners. This further strengthens the reason why they are able to secure high loans with low APR.
>Loan Term was discovered to have a positive relation with Loan Amount. Therefore, high loan amount are link with long term loans. Although Loan Amount has a strong relation with Monthly Loan Payment, as Loan Term increases, the monthly loan payment decreases.
> Borrowers secured loans largely for debt consolidation purpose. Student Use was the only listing category that Borrowers did only one type of loan term i.e medium term. 


## Key Insights for Presentation

> I would like to focus on Prosper Ratings influences on some of the other variable since It has a strong positive relation on Loan Amount but a negative relation on Borrower APR. To do this a few multivariate plots will be done for Ratings and some few other variables. 
