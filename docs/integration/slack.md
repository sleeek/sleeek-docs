---
id: slack
title: Connect with Slack
sidebar_label: Connect with Slack
---


Slack is a necessary tool for software developers to help to facilitate communication on a daily basis. Sleeek helps to make Slack communication even better. Sleeek gets data from your Slack workspaces using a Slack Chat Bot called “Shep” (Fig. 1). Once Shep is installed in your Slack workspace,  it gathers a list of channels in the workspace. From there, you can select channel members in your project which Shep will begin to have communication with.

After you connect Sleeek to Slack, you can enjoy:

* “How’s each member doing?” panel in order to check each member’s current status
* “Is your team hot enough?” panel (to be published in July) to check each member’s contribution activity.

This page explains how to connect Sleeek with your workspace in Slack.


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

<iframe title="vimeo-player" src="https://player.vimeo.com/video/347007590" width="640" height="360" frameborder="0" allowfullscreen></iframe>
