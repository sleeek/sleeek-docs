---
id: github
title: Connect with GitHub
sidebar_label: Connect with GitHub
---

Sleeek connects to your GitHub with Sleeek GitHub App in order to get source code information including its historical transition data, and issue information if you use issue-tracking feature.


The Sleeek GitHub App has only read permission to your repository. Using these data, Sleeek shows productivity of each member, relationship between source code and issue, review comments of every code committed to the repository by an automated source code review tool, etc.

## How to connect to GitHub

GitHub is a web-based hosting for repository management tool using Git. It also provides issue-tracking, bug tracking, and wiki for every project.  Sleeek  connects to your GitHub with Sleeek GitHub App (Fig. 1) in order to get source code information including its historical transition data, and issue information if you use issue-tracking feature. The Sleeek GitHub App has only read permition to your repository. If you need more information about GitHub App, please refer to GitHub Apps on your GitHub organizations.

Using these data, Sleeek shows productivity of each member, relationship between source code and issue, review comments of every code committed to the repository by an automated source code review tool, etc.

![GitHub_conect_figs.png](../../img/docs/integration/github/GitHub_conect_figs.png)

## Procedure

1. Login to Sleeek, then go to the “Settings” page. If you haven’t created any dashboards yet, please create a dashboard first. Click GitHub icon in a dashboard you want to connect to GitHub (the dashboard already connected to GitHub has colored GitHub icon with a green button).

![Step 1](../../img/docs/integration/github/step1.png)


2. If you create a new dashboard, you will see this Dashboard setup page.  Please select GitHub, then press “Next”.

![Step 2](../../img/docs/integration/github/step2.png)


3. To connect with your GitHub repositories, you need to install Sleeek GitHub Apps on your GitHub organizations. Click ‘Install Apps via GitHub’. Then move to setup page on GitHub. 

![Step 3](../../img/docs/integration/github/step3.png)


4. In the new tab, please click ‘Install” button on top right.

![Step 4](../../img/docs/integration/github/step4.png)


5. In this screen, please select the Organization name of which you would like to install Sleeek onto.
Note : Each Organization require this process. If you would like to apply multiple organizations, please setup the following process for each organization.

![Step 4](../../img/docs/integration/github/step5.png)


6. Select the appropriate repository in your organization. If you want to apply all, check ‘All repository’. If you want to apply any repository, check ‘Only select repository’.

Once finished, click ‘Install’ button.


7. This is end of the setup process in GitHub’s side. Sleeek analysis program starts running in order to create panels in the project view. It takes at least several minutes (depends on the data size of your repository).


## Add a new organization

If you would like to add a new organization which is not installed into Sleeek yet, you need to proceed with the following process.


> In the current version, the dashboard is not able to link with multiple GitHub organizations.  

If your dashboard has already linked with another GitHub organization, you will not be able to connect. If you want to monitor your GitHub organization which is already linked with Sleeek, create a new dashboard and link that GitHub organization.
Click ‘Dashboard Setting’ on the bottom left corner of the Dashboard screen.

![Add new org](../../img/docs/integration/github/add-new-org.png)

Then, click the GitHub Logo in the Dashboard Name row. 

![Add new org](../../img/docs/integration/github/add-new-org2.png)

Click ‘Install the Sleeek App on other Organization’ in the screen below.

> If another GitHub organization member has already installed Sleeek in the GitHub organization you want to link to, you can select in Select Org.

![Add new org](../../img/docs/integration/github/add-new-org3.png)

Click ‘Install App via GitHub’. Then move to new tab, setup screen on Github side.

![Add new org](../../img/docs/integration/github/add-new-org4.png)

Click ‘Install’ button in the screen below.

> If any of your GitHub organization already has Sleeek installed, the install button may be changed to the ‘Configure’ button, but please proceed as is.

![Add repo](../../img/docs/integration/github/add-repo.png)

You can see organization list. Please select organization you want to install.

> Note: If Sleeek is already installed, it shows ‘Configure’ in organization.

![Add repo](../../img/docs/integration/github/add-repo2.png)

Choose repository in specific organization.

If you want to apply all, check ‘All repository’. If you want to apply any repository, check ‘Only select repository’ and select specific repository you want to apply.
Once finished, click ‘Install’ button.

![Add repo](../../img/docs/integration/github/add-repo3.png)

This is end of the setup process for the GitHub side.
Let’s back to Sleeek and continue to setup in Sleeek.