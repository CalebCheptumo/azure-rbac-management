# Task 2: Review and assign a built-in Azure role

1. az104-mg1 overview
   I navigated to the az104-mg1 management group to start the role assignment process.
   ![az104-mg1 Overview](../screenshots/assign%20az104-mg1%20role/az104-mg1%20overview.png)

2. az104-mg1 IAM overview
   I opened the Access control (IAM) blade to see the current role assignments and available roles.
   ![az104-mg1 IAM Overview](../screenshots/assign%20az104-mg1%20role/az104-mg1%20IAM%20overview.png)

3. az104-mg1 roles overview
   I reviewed the Roles tab to see all available built-in roles for assignment.
   ![az104-mg1 Roles Overview](../screenshots/assign%20az104-mg1%20role/az104-mg1%20roles%20overview.png)

4. Virtual machine contributor role overview
   I examined the Virtual Machine Contributor role to understand what permissions it provides before assigning it.
   ![Virtual Machine Contributor Role Overview](../screenshots/assign%20az104-mg1%20role/virtual%20machine%20contributor%20role%20overview.png)

5. select role az104-mg1
   I clicked Add role assignment to start assigning the Virtual Machine Contributor role.
   ![Select Role az104-mg1](../screenshots/assign%20az104-mg1%20role/select%20role%20az104-mg1.png)

6. Entra ID overview
   I went to Microsoft Entra ID to check if the helpdesk group already existed.
   ![Entra ID Overview](../screenshots/assign%20az104-mg1%20role/Entra%20ID%20overview.png)

7. new group overview
   I created a new security group since the helpdesk group didn't exist yet.
   ![New Group Overview](../screenshots/assign%20az104-mg1%20role/new%20group%20overview.png)

8. add helpdesk group owner
   I configured the role assignment by selecting the helpdesk group and assigning the Virtual Machine Contributor role.
   ![Add Helpdesk Group Owner](../screenshots/assign%20az104-mg1%20role/add%20helpdesk%20group%20owner.png)

9. helpdesk group overview
   I confirmed the helpdesk group was created successfully with the correct settings.
   ![Helpdesk Group Overview](../screenshots/assign%20az104-mg1%20role/helpdesk%20group%20overview.png)

10. az104-mg1 members tab
    I went back to the role assignment and selected the Members tab to add the helpdesk group.
    ![az104-mg1 Members Tab](../screenshots/assign%20az104-mg1%20role/az104-mg1%20members%20tab.png)

11. assign member to az104-mg1
    I searched for and selected the helpdesk group to add it as a member for the role assignment.
    ![Assign Member to az104-mg1](../screenshots/assign%20az104-mg1%20role/assign%20member%20to%20az104-mg1.png)

12. assign helpdesk as member to az104-mg1
    I confirmed the helpdesk group was selected and ready to be assigned the role.
    ![Assign Helpdesk as Member to az104-mg1](../screenshots/assign%20az104-mg1%20role/assign%20helpdesk%20as%20member%20to%20az104-mg1.png)

13. review and assign role az104-mg1
    I reviewed the assignment details and clicked Review + assign to complete the role assignment.
    ![Review and Assign Role az104-mg1](../screenshots/assign%20az104-mg1%20role/review%20and%20assign%20role%20az104-mg1.png)

14. az104-mg1 IAM group added
    I verified the assignment was successful by checking that the helpdesk group now has the Virtual Machine Contributor role.
    ![az104-mg1 IAM Group Added](../screenshots/assign%20az104-mg1%20role/az104-mg1%20IAM%20group%20added.png)
