---
id: gitlab
title: Connect with GitLab
sidebar_label: Connect with GitLab
---


To give you more insightful information and actionable suggestions, you can connect your [GitLab](https://about.gitlab.com/) to Sleek. We analyze source code  and issue management information along with feedback from your team members to provide comprehensive input for your team. 

Sleeek connects to GitLab using [OAuth2 protocol](https://docs.gitlab.com/ee/api/oauth2.html). It does so in order to access source code information and its historical transition data (including issue information if you use the issue-tracking feature). ([learn more about our security](https://sleeekbeta2019.squarespace.com/security)). 

![GitLab_conect_figs.png](../../img/docs/integration/gitlab/GitLab_conect_figs.png)

## Setup Procedure

1. Connecting to GitLab can done by 
- going through the initial setup process
- accessing the dashboard setup page

The initial setup screen when you first log into Sleeek will show a set of panels. You will need to select one of the 'Connect to Tools' button associated with GitLab, after which you will be taken to a page to connect to tools. 

![Initial Setup 1](../../img/docs/integration/gitlab/Integration-First-Page-GitLab-rd.jpg)

Once at the connect to tools page, select GitLab. Then you will be taken to a GitLab connection process flow.

![Initial Setup 2](../../img/docs/integration/gitlab/Integration-02-ToolsSelect-Gitlab.png)

If you have already connected some tools and want to connect to GitLab, you will need to go to the dashboard settings page on the left sidebar and click on dashboard, and then select 'GitLab' on the dashboard you choose. This will then take you to the GitLab connection process.

![Dashboard Setup Page](../../img/docs/integration/gitlab/Integration-02-ToolsSelect-FromSettingsPage-Gitlab.png)


2. Please input your GitLab server URL and click the "Next" button. If it is not able to access your Gitlab repositories, please contact your network administrator. 

    The URL that you provide:
- must NOT have a path (e.g. https://example.gitlab.com/path)
- must NOT contain any parameters (e.g., https://example.gitlab.com/?q=target)

>Sleeek currently supports cloud hosted GitLab servers only. If you need to connect to an on-premise version of GitLab, please contact us.

![Step 2](../../img/docs/integration/gitlab/step2.png)


3. In order to add Sleeek as a new application in GitLab, you will need to get to the GitLab application setup page and follow the instructions below. 

- Input name "Sleeek" on GitLab application page 
- Copy this Redirect URI link (https://app.sleeek.io/settings/gitlab/auth/callback) on Gitlab application page
- Check the two scopes below: 
- Click "Save application"

![Step 3](../../img/docs/integration/gitlab/step3.png)

4. The integration is completed. Sleeek analysis program starts running in order to create panels in the project view. It takes at least several minutes (depends on the data size of your repository).
