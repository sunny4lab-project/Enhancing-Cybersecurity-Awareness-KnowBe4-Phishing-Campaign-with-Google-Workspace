#  KnowBe4 Phishing Campaign Integration with Google Workspace

*<img width="866" alt="Final result Clicks" src="https://github.com/sunny4lab-project/Enhancing-Cybersecurity-Awareness-KnowBe4-Phishing-Campaign-with-Google-Workspace/assets/139194279/5c4158e2-1013-44ce-86f9-c3200cb57742">*


**Project Overview:**

As part of the cybersecurity awareness initiative, this project aims to simulate phishing attacks using KnowBe4, a leading cybersecurity training platform, integrated with Google Workspace. By conducting phishing simulations tailored to our organization, we aim to raise awareness about the risks of phishing and enhance participants' ability to recognize and respond to phishing threats effectively.

**Project Objectives:**

▶️ *Set up KnowBe4 integration with Google Workspace to facilitate phishing campaign management*.

▶️ *Design and execute phishing simulations targeting members of our organization*.

▶️ *Analyze campaign results to assess susceptibility to phishing attacks and identify areas for improvement*.

▶️ *Develop and deliver educational resources and training modules to enhance cybersecurity awareness*.

***Prerequisite*** 
<details><summary>Click Here for Details</summary>
  
  *You will need the following account set up before proceeding with the project*
  
➡️Google Workspace Domain account 
  
➡️ KnowBe4 Account.
  
</details>

# **Project Steps**
<details><summary>Details Here</summary>

**Step 1:** *Integration Setup*
👨‍💻 Log into your account Click on the Account user ID at the top to the right and select "Account Settings". 

*<img width="950" alt="Account Settings" src="https://github.com/sunny4lab-project/Enhancing-Cybersecurity-Awareness-KnowBe4-Phishing-Campaign-with-Google-Workspace/assets/139194279/50da7381-db36-4d55-a9ff-e348954cc089">*

🧑‍💼 Then scroll down and click "Phishing" to the left and select Direct Message Injecting (DMI), then, *click the Add DMI Connection*. Also, make sure to select *Google Workspace*

*<img width="699" alt="Phishing DMI" src="https://github.com/sunny4lab-project/Enhancing-Cybersecurity-Awareness-KnowBe4-Phishing-Campaign-with-Google-Workspace/assets/139194279/a8c8d9f6-f53b-47a1-98cf-9a0c7291d798">*

Authorize Integration:

- Follow the prompts to authorize the integration between KnowBe4 and Google Workspace.
- You may need to log in to your Google Workspace administrator account and grant permission for KnowBe4 to access your Google Workspace data.
- A couple of things you will need for this integration to be complete.
-      Client ID for KnowBe4 that looks like this  (1170*******************) and the following scopes or permissions:
                                                                              ↙️
                     https://mail.google.com/
                     https://www.googleapis.com/auth/gmail.insert
                     https://www.googleapis.com/auth/gmail.modify
  
*<img width="713" alt="Google Workspce intergration" src="https://github.com/sunny4lab-project/Enhancing-Cybersecurity-Awareness-KnowBe4-Phishing-Campaign-with-Google-Workspace/assets/139194279/d58d815a-2c92-4b77-ad9a-d080d4394556">*

-     You need a Domain name
      Enter an email address from your Google Workspace domain:

    
*<img width="716" alt="Add Domain name and an email from your dmain" src="https://github.com/sunny4lab-project/Enhancing-Cybersecurity-Awareness-KnowBe4-Phishing-Campaign-with-Google-Workspace/assets/139194279/59e65a83-7b50-4933-9865-df2f0ae061c1">*

Configure Integration in Google Workspace:
- To authorize KnowBe4 in Google Workspace, You need to log in to https://admin.google.com/
  
💻 Navigate to *security* on the left Navigation Panel then select *Access and data control*, and click on _API Controls_. Click on *Manage Domain Wide Delegation*

*<img width="725" alt="How to locate manage domain wide delegation" src="https://github.com/sunny4lab-project/Enhancing-Cybersecurity-Awareness-KnowBe4-Phishing-Campaign-with-Google-Workspace/assets/139194279/68c485b6-b7ca-413e-9c80-3fbfaf139849">* 

The final stage of this integration is to add API Client ID to your settings. So, Click on _Add New_ and get the KnowBe4 Client ID from the previous KnowBe4 phishing Integration screen above. You will also need a Domain name and any email from your Domain to finalize the integration. 

*<img width="716" alt="Add Domain name and an email from your dmain" src="https://github.com/sunny4lab-project/Enhancing-Cybersecurity-Awareness-KnowBe4-Phishing-Campaign-with-Google-Workspace/assets/139194279/ad8b2fe9-5d30-4376-ad8f-9b676ee03541">*


After configuring the integration settings, verify that the integration between KnowBe4 and Google Workspace is successfully established.
You may be provided with confirmation messages or status indicators indicating that the integration is active.
</details>
