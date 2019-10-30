---
id: slack
title: Connect with Slack
sidebar_label: Connect with Slack
---


Many companies utilize Slack to help facilitate communication on a daily basis. Sleeek helps to make Slack communication even better by providing insightful data from analyzing source code, issue tracking system, and conversations of team members within your Slack workspace. After connecting your Slack, you can enjoy:

* Daily report summary (for project managers) 
* Daily priority list (for members) 

This page cplains how to connect Sleeek with your workspace in Slcak. 


![GitLab_conect_figs.png](../../img/docs/integration/slack/Slack_conect_figs.png)

## Setup Procedure

1. Login to Sleeek, then go to the “Settings” page. If you haven’t created any dashboards yet, please create a dashboard first. Pick a dashboard you want to connect with Slack (the dashboard already connected with Slack has colored Slack icon with a green button).

![Step 1](../../img/docs/integration/slack/step1.png)


2. Install the Slack chat bot “Shep” by clicking the “Connect with tool” button.

![Step 2](../../img/docs/integration/slack/step2.png)


3. You are then transferred to a setting page in Slack. Select a slack workplace you want to connect to Sleeek, then “authorize” Shep to do following items:

* Confirm your identity on <User Name>
* Access information about your channels
* Add slash commands and add actions to messages (and view related content)

Note that you need several access rights to install the Slack bot into your workplace. If you have any errors related with access levels, please contact an administrator of your workspace.

![Step 3](../../img/docs/integration/slack/step3.png)


4. You will be then redirected back to the Sleeek web site. The list of channels you can access are shown. Please pick one of channels that you want to connect to Sleeek. Shep will then start communication with members who join this channel.

![Step 4](../../img/docs/integration/slack/step4.png)


5. Almost done! The final step is the configuration of the Sleeek panel called “How’s each member doing?”. For this panel, the Slack chat bot, Shep, is asking the overall status to each member. You can configure:

* Who should or shouldn’t Shep communicate with? (Default: all members who join the channel) 
* When should Shep ask a question? (Default: 5:00PM)


![Step 5](../../img/docs/integration/slack/step5.png)


6. Congratulations! Your Slack channel is connected to Sleeek. If you go back to the Setting view, you can see the Slack icon has green button. It means your Slack channel is successfully connected.

Now you can confirm each member’s status on the “How’s each member doing?” panel. (Of course, it takes at least one day to show each member’s answers to the question). Shep only has this function right now, but will be updated to have more useful functions for your software project. Stay tuned!

![Step 6](../../img/docs/integration/slack/step6.png)
