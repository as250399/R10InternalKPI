# R10InternalKPI
This repository is for KPI app
The application has a main class "WorkItemHistory.cs" with all the preliminary logic. The method "ConnectToTFS()" which has the code to connect the app to tfs. 
The form has 2 inputs, TFS URL (legitimate TFS URL to connect) and WorkItemID (TFS ticket id for item).
Once the user passes WorkiteID in the input, it fetches the history of that with each update and the datetime of the update. 
We are trying to get the following details as output:

Date time difference between the status "Assigned" - "Fixed" which would give the time taken by resource to complete the issue.
