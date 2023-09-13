To Connect to database , login as an Admin : 
Username: Admin
Password: <enter password for your wallet>
To create the tables and insert the data, please execute the file : 1.Create_Table&Sequence_InsertData
This script when executed will drop the tables if they already exist and create the tables again and insert data. 
If the tables do not exist already, tables will be created.

After successful execution of file 1.Create_Table&Sequence_InsertData please execute the 2.views_creation file for the views for admin.

3. Insert_Update_NewRecord_Procedures_Package file contains all the stored procedures for inserting new record in any table , update procedures and for getting the avg rating of the properties.

Then execute the 4.user_testcases file to execute the various positive and negative test scenarios and check exception handling.

Execute the 5.user_roles_creation file to create various user roles and granting them various access.

Login as Manager with Username : Milan and Password : Northeastern2021
Please execute the emp_manager_role_views to see the views for Manager

Login as Employee with Username : Hal and Password : Northeastern2021
Please execute the emp_Agent_role_views to see the views for Employee

Login as Owner with Username : Marshall and Password : Northeastern2021
Please execute the Owner_role_views to see the views for Owner

Login as Customer with Username : Bernard and Password : Northeastern2021
Please execute the Customer_role_views to see the views for Customer


Execute 6.Indexes file for better search performance

7.Triggers file has the triggers

To see the various reports , please execute 8. Reports
Complain_stats.xml and Salesbyregion.xml are graphical representation of some reports from 8.Reports file. To view these reports, open these files in User Defined Reports section in Oracle SQL Developer
