# PT3-E034_IsMenuItemAthorized
IsMenuItemAthorized() PeopleCode Function

PeopleTools Tech Tips    
Randy Groncki

2023-03-19

Different users have different navigational access to PeopleSoft.  It’s a feature of the system.  Administrators, managers and users of specialty areas have navigation access to pages that other users don’t even see in their menu and search results.   

IsMenuItemAuthorized() is a delivered PeopleCode function that tells us, True or False if the current user has access to a specific page.

## Install
Import project into PeopleSoft Demo Environment
Grand Role X_PT3_ALL_EMPLOYEES to all test employees
Grand Role X_PT3_ADMIN Only to "Management" employees who can see the "Confidential" data

### Web Posting: https://peopletoolstechtips.com/TBD

### YouTube demo: https://youtu.be/TBD

### Contact:  
* randy@peopletoolstechtips.com  
* PeopleToolsTechTips@Gmail.com

This file contains all the objects referenced in the video and document.

## PeopleTools Project is using PeopleTools 8.59.12
  * This contains all the components, pages, records and PeopleCode used in the demonstration.
  * The target database must be minimal 8.58 PeopleTools

* X_PT3_E034_ISMENUITEMAUT (folder - PeopleTools Project)  
* X_PT3_E034_ISMENUITEMAUT.zip  (All Objects)
