# Manager-Interview-Quotes
Data Scrapping from url='https://devtomanager.com/interviews/page/{1}/'
# Data of successful Manager interview quotes,tags,date,company etc.
# Procedure:-
The url has html block for each Quote info.

Used requests library to get url.

Used BeautifulSoup i.e bs4 library to extract data from html tags.

I considerd each block as one and extracted information from it then used list comprehension to get data of all blocks.

After that used for loop and format() function to get data from next 5 pages.

Faced some difficulties while extracting date and tags but solved that by creating dummy list then splitting the string and then indexing.

Faces issue with job profile and company but solved it by splitting the string at ' at'.(Using space so that it will split only at first)

Creating functions to extract multiple data and creating dataframe.

Finally,converted the DataFrame to a .csv file.

Changing the data type of columns as required for future analysis.

Data shape is (25, 7).
