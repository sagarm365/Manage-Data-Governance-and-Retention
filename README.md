# Manage-Data-Governance-and-Retention
Create a static 10 year deletion retention policy for Teams. Create forever label for MS365 groups.

<h2>Description</h2>
Lab consists of a create and pulish Retention Forever Label by using Purview Compliance Portal. Use a retention policy to assign the same retention settings for content at a site or mailbox level, and use a retention label to assign retention settings at an item level (folder, document, email). In this Lab we have create and publish retention policy for Teams and label for Microsoft 365 Groups.
<br />


<h2>Environments Used </h2>

- <b>Microsoft Purview Compliance Portal</b> 

<h2>Prerequisites</h2>

-<b> Retention Policies & Labels can be created or modified by anyone assigned the following roles:
 - Compliance Administrator
 - Global Administrator
 </b>
- <b> Licenses:  Microsoft 365 E5 or Free Trial license</b>

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
Review & Submit: <br/>
<img src="Review & Finish Policy.png" height="65%" width="50%"/>
<br />
<br />
Retention Label Settings: <br/>
<img src="label set.png" height="65%" width="50%"/>
<br />
<br />
Label Settings: <br/>
<img src="r period 2.png" height="65%" width="50%"/>
<br />
<br />
Review Finish & Create Label: <br/>
<img src="label creation.png" height="65%" width="50%"/>
<br />
<br />
Choose location of Publish Label: microsoft 365 groups <br/>
<img src="Location of public label.png" height="65%" width="50%"/>
<br />
<br />
Choose Scope of Publish Label: <br/>
<img src="scope of publish label.png" height="65%" width="50%"/>
<br />
<br />
Result of Publish Label: <br/>
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
