---
id: jira
title: Connect with Jira
sidebar_label: Connect with Jira
---

[JIRA](https://www.atlassian.com/software/jira) is an enterprise software provided by [Atlassian](https://www.atlassian.com/) used for bug tracking, issue management, and project management. By connecting Sleeek and JIRA, you can receive insightful information from our Sleeek-bot. Moreover, if your repository management system has also connected with Sleeek, it is possible to comprehensively grasp the information of all elements that make up a project such as Code, Issue and Member, and prepare in advance for future project risks. 


## Setup Procedure

1. Connecting to Jira can done by 
- going through the initial setup process
- accessing the dashboard setup page

The initial setup screen when you first log into Sleeek will show a set of panels. You will need to select one of the 'Connect to Tools' button associated with Jira, after which you will be taken to a page to connect to tools. 

![Initial Setup 1](../../img/docs/integration/jira/Integration-First-Page-jira-rd.jpg)

Once at the connect to tools page, select Jira. Then you will be taken to a Jira connection process flow.

![Initial Setup 2](../../img/docs/integration/jira/Integration-02-ToolsSelect-jira.png)

If you have already connected some tools and want to connect to Jira, you will need to go to the dashboard settings page on the left sidebar and click on dashboard, and then select 'Jira' on the dashboard you choose. This will then take you to the Jira connection process.

![Dashboard Setup Page](../../img/docs/integration/jira/Integration-02-ToolsSelect-FromSettingsPage-jira.png)


2. Issue API token from JIRA side. Click on the "Atlassian account page" to go to the screen on the JIRA side.

![Step 2](../../img/docs/integration/jira/step2.png)


3. Click on the "Create API token" button, a modal will be displayed called Create your API token. Enter ‘Sleeek’ (optional) for the Label and click the [Create] button. 

![Step 3](../../img/docs/integration/jira/step3.png)


4. A new API token will be issued, so be sure to copy it to the clipboard.

![Step 4](../../img/docs/integration/jira/step4.png)


5. Return to the Sleeek screen, enter the URL of your JIRA instance, Your Atlassian account email address, and the API token, and click the "Next" button.

![Step 5](../../img/docs/integration/jira/step2.png)


6. Check the checkbox of the projects of JIRA you want to connect to the Dashboard, and click the "Pick up" button.

![Step 6](../../img/docs/integration/jira/step6.png)


7. The integration is completed. Sleeek analysis program starts running in order to create panels in the project view. It takes at least several minutes (depends on the data size of your repository).
