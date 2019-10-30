---
id: jira
title: Connect with Jira
sidebar_label: Connect with Jira
---

JIRA is enterprise software provided by Atlassian used for bug tracking, issue management, and project management.By connecting Sleeek and JIRA with API token, you can collect and visualize the progress status of issues and projects managed by JIRA and member comments linked to them.

By connecting JIRA to Sleeek to which Repository management system has already been connected, it is possible to comprehensively grasp the information of all elements that make up a project such as Code, Issue and Member, and prepare in advance for future project risks. Become.


## Setup Procedure

1. Login to Sleeek, then go to the “Settings” page.You can view the registered Dashboard on this page, so click the JIRA icon on the Dashboard to which you want to connect JIRA.

![Step 1](../../img/docs/integration/jira/step1.png)


2. Issue API token from JIRA side. Click on the [Atlassian account page] to go to the screen on the JIRA side.

![Step 2](../../img/docs/integration/jira/step2.png)


3. Click on the [Create API token] button, a modal will be displayed called Create your API token. Enter ‘Sleeek’ (optional) for the Label and click the [Create] button. 

![Step 3](../../img/docs/integration/jira/step3.png)


4. A new API token will be issued, so be sure to copy it to the clipboard.

![Step 4](../../img/docs/integration/jira/step4.png)


5. Return to the Sleeek screen, enter the URL of your JIRA instance, Your Atlassian account email address, and the API token, and click the [Next] button.

![Step 5](../../img/docs/integration/jira/step5.png)


6. Check the checkbox of the projects of JIRA you want to connect to the Dashboard, and click the [Pick up] button.

![Step 6](../../img/docs/integration/jira/step6.png)


7. The integration is completed. Sleeek analysis program starts running in order to create panels in the project view. It takes at least several minutes (depends on the data size of your repository).
