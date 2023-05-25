# LAB 1 : Enabling the VM's RDP access over HTTPS
## Lab Overview
This lab creates an virtual machine which will be able to establish an RDP connection to VM over https. Bascically there will be an **Go to VM Name** button is available in the bottom of the environment or under the resources tab you will find the **Lauch VM in Browser**
## Excersie 1 
This Task is About creating an RDP connection over HTTPS for an ODL that creates an VM. Below are the following details for achieving the task : 
1. Login to **cloudlabs.admin.ai** using the credentials.
2. Go to the **Templates** section within the portal of the cloud labs.
3. Click on the **Add Template** button to create a new template 
4. Provide a name to your template select the resource provider as the Azure then give an name to the code section which will act an internal identifier and this will be concatenated with the Resource group if you have not enable the **Custon RG name**
5. Next, Select the **Subscription** to the shared and then provide an description about the lab which will be displayed in the registration page. Provided an description about the lauch page which will be visible once the lab is lauched.
6. Provided an Custom name to the registration page title. Spektra mail Id was given as the name of the owner for the template, The deployment plan was set to **Single resource group** hence only one RG will be created for the Lab under which the resources are deployed.
7. Then a region for the resource deployment is selected. Under the **Control Panel Resources** we can enable the Virtual Machine in order to make it see it's setting in the control panel.
8. Enabled the Customn RG Name in order to customize the name of the resource group created. Checked the box which contained **Enable VM access over Http**.
9. **Show Resource Tab** was enabled to view the resources created. Clic on **Submit**.
10. Then Under **ARM Template** click on add you will be able to see the resource group name and provide an custom name to your RG. Provide the Storage account URl of the arm template an the parameter file.
11. Under the **Template Permission** Select the permission type as Azure-built-in-role and Select the profile type to attendee and select the permission to contributor check for the scope level and set it to the RG.
12. under the Virtual machine configuaration provide the actual name of your VM and set the tyoe to RDP. The provide the name given to the output parameter which contains server password, server username, server DNS.
13. Come to the **On demand Labs** part an then click on add lab. 
14. Provide an name to the ODL and choose the **Template** to the one that was created earlier.
15. Most of the fields will be updated as those information will be present in the template prior.
16. Set the **Status** of the ODL to the Registration open in order to take in the Registrartion.
17. Provide the **Approval** to registration required which enable the registration page and you will be able to register for the lab.
18. Set the **Duration** of the lab to the time that is required this specifies when will the lab expires. Then, provide an **Uptime** which will be for the VM uptime.
19. Select the **Expiry date** of the ODL to the date required. 
20. Type in the maximum number of users that can register for the users. 
21. Select the **ACI Deployment style** to Default through which we will be able to access the VM RDP over HTTPS.
22. Then you can tick the check box Allow users to delete ODL where we will be able to delete the ODL. Enable the Enable Resource Operation where we can start, stop, deallocate and lanuch the VM to browser. 
23. Check the box that is **Test** so that the lab is not considered in the reports.    
24. Select the default language to English. Then Click on Submit.
25. Then under the ODL created you will be able to see the ODL you have created copy the bit.ly URL and paste it in the browser. 
26. The Register for the Even tby providing the name,last name, Email, then the country and organisation then click on the submit.
27. You will be redirected to the launch lab page click on **Launch Lab** you will initiate  an lab deployment of the resources in the ARM template.
28. Then you will be able to acces the VM through the browser. 
