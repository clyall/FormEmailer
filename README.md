# FormEmailer
This is a fork of Henrique Abreu's FormEmailer for Google Forms / Sheets. His original project can be found here:
https://sites.google.com/site/formemailer/form-emailer

His script has been updated to a Scripts Add-on, which can be installed in Google Sheets.

## Getting Started
If you have not already, please install this add-on on the sheet you would like the program to run on. Download can be found here:
TODO INSERT LINK

### Script Installation
Once you have download the add-on, you should see a new menu at the top of your spreadsheet called "FormEmailer". If you select this menu, click the "Install" button on the drop down that appears.

Select your language and the sheet you would like FormEmailer to send emails about. Once you select the "Install" button, the add-on will setup it's configuration and create a new sheet called "FormEmailer". This sheet contains all the configuration for the add-on; please do not modify it directly.

### Time-Trigger Installation
In order for FormEmailer to work properly, you must setup a "Time-trigger" to have this add-on run automatically in the background. Below are the steps to get this setup:

1. Open your spreadsheet, and select "Tools > Script Editor" on the top menu. This should open a new tab titled "FormEmailer"
2. On this tab, select "Edit > Current Project Triggers" on the top menu. This will also open a new tab.
3. In this tab, click the "Add Trigger" button found at the bottom right. 
4. A dialog will popup asking for a bunch of configuration values. You can use the values found below as defaults:
   TODO INSERT SCREENSHOT OF CONFIG 
   Note that you can change the "Select type of time based trigger" to have this add-on run autmoatically at any given time interval.

5. Select "Save" on the popup window
6. If eveything went OK, you should see the following row displayed:
   TODO INSERT SCREENSHOT OF SAVED CONFIG
   
7. You can now close the two tabs that were opened, and refresh your spreadsheet.
   
