# Manage-Data-Governance-and-Retention
Create a static 10 year deletion retention policy for Teams. Create forever label for MS365 groups.

<h2>Description</h2>
Lab consists of a create and perform an eDiscovery hold for Content Search by using Compliance Purview Portal. Microsoft Purview eDiscovery (Standard) in Microsoft Purview provides a basic eDiscovery tool that organizations can use to search and export content in Microsoft 365 and Office 365.  can also use eDiscovery (Standard) to place an eDiscovery hold on content locations, such as Exchange mailboxes, SharePoint sites, OneDrive accounts, and Microsoft Teams.
<br />


<h2>Environments Used </h2>

- <b>Microsoft Purview Compliance Portal</b> 

<h2>Prerequisites</h2>

-<b> Configuration Profile can be created or modified by anyone assigned the following roles:
 - eDiscovery Manager
 - eDiscovery Administrator
 - Case Management
 - Global Administrator
 </b>
- <b> Licenses: Exchange online Plan 2 or  Microsoft 365 E3 OR Office 365 E3 license or higher OR Office 365 E1 license with a SharePoint Online Plan 2 OR OneDrive for Business Plan 2 add-on license</b>

<h2>Program walk-through:</h2>

<h3>Steps: </h3>

1.  Go to  Microsoft purview portal --> Data lifecycle management --> Microsoft 365
2.	Retention policies --> new retention policy --> give name and choose type of policy
3.	Locations --> select Teams  
4.	Select Retention period ’10 years’
5.	Review finish and Submit
6.	Go to ‘Labels’ tab in Data lifecycle management --> create new --> name it
7.	Define label settings ‘Forever’,  period ‘Forever’ --> Review Finish
8.	Go to Label policies tab --> publish label --> choose a label
9.	Choose scope ‘static’ and choose locations
10.	Name a policy and Finish it

	
<h3>Screenshots:</h3>

<p align="center">
Datalifecycle Management & MS365:  <br/>
<img src="ms 365 1.png" height="50%" width="50%" />
<br />
<br />
Create a new Retention policy & Give a Name: <br/>
<img src="retention policy name.png" height="50%" width="50%" />
<br />
<br />
Select a Scope of Retention policy: <br/>
<img src="scop.png" height="50%" width="50%" />
<br />
<br />	
Choose a Location (Teams): <br/>
<img src="location.png" height="50%" width="50%"/>
<br />
<br />
Select Retention Period: <br/>
<img src="decide period.png" height="65%" width="50%"/>
<br />
<br />
Query Section: <br/>
<img src="query.png" height="65%" width="50%"/>
<br />
<br />
Review & Submit: <br/>
<img src="review.png" height="65%" width="50%"/>
<br />
<br />
Result: <br/>
<img src="result.png" height="65%" width="50%"/>
<br />
<br />
Query Section: <br/>
<img src="query.png" height="65%" width="50%"/>
<br />
<br />
Review & Submit: <br/>
<img src="review.png" height="65%" width="50%"/>
<br />
<br />
Result: <br/>
<img src="result.png" height="65%" width="50%"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
