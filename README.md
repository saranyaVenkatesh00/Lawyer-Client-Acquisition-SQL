About the Project
_______________________________________________________________________________________________________________________
Lawyers rely heavily on online visibility to attract new clients. However, not all lawyers have the same digital presence. This project explores how factors like firm size, practice area, and online presence influence the number of clients lawyers receive.
Using SQL, I analyzed a dataset of lawyers to understand where lawyers are easy to find online and where potential clients may struggle to locate legal services.
_____________________________________________________________________________________________________________________________
Dataset
_____________________________________________________________________________________________________________________________
The dataset used for this project contains information about lawyers, including:

State
Firm size (Solo, Small, Mid, Large, BigLaw)
Practice area
Years of experience
Online presence indicators (website and reviews)
Average client rating
Estimated number of clients per year

The dataset was sourced from a publicly available legal dataset on Kaggle.
____________________________________________________________________________________________________________________________
Questions I Wanted to Answer
_____________________________________________________________________________________________________________________________
While exploring the dataset, I focused on a few key questions:

Are large law firms more visible online than solo lawyers?
Which legal practice areas have the weakest online presence?
Do solo lawyers receive better client ratings than firm lawyers?
Are there practice areas where lawyers may be losing clients due to poor online visibility?
_____________________________________________________________________________________________________________________________
What the Analysis Shows
_____________________________________________________________________________________________________________________________
1. Online Visibility by Firm Size

Large firms tend to have stronger online visibility. They are more likely to have websites and client reviews, which can help attract more potential clients.

Solo lawyers, while numerous, often have lower online presence, which may limit their client reach.
             
2. Practice Areas with Low Online Presence

Some practice areas show a higher percentage of lawyers without websites or reviews. These lawyers may be harder for potential clients to discover online.

This suggests that certain legal fields may have untapped opportunities for lawyers who invest in online visibility.
           
3. Solo vs Firm Lawyer Ratings

The analysis compares average client ratings between solo lawyers and firm lawyers across different practice areas.

In some areas, solo lawyers receive similar or even slightly higher ratings than lawyers working in larger firms, suggesting that client satisfaction is not necessarily tied to firm size.
              
4. Client Acquisition Gap

The final analysis identifies practice areas where:

client demand appears high , but lawyer online presence is low
These areas represent potential client acquisition gaps, where lawyers could attract more clients simply by improving their online visibility.
_____________________________________________________________________________________________________________________________
SQL Techniques Used:
_____________________________________________________________________________________________________________________________
The analysis uses several common SQL techniques including:

Aggregate functions (COUNT, AVG, SUM)
Conditional logic using CASE WHEN
Data grouping using GROUP BY
Filtering aggregated data with HAVING
Calculating percentages and averages
