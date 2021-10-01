---
type: rule
title: Do you know where to save reports?
uri: where-to-save-power-bi-reports
authors:
  - title: Mark Liu
    url: https://ssw.com.au/people/mark-liu
related: []
redirects:
  - do-you-know-where-to-save-reports
created: 2016-04-26T14:42:38.000Z
archivedreason: null
guid: 8081d068-60a1-4ee9-a77d-90e3c99c1c9a
---
When creating reports in Power BI, a common place to store them is under the 'My Workspace' workspace. However, this is not good practice unless it is purely for development or testing purposes. You should always save your Power BI reports in a shared workspace because if you leave your company, your report will go too!

<!--endintro-->

::: bad  
![Figure: Bad example - saving report under My Workspace](powerbi-bad.png)  
:::

::: good  
![Figure: Good example - saving report under Group Workspace](powerbi-good.png)  
:::

1. Group workspace requires all users to have a pro license ($10 / month)
2. Group workspace cannot share report and dashboard via embed link
3. Until  Microsoft fixes PowerBI's group sharing, it's better to use My Workspace with a shared account (i.e.  **powerbi@northwind.com** )
