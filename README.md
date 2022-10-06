# Web-Scrapping-Cars-24

Web Scraping : web scraping is the process of collecting structured web data in an automated fashion.its also called web data extraction.

here i have perfomed some steps to do this project                                                                                                                      
         1.Process of extraction of data 
           ->Dta extraction is the process of collecting or retreving disparate types of data from a variety of sources
         2.Creation of dataframe
             ->Aligning the data in a structured format using rows and columns                                                                                              
         3.Process of cleaning of dataframe
             ->it is a process to detecting and correcting inncorrect and unwan  
         4.Data Visualization
             ->it is the process of translating large data sets and metrics into charts,graphs and other visuals
  
         LIBRARIES I HAVE USED IS:
         numpy, pandas, requests, Beautiful soup, warnings, matplotlib, seaborn.
  
  
        Firstly we need to copy the URL of the webpage to which web scrapping has to be done
        A request is sent from the jupyter note book to the webpage by using requests library after sending request a response in the form of HTML is obtained from the  webpage  
        Beautiful soup library is helpful to parse this HTML content then we need to inspect requried data from the webpage.
        A dataframe is a two dimensional labeled data structure with columns of potentially different types in simple words is a data structure wherein data is aligned in a tabular fashion that is rows and columns 
        Data Cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect,incomplete,irrevelent,duplicated or improperly formatted
        the data we have extracted is the form of unstructured format
        we need to clean all the null values and set it to a definite data types
        data cleaning is done using 'Regular Expression'
        Regular Expression : (Regex) are essentially text patterns that we can use to automate searching through and replacing elements within strings of text.this   trouble of   having to search through mountains of text by hand
        check the null values it is very crucial part
        Finally done the EDA(Expolatary Data Analysis
