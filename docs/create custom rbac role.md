# Task 3: Create a custom RBAC role

1. az104-mg1 overview
   I navigated back to the az104-mg1 management group to start creating a custom role.
   ![az104-mg1 Overview](../screenshots/custom%20RBAC%20role/az104-mg1%20overview.png)

2. az104-mg1 IAM overview
   I opened the Access control (IAM) blade to access the custom role creation options.
   ![az104-mg1 IAM Overview](../screenshots/custom%20RBAC%20role/az104-mg1%20IAM%20overview.png)

3. create custom role basic
   I clicked Add custom role and filled in the Basics tab with the role name and description.
   ![Create Custom Role Basic](../screenshots/custom%20RBAC%20role/create%20custom%20role%20basic.png)

4. microsoft support exclude permission
   I selected "Clone a role" and chose Support Request Contributor as the baseline to customize.
   ![Microsoft Support Exclude Permission](../screenshots/custom%20RBAC%20role/microsoft%20support%20exclude%20permission.png)

5. select other registers support resource provider permission
   I went to the Permissions tab and searched for Microsoft.Support to find the permission to exclude.
   ![Select Other Registers Support Resource Provider Permission](../screenshots/custom%20RBAC%20role/select%20other%20registers%20support%20resource%20provider%20permission.png)

6. add other registers support resource provider permission
   I added "Registers Support Resource Provider" to the NotActions list to remove this permission from the role.
   ![Add Other Registers Support Resource Provider Permission](../screenshots/custom%20RBAC%20role/add%20other%20registers%20support%20resource%20provider%20permission.png)

7. JSON custom role
   I reviewed the JSON definition to see the original role structure before the permission exclusion.
   ![JSON Custom Role](../screenshots/custom%20RBAC%20role/JSON%20custom%20role.png)

8. JSON custom role with excluded permission
   I verified the JSON now shows the excluded permission in the NotActions section as intended.
   ![JSON Custom Role with Excluded Permission](../screenshots/custom%20RBAC%20role/JSON%20custom%20role%20with%20excluded%20permission.png)

9. review and create new custom role
   I reviewed all the configuration details and clicked Create to finalize the custom role.
   ![Review and Create New Custom Role](../screenshots/custom%20RBAC%20role/review%20and%20create%20new%20custom%20role.png)

10. custom role successfully created
    I confirmed the custom role was created successfully and is ready for assignment.
    ![Custom Role Successfully Created](../screenshots/custom%20RBAC%20role/custom%20role%20successfully%20created.png)
