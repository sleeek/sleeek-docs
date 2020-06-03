---
id: jira-server-applink-en
title: Configuration on your Jira Software Server
sidebar_label: Linking with Jira Software Server (en)
---

Sleeek uses REST APIs to retrieve information from JIRA Software Server.
To use REST API, [it is necessary to authorize the API usage by the user using the OAuth 1.0a protocol.](https://developer.atlassian.com/server/jira/platform/oauth/)  
In order to start this authorization process, pre-configuration on the JIRA Software Server side is required.
If you get an error message stating "Registration on JIRA Server is required" when setting up linkage with JIRA Server on Sleeek, proceed with the registration process according to the steps below. 

Please note that this work is only required once for each JIRA Software Server.
Even if you set up multiple links between a JIRA Software Server and Sleeek, you do not need to repeat the registration process multiple times.
For example, if you have a JIRA Software Server running at `https://jira.example.com`, and you have 3 users connected to Sleeek,
all users can start the authorization process from the Sleeek side without having to repeat the JIRA pre-configuration process if it is completed once.

This work requires administrator rights on JIRA Software Server. Those who do not have administrator rights will need to ask a user with administrator rights.


## Setup Procedure

1. Log in to JIRA and click "JIRA Administration" > "Applications" from the settings menu on the upper right (If there is no transition to the settings screen in this menu, there are insufficient privileges).
Contact a JIRA administrator and request the change or obtain sufficient admin privileges.

![Step 1](../../img/docs/integration/jira-server-applink-en/step1.png)

2. When the administrator screen is displayed, click \[Integrations\] > \[Application Links\].

![Step 2](../../img/docs/integration/jira-server-applink-en/step2.png)

3. When "Configure Application Links" is displayed, enter https://app.sleeek.io in the text box and click "Create New Link".

![Step 3](../../img/docs/integration/jira-server-applink-en/step3.png)

4. An error message will display, however, it is not related to the operations in this procedure manual. Please click "Continue"

![Step 4](../../img/docs/integration/jira-server-applink-en/step4.png)

5. Set the following contents in the displayed dialog box and click \[Continue\].
* Enter any "Application Name"
* Select "Generic Application" for "Application type"
* Check the "Create incoming link" checkbox

![Step 5](../../img/docs/integration/jira-server-applink-en/step5.png)

6. Set the following contents and click the "Continue" button.
* Enter `SleeekJiraLink` in "Consumer Key"
* Enter `Sleeek` in "Consumer Name"
* Enter the following character string in "Public Key"
```text
-----BEGIN PUBLIC KEY-----
MIGfMA0GCSqGSIb3DQEBAQUAA4GNADCBiQKBgQCbqUf0AjETHMyskzpc3fq/i3VR
kEzfc9rh/FHoiyDAhNArQUW+a/07tB0M7F0X90BI6XvVkixaPDoEquAw6VMlhteH
J0DBuDjNC+mIaGjXw6woUta+wS2dV6BNx3DPH29BkdKSNkXmvkYoj+fwy3+dviQC
lghtzKE3/zcuxsVc7QIDAQAB
-----END PUBLIC KEY-----
```

![Step 6](../../img/docs/integration/jira-server-applink-en/step6.png)

7. If the registered setting items are displayed in the application link list, you are done.

![Step 7](../../img/docs/integration/jira-server-applink-en/step7.png)

This completes the settings on JIRA. Let's connect to JIRA from Sleeek!