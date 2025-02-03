# DATA601HW4  

#### https://github.com/evan-losier/DATA601HW4  


#### Regex  

Regex was used for data cleaning by detecting all postal code formats  
and grouping standardizing them to contain only capital letters and  
numbers with a space separating the first three characters from the  
second three characters.  

It was also used to remove commas in numbers that contained commas and  
were processed as strings while being read from the csv. It was also  
supposed to be used to remove unnecessary information from property  
names and addresses, but I was unable to spot information that needed  
to be removed.  


#### Methodology  

Data was imported, cleaned, processed, and visualized using a variety  
of python libraries and methods commonly used in data analytics.  
Pandas was used for the majority of data handling, regex was used for  
cleaning, and Seaborn was used to create visualizations.  


#### Challenges Faced  

The main challenge faced was in the use of regex for cleaning data.  
Initially when the data was imported and numerical columns were being  
read as text columns, I discovered that the thousands parameter  
could be used by the csv_read function to automatically read the  
problematic columns as numeric. Going back and using regex to convert  
the columns instead was more time consuming. Another challenge faced  
was trying to understand what "meaningful text" in Property Names and  
Addresses was referring to given that nothing stood out about the data  
in those columns and they weren't being used in a way that would  
conflict with the main analysis tasks.  