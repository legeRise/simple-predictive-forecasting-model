This is a simple Notebook to get an idea of how actually forecasting works 

the dataset named 'testpf.csv' contains just two columns  
1. Date
2. Sales

and in this notebook I have just converted Date to datetime object(pandas) and based on the day_of_year 
i am predicting sales for upcoming dates
so like if i have dates and sales from  1 jan 2022  -  31 dec 2022   the forecasting will be done for upcoming days(weeks,months or so)

the relationship between day_of_year  and sales is pretty straightforward in this dataset   the bigger day the more the sales
so for example sales for  date: 4 jan 2001 ( day_of_year = 4 ) were  40  then the sales on  date: 1 feb 2001 (day_of_year=32) will be 320( almost)
