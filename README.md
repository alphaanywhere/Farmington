# Farmington

The sample application built for Alpha DevCon 2020.

Farmington is a b2b e-commerce application that works on both web and mobile devices.

![Farmington Login Screen](/screenshots/loginScreenshot.png)

This workspace contains several files:
 
- farmington_app.a5wcmp : This is the fully completed application
- farmington_app_part1.a5wcmp : This is the application built during DevCon 2020's "App Building from Scratch" training session
- images : Folder containing the Farmington logo.
- products : Folder containing product images. These images are referenced in the Farmington.xlsx file.
- Farmington.xlsx : An Excel 2007 file that contains sample Product and Farm data
- Farmington.db : A SQLite database that contains sample Product and Farm data
- css/Farmington : The final Web Theme for the application
- screenshots: Folder containing screenshots of the final application

**The files in this repository require Alpha Anywhere 4.6.2.5 (released September 20, 2020) or newer.**

## Using SQL Instead of Excel

Two data sources are included in this repository. To use the SQL data source for the lists in the components, you will need to manually setup the data source for each component, including re-selecting the tables and columns.
