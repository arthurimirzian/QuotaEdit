Edit Quotas - version 1.7 (2016-02-26)
===========

UI for viewing and editing quotas for Collaborative Forecasting
![Screenshot](QuotaUI.png "Screenshot from Spring '16")

* Edit Quotas is a Salesforce.com managed app for viewing and editing quotas. Check out the 
  AppExchange listing [here](https://appexchange.salesforce.com/listingDetail?listingId=a0N3000000B41EqEAJ). 
  
* Access to quotas is governed by the following:
  - Full read/write to all quotas for those with View All Forecasts and 
    Manage Quotas perm
  - Full read/write to subordinate quotas only for those with Manage Quotas
    perm
  - Read only for subordinate quotas for those without the Manage Quotas perm
  
* Version 1.7 is adapted for the Spring '16 release. 
 - Support for Custom Fiscal Years
 - Easier entry for customers using Quarterly Forecasts
 - Localization to French
 - Redesigned UI

* Installation instructions
 - Install this package from AppExchange for All Users
 - For the users you want to enable:
   - Check their Manage Quotas and View All Forecasts perm
   - For their Profile, enable access to the page under Enabled Visualforce Page Access and/or Enabled Apex Class Access lists
  

Known issues
------------
* In edit mode, quotas that are whole number quotas will appear with only one digit after the period, for example 
  USD 123.0 
  
