---
id: gitlab
title: Connect with GitLab
sidebar_label: Connect with GitLab
---


GitLab is a Git base repository management tool, and also provides issue-tracking and CI/CD pipeline features, developed by GitLab Inc. Sleeek connects to your GitLab with the OAuth2 protocol in order to get source code information including its historical transition data, and issue information if you use issue-tracking feature.

Using these data, Sleeek shows productivity of each member, relationship between source code and issue, review comments of every code committed to the repository by an automated source code review tool, etc.

Note that Sleeek does READ access to GitLab only and does not do any WRITE access.

![GitLab_conect_figs.png](../../img/docs/integration/gitlab/GitLab_conect_figs.png)

## Setup Procedure

1. Login to Sleeek, then go to the “Settings” page. If you haven’t created any dashboards yet, please create a dashboard first. Click GitLab icon in a dashboard you want to connect to GitLab (the dashboard already connected to GitLab has colored GitLab icon with a green button).

![Step 1](../../img/docs/integration/gitlab/step1.png)


2. If you create a new dashboard, you will see the Dashboard setup page. Please select GitLab, then press Next.

![Step 2](../../img/docs/integration/gitlab/step2.png)


3. Please input your GitLab server URL and click the ‘Next’ button. If it is not able to access your Gitlab repositories please contact your network administrator. And please note: internet access is required to set up with Sleeek.

![Step 3](../../img/docs/integration/gitlab/step3.png)


4. To connect to your Gitlab repositories, you need to install Gitlab OAuth Applications on your Gitlab account. In screen below, please click ‘Copy’ button to copy Redirect URL in (1) and Click ‘Install App via GitLab’ in (2). 
After that, the Gitlab set up screen will open up in the next tab; get your ApplicationID and Secret from this page.

![Step 4](../../img/docs/integration/gitlab/step4.png)


5. Please continue to the new tab (Applications setup page). 

Enter your preferred name and Redirect URL which you copied from Sleeek. Check the ‘API’  and ‘read_repository’ boxes and finally click ‘Save Application’. 

![Step 5](../../img/docs/integration/gitlab/step5.png)


6. You also need to enter  'Application ID' and 'Secret' from  the Gitlab for dashboard configuration.Please make sure to note your Application ID and Secret. You can take note when using copy and paste buttons easily.

![Step 6](../../img/docs/integration/gitlab/step6.png)


7. Let’s go back to the Sleeek site and enter copied 'Application ID' and 'Secret' in Sleeek web site. Click Next to finish this integration process.

![Step 7](../../img/docs/integration/gitlab/step7.png)


8. The integration is completed. Sleeek analysis program starts running in order to create panels in the project view. It takes at least several minutes (depends on the data size of your repository).


<iframe title="vimeo-player" src="https://player.vimeo.com/video/337503254" width="640" height="360" frameborder="0" allowfullscreen></iframe>