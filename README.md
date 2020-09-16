# Yearly_audit
Check yearly trends of your business
Basic idea of the project is to get yearly trends of your business expenses and totals.

This is a web application created with help of Python Flask.
###################################################################################

Details:
  Insted of database used MS excel for storing data.
    MS Excel contains DATE, DAy, Amount, Expenses and Total Amount columns.
  Used python libraries:
    Pandas, xlxswriter, plotly, flask, os, datetime and openpyxl
  IDE used:
    Pycharm
###################################################################################   

Project template:
Project name
  files
    Contains Excel files
  templates
    contains all .html files except plot.html
  static
    contains plot.html (Since it is a static html file)
  shop.py
###################################################################################

Required code changes:


###################################################################################
Manual:
Run the .py file after placing all files as per mentioned above

Once started in browser(chrome) Prompts for file name.
  If given file name exists:
    Provides option for Adding or Filter data in excel
      Add - Asks for date and details to add
      Filter - Choose based on options to filter
    Once adding or filtering of data complets it display the outpuy based on your selection and also displays plot link.
      Plot - It displays the trends of your data in excel sheet as per filtered craiteria.
  If given file name does not exist:
    After clicking on submit prompts for year to select.
    Generates MS excel with dates and day according. (For financial year given_year - given_year+1)
