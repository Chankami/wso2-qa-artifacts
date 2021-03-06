## Read Me for DS200_Test_Script_Super_Tenant

This test script can be used to create different types of dashboards for any user in the super tenant's domain. Two types of dashboards can be created from this script as explained below.

* Multiple Pages Test 
\
This test creates a dashboard with two pages and adds two different gadgets in both pages. Then, the user views the dashboard and browse between the dashboard pages

* Banner Test
\
This test creates a dashboard with a banner layout and adds an image to the banner. The dashboard comprises of USA Map, USA Business Revenue and USA Social Media Usage gadgets all linked through events and also Publisher and Subscriber gadgets linked together.


### Follow the below steps to run the test plan

##### Run the DS200_Test_Script_Super_Tenant.jmx
1. Open Jmeter and navigate to File -> Open and browse the DS200_Test_Script_Super_Tenant.jmx file
2. Configure the user defined variables accordingly. (Descriptions of the variables are given)
3. Also, add the hostname and the port in HTTP Request Defaults.
4. Then, run the required requests by enabling the relavant Controller

You can browse the portal as https://<hostname:port>/portal and verify the dashboard created.

**Note**

 - This script can be used directly for long running tests as the dashboard name is created uniquely. (the counter appends a unique value at the end of each dashboard name)
 - This script cannot be created when SSO feature is enabled
