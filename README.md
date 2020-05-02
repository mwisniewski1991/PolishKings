# Polish Kings

## Goal:
Scrap data regarding Polish Kings/Lords, when their live and rule.\
Make charts to visualize gathered data.

Link to visualization: https://observablehq.com/@mwdataweb/polish-kings

## Stack
- Python
    - BeautifullSoup
    - Pandas
- JavaScript
    - D3.js

## Project details
### Data
Data has been scraped from page *https://ciekawostkihistoryczne.pl* with Python and Beautifull soup. Raw data is stored in csv file. *PolishKings_rawData.csv*. It was necessery to do some data clean-up.

Two raw column has been divided in more details data. Result of this is store in final file *PolishKings_cleared.csv*. After this action I had information about kings and when they lived.

I wanted also to show when they rule over the country. I used data from *Wikipedia* to complete my data. I decide that it may be a litte frustrating to scrap another table and try to joined it with my current data in csv file so I decided to add data manually.


### Visualization
I've use Observable to make quick data visualization.\
I use circles and lines to show when kings rule over country.\
White dashed lines show year of birth and death.\
Hover effect show years for each person and change text color to white to help recognize kings for data.

History is a very complex topic and the data may be imprecise. I based only on meantion above sources.

Project is only for education purpose.


## Developer:
**Mateusz Wiśniewski**

Check my other repositories:
https://github.com/mwisniewski1991?tab=repositories