# Access Lifecycle Management
## Customer Zero - GCP
##### Version 1.3




## 1. Summary 
   This document describes varies level of access to be maintained for the Customer Zero – GCP environment throughout the life cycle of this project.
   


## 2. Objective 
   The Objective of this document is to manage the access request, credentials required for varies tools and services for the Customer Zero Landing zone. This should be followed by GCP Professional Services and CloudOps throughout the Customer Zero GCP project life cycle.
   
 
 
## 3. Access Request for GCP Delivery team / CloudOps team to deploy and manage the Customer Zero environmnent

  ### 3.1 Request Organization Level Infrasec Access
     
   •	Organization level Infrasec teams are needed for the Onboarding. Below are the Infrasec teams should be requested by the user via Infrasec portal (https://infrasec.svcs.entsvcs.net)
   
   •	For detail access procedure refer the Onboarding document **GCP Customer Zero Onboarding Guide v1.2.docx** and section 4.2.
   
   
   | Sl.no | Infrasec teams | Description |
   | --- | --- | --- |
   | 1. | GCP-DXC-ORGLEVEL-Developers | Project Deployer access on GCP organization |
   | 2. | GCP-DXC-ORGLEVEL-NetworkAdmins | Shared VPC admin and VCPS (Access Context Manager Admin) |
   | 3. | GCP-DXC-ORGLEVEL-OrgViewer | GCP Organization viewer |
   | 4. | GCP-DXC-ORGLEVEL-SupportAdmin | Support ticket to Google creator |
   | 5. | GCP-DXC-ORGLEVEL-DevOps | Project owner access on GCP organization |
   
    
   ### 3.2 Revoking Organization Level Infrasec Access
   
   • Create a Jira ticket and assign the same with CPS Engineering team so that they will Revoke the access for the user.
   
   
   ### 3.3 Manage Project Level Infrasec Access
   
   •	The following Infrasec team and functional groups are created for Customer Zero GCP landing zone. It should be maintained, if any additional requirement of Infrasec    team to be accommodated and documented by the CloudOps team.
   
   
 ![MicrosoftTeams-image (3)](https://github.dxc.com/storage/user/133938/files/3296cdef-32ae-4589-a4da-e7e7f49521dd) 
 ![MicrosoftTeams-image (4)](https://github.dxc.com/storage/user/133938/files/3efdb8a4-080e-4af8-bb01-556c5d220034)
 ![MicrosoftTeams-image (5)](https://github.dxc.com/storage/user/133938/files/df075dcc-8048-4423-9a7a-6257f21cd8f1)
 ![MicrosoftTeams-image (6)](https://github.dxc.com/storage/user/133938/files/70c1159f-9400-46eb-ac82-5029a578409e)
 
    
   ### 3.4 Request Shared Service Portal Access
   
   •	Users need to request the below Infrasec teams to access the Shared Service portal in the Infrasec portal (https://infrasec.svcs.entsvcs.net)
   
   •	For detail access procedure refer the Onboarding document **GCP Customer Zero Onboarding Guide v1.2.docx** and section 4.5.
   
   
   | Sl.no | Infrasec Teams | Description |
   | --- | --- | --- |
   | 1. | CPS-SS-dev-GCP | This team is needed to access CPS shared service portal development environment |
   | 2. | CPS-SS-PROD-GCP | This team is needed to access CPS shared service portal production environment |
   
   
   **DEV SSP:** (https://cps-sharedsvcs-dev.paas4sap.svcs.entsvcs.com/ui/management/login/system)
   
   **PROD SSP:** (https://cps-sharedsvcs.paas4sap.svcs.entsvcs.com/ui/management/login/system)
 


## 4. Revoking the shared service portal access for GCP professional services and Cloudops team.
•	Create a Jira ticket and assign the same with CPS Engineering team so that the access is Revoked for user

   ### 4.1. Customer Access for SSP

   • Customer access is created through Shared Service Portal in the user section of Prod SSP URL mentioned above.  GCP Professional Services and CloudOps team must maintain the records of the users which are created in the SSP.
   
   ### 4.2. Revoke Customer Access for SSP

   • Customer access is deleted through Shared Service Portal in the user section of Prod SSP URL mentioned above.  GCP Professional Services and CloudOps team must maintain the records of the users which are deleted in the SSP.

   ### 4.3. Service Account for SSP

   While we publish the customer in the SSP portal, service account is needed so it needs to be created by the GCP Professional Services Team and managed by the CloudOps team.



## 5. Request Access to AWX Portal

   ### 5.1. Request Access for AWX Portal

   • Create a JIRA ticket for AWX portal access and assign to CPS Engineering team (Moravcik, Alexander alexander.moravcik@dxc.com).
   
   • Users can be able to Login into AWX portal  https://35.224.183.92/ using the provided access credentials in the email.
   
   • For detail access procedure refer the Onboarding document **GCP Customer Zero Onboarding Guide v1.2.docx** and section 4.6.
   

   ### 5.2. Revoking AWX Portal Access

   • Create a Jira ticket and assign the same with CPS Engineering team (Moravcik, Alexander alexander.moravcik@dxc.com) so that the access is Revoked for user.



## 6.	Request Data-Studio Dashboard Access

   ### 6.1. Request Data-Studio Access

   • Create a Jira ticket and assign the same with CPS Engineering team(Arumugham, Bharath Swaminathan barumugham@dxc.com) to view the reports in the DataStudio dashboards
   
   • For detail access procedure refer the Onboarding document **GCP Customer Zero Onboarding Guide v1.2.docx** and section 4.9.
   

   ### 6.2. Revoking the Data studio Access

   • Create a Jira ticket/Send an Email and assign the same to CPS Engineering team (Arumugham, Bharath Swaminathan barumugham@dxc.com) so that the access is revoked for user.
   


## 7. CrowdStrike Access and Revoke procedure

   ### 7.1 To Request CrowdStrike Portal Access
   
   •	Send an email along with CID number to the CrowdStrike team(support@crowdstrike.com) and requesting them to provide the CrowdStrike Portal access based on the required role.
   
   •	After the 2FA is setup is done, the user can be able to login to the CrowdStrike Dashboard, using the below link. https://falcon.us-2.crowdstrike.com/activity/
   
   •	For detail access procedure refer the Onboarding document GCP Customer Zero Onboarding Guide v1.2.docx and section 4.6.

   ### 7.2 Revoking CrowdStrike Portal Access
   
   Send an Email to Falcon Administrators or support team(support@crowdstrike.com) so that the access is revoked for the user.



## 8. Servicenow Access Request Procedure for Development and Production environment

   ### 8.1 Procedure to request Development Service Now and Production ServiceNow Access
   
   •	Users need to request for the ServiceNow development access by filling the details in the below link.
   
   [Develpoment ServiceNow URL](https://csc.service-now.com/sp?id=sc_cat_item&sys_id=50a9889ddbd6b384ccd8a5db0b961922)
   
   [Production ServiceNow URL](https://csc.service-now.com/sp?id=sc_cat_item&sys_id=d17850d1dbc38450ccd8a5db0b9619c2)
   
   ### 8.2.	Procedure to remove the Development Service Now and Production ServiceNow Access
   
   •	Users need to request for the ServiceNow development access by filling the details in the below link.
   
   [Development ServiceNow URL](https://csc.service-now.com/sp?id=sc_cat_item&sys_id=50a9889ddbd6b384ccd8a5db0b961922)
   
   [Production ServiceNow URL](https://csc.service-now.com/sp?id=sc_cat_item&sys_id=d17850d1dbc38450ccd8a5db0b9619c2)
   
 
 
## 9. Procedure for the User to get access for GCP Customer Zero environment using Infrasec

   ### 9.1 Request Team Membership for the user
   
   • Users need to request the required Infrasec team to access the GCP console in the Infrasec portal (Team names should be provided by the Customer Zero project team) 
   
   • Below is the example of Infrasec team to access the PROD project with the read-only access in the GCP Console (https://console.cloud.google.com).
   
   • For detail access procedure refer the Onboarding document **GCP Customer Zero Onboarding Guide v1.2.docx**
   
   | Infrasec Team Name | Infrasec Function Group Name |
   | --- | --- |
   | Example: GCP-CZE-PROD-ReadOnlyUsers | dxc-ms-gcp-g-cze-prod-projectviewer |
   |                                     | dxc-ms-gcp-g-cze-prod-monitorviewer |
   |                                     | dxc-ms-gcp-g-cze-prod-logsexplorer |
   
   
   ### 9.2 Revoking the Team membership Access
   
   • The Infrasec teams which are assigned to user will be deleted by the Team owner.  Please refer the “Customer Zero Access Procedure” document for the Infrasec Team to be deleted. This document is shared with the user while requesting project access.  
   
   • To delete the IAM mapping for the functional groups which are created for the assigned project. Create a Jira ticket and assign the same to CPS Engineering team (Kotlarik, Pavol pavol.kotlarik@dxc.com). 
   
   • Provide the required details like project id, project name, folder id and the functional group/team. 
   
   • The CPS team (Pavol) will delete the required functional group mapping in the console. 


   
   
      
      
   
   



   
   

 
      




