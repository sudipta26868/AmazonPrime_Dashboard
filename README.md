# AmazonPrime Dashboard

Here I have created a dashboard on amazon prime . The data I got from Kaggle . 

## Upload the data And cleaning
At first I uploaded the data in Power BI . Then transform it on power Query and perform some basic data cleaning operation . After that save the file and it will automatically did some changes . ( note : anyone can do data cleaning operation on excel also and then upload it on power bi ) 

## Dasboard creation 
- **Total shows by country** : Select filled map from visuals then drag country column inside location and shows id inside tooltips (aggregation should be count(distinct) for show_id) . After that perform some formatting to give it a better look.
- **Movies & Tv shows** : select donut from visuals then drag type on legend and show_id on values ( Aggregation: count(distinct) for it) )
