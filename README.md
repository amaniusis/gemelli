# gemelli
Programming learning resources and an economic data project.

##Learning Materials


[Introduction to Computer Science: Harvard CS50x](https://cs50.harvard.edu/x/2021/)

[Introduction to Database Design: Database Design for Mere Mortals: 25th Anniversary Edition, 4th Edition](https://3lib.net/book/16352060/f49fed)

**Introduction to Python**

[Setting up VSCode for Python by Corey Schafer](https://www.youtube.com/watch?v=-nh9rCzPJ20&t=74s)

[Python Pandas Tutorial by Corey Schafer](https://www.youtube.com/watch?v=ZyhVh-qRZPA&list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS)

**Introduction to SQL -> to add**

##Project:

Acquire global economic trade statistics and prepare a country-wise overview of import and export data that would be published on the web.

**Data Sources:**

- World Bank 

- OECD: API (JSON)

Format URL for API call: `http://stats.oecd.org/SDMX-JSON/data/<dataset identifier>/<filter expression>/<agency name>[ ?<additional parameters>]`

Variables: 
- dataset identifier; 
- filter expression;
- agency name;

- optional parameters: startPeriod, endPeriod; dimensionAtObservation; detail;

UpdatedAfter
  
Dataset: Monthly International Merchandise Trade (IMTS)
[Data API Call](https://stats.oecd.org/SDMX-JSON/data/MEI_TRD/XTEXVA01+XTIMVA01+XTNTVA01.AUS+AUT+BEL+CAN+CHL+COL+CRI+CZE+DNK+EST+FIN+FRA+DEU+GRC+HUN+ISL+IRL+ISR+ITA+JPN+KOR+LVA+LTU+LUX+MEX+NLD+NZL+NOR+POL+PRT+SVK+SVN+ESP+SWE+CHE+TUR+GBR+USA+EA19+EU27_2020+G-7+OECD+NMEC+ARG+BRA+CHN+IND+IDN+RUS+SAU+ZAF+BRIICS.CXMLSA+CXML+NCMLSA+NCML+GPSA+GYSA.M/all?startTime=2014-01&endTime=2021-08&pid=27d76367-1c01-4c81-962a-2dc28bb01fc6)

!!!To think how to check for the updates of the data

[Structured query](https://stats.oecd.org/restsdmx/sdmx.ashx/GetDataStructure/MEI_TRD?pid=27d76367-1c01-4c81-962a-2dc28bb01fc6)
  
  
  
  
**Learning objectives:**
1. ETL pipe from a data source to local database.
2. Data manipulation.
3. Good code codumentation and best code practices.
4. Set up a website and publish infographics.


