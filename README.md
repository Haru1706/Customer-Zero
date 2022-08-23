# Procedure to Access GCP Customer Zero Environment 
## July 12, 2022
##### Version 1.0


## Requesting the GCP Console (Customer Zero environment) access using Infrasec teams
**Request Team Membership:**

This procedure describes the steps to request access to GCP console via Infrasec.

**Steps:**
	
1. Go to DXC Infrasec using VPN: (https://infrasec.svcs.entsvcs.net)

2. Log in with Global Pass credentials
3. Select **"User"** --> **"Team Membership"**
4. Scroll to bottom table titled **"List of Infrasec teams"**
5. Search for the team names to request access as per your needs (Team names should be provided by the Customer Zero project team)

| Infrasec Team Name | Infrasec Function Group Name |
| -----              |  -------- |
| Example: GCP-CZE-PROD-ReadOnlyUsers | dxc-ms-gcp-g-cze-prod-projectviewer |
|                                      | dxc-ms-gcp-g-cze-prod-monitorviewer |
|                                     | dxc-ms-gcp-g-cze-prod-logsexplorer |


6.  Select the desired team (GCP-CZE-PROD-ReadOnlyUsers) and select **"Add"**

7.  Enter business justification for request, then select **"Request Team Membership"**

8.  Request will go to your manager and to the Team owners for approval.

9.  After the user gets the approval of Infrasec Team, please log in to Infrasec portal (https://infrasec.svcs.entsvcs.net)

10. Select **“Password”** tab and click the "init password” for CLMGMT as mentioned in the below screen shot.

11. Once the user clicked the init password tab, the user needs to generate the password and use the same to login to the GCP console. 


![Picture1](https://github.dxc.com/storage/user/133938/files/463c385b-923a-4e39-b3b4-94f2112777dd)

## Access To GCP Console:


![Picture2](https://github.dxc.com/storage/user/133938/files/ffe1f1fd-2618-4c27-96fa-250468d50fb8)



1. Open a private browser window in your browser of choice (Google Chrome is preferred).

2. Navigate to the GCP Sign On URL:
   
   •	Sign On URL: (https://console.cloud.google.com) 
   
   •	You will be prompted with Google Sign in.
   
3. Enter your dxc email, short name @dxcmgmt.com and click on the "Next" button.
  
4. You will be redirected to DXC sign in.
  
5. Enter your username into the box, i.e., <short name>@dxcmgmt.com and click the Next button.
  
6. Sign-in to Cloud Management with <short name>@dxcmgmt.com and your CLMGMTDEV password created in DXC Infrasec.
	
7. Setup the Okta for multifactor authentication and enter your Okta code as the security code when prompted or use push notification. Follow the below steps to setup Okta:
	
   a) Install Okta application on Mobile
	
   b) Click on **+** to add Account
	
   c) Choose the type of account to add, Choose **Organization**
	
   d) Scan the QR code for dxcmgmt.com
	
   e) Then the user can able to login to console successfully.
	
	
8. Once the user is logged into the GCP console, the mapped project for the user is visible (Example: MS-GCP-Customer-Zero-P-test) and underlying resources (Example: VMs)      are accessible.

	
![Picture3](https://github.dxc.com/storage/user/133938/files/3ee43005-1a55-44b9-b37e-3c2ebdde58f6) 
	

## Do's and Don'ts Instructions
	
 **Do**  
- Once the user is completed their activities in the Customer Zero environment, the user must delete the resources which are created by them.
	
- If any unused resources/instances to be stopped and removed. 
	
- Any support is needed during usage of Customer Zero, the user must contact and get the technical support from GCP CloudOps team by following ITSM process.
	
- User is responsible for Application related activities.
	
- If any logging and alerting rules created for testing purpose, it needs to be deleted once their work is complete. 
	

	
**Do Not** 

- Service account key should not be changed.
	
- Do not create services and instances which are not part of the requirements. 
	
- Do not extend the usage after the timeline is over. 
	
- Do not use the Customer Zero environment for personal use. 

	

	
**Note:**
	
Any resource created in the sandbox will be deleted automatically after 24hours to avoid unnecessary expense. If a resource needs to be running for more than 24hours, please get the resource added to the approved-list in the Customer-Zero-Sandbox repository (https://github.dxc.com/google-cloud-delivery/customer-zero-sandbox)
	


	
	
	
