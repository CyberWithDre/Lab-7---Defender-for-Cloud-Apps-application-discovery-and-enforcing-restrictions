# Lab-7---Defender-for-Cloud-Apps-application-discovery-and-enforcing-restrictions
In this exercise, I reviewed cloud app discovery data and configured app restrictions in Microsoft Defender for Cloud Apps. This exercise showed how to identify and govern shadow IT in the organization.



Microsoft Defender for Cloud Apps utilizes logs from network traffic to identify the applications that users are accessing.  Traffic logs from on-premises firewalls will provide a snapshot report on the most common applications and the users that are accessing these apps.  Traffic from managed devices will be fed into the Microsoft Defender for Cloud Apps discovery overview dashboard

<h2>Walk-through:</h2>

<p align="center">
Launch Microsoft Defender portal.
  On the Microsoft Defender portal, in the left navigation menu, expand the Cloud Apps, select Cloud App Catalog:
  <br/>
<img src=https://i.imgur.com/A7M61Wg.png/>
<br />
<br />
In the filter bar, set Category to Cloud storage.

From the list of apps, select Dropbox.

In the app details pane, review the Risk score shown under the General tab.

:  <br/>
<img src=https://i.imgur.com/mYDKOUb.png/>
<br />
<br />
 <br/>
<img src=https://i.imgur.com/5eJVR4A.png/>
<br />
<br />  <br/>
<img src=https://i.imgur.com/8iDvAiM.png/>
<br />
<br />

In this case i didn't show this process, but here's what i did, opened a new browser tab and went to Dropbox at https://www.dropbox.com.

I was able to access the website.

Close the tab for Dropbox.

Return to the Defender for Cloud Apps screen.

In the Dropbox details pane, select Sanction.

 
 
 Restrict Apps in Defender for Cloud Apps
 Return to the Cloud app catalog in the Microsoft Defender portal.

In the list of apps, locate Dropbox.

In the Dropbox details pane, select Unsanction.

Select Save to apply the change.:  <br/>
<img src=https://i.imgur.com/h3kDdHP.png/>
<br />
<br />
  <br/>
<img src=https://i.imgur.com/oRSWrna.png/>
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
