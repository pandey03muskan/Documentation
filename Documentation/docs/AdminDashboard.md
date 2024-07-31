---
title: "Admin Dashboard"
description: "This will guide to about Admin settings of the apps on  the Initializ Console."
sidebar_position: 8
---

# Admin Dashboard

## All About Admin Settings

 Admin dashboard allows the admin to invite new users to the organization and also manage the existing users.

- ### Accessing the Dashboard

   You can access the Admin Dashboard by selecting the "Settings" option in the left sidebar of the Initializ.ai console. Only admin can access the Admin Dashboard. The user who initially creates the organization will be designated as the initial admin.

   Admin can invite new users for the roles of admin, workspace-admin, developer and all the invited admin will have the same privileges as the initial admin.

   ![Compliance_scan](/assets/admin_dashboard/AccessDashboard.png)
   \*\* _Snippet of accessing the admin dashboard_.

- ### Inviting the user to the organization
   
   To invite the user in the organization, open the settings and click on the option of "Add New User".

    ![Compliance_scan](/assets/admin_dashboard/add_user.png)
    \*\* _Snippet of inviting the user to the organization_.

    There are two possible scenarios
    #### 1. User is already registered to the initializ.ai 
    In this instance, you need to enter the user's email address, select their role, and choose the specific workspace to which you wish to invite the user. The username will be automatically retrieved from the user's account.

    ![Compliance_scan](/assets/admin_dashboard/registered_user.png)
     \*\* _Snippet of inviting the user(already registered to initializ.ai) to the organization_.

    After clicking "Save," the user is successfully invited to the organization. 

    #### 2. User is not registered to the initializ.ai 
    In this instance, you need to enter the user's email address, select their role, enter the username and choose the specific workspace to which you wish to invite the user.

    ![Compliance_scan](/assets/admin_dashboard/not_registered_user.png)
     \*\* _Snippet of inviting the user(not registered to initializ.ai) to the organization_.

    After clicking "Save," the user is successfully invited to the organization and user will receive two email - 
    1. To verify their email address.
    2. To Reset the password.


    After verifying their email and resetting the password, the user will be able to log in to the specific organization in Initializ.ai.

- ### Update the User
    To update a user, follow these steps:

    - Open the Settings section you will get the list of existing users.
    - Click on the three dots next to the user you wish to update.

    ![Compliance_scan](/assets/admin_dashboard/user_edit_threeDot.png)
    \*\* _Snippet of edit the user_.

    - Select "Edit" from the menu.

    ![Compliance_scan](/assets/admin_dashboard/user_edit.png)
    \*\* _Snippet of inviting the user(not registered to initializ.ai) to the organization_.


    - Admin can update only the user’s role and workspace.

    ![Compliance_scan](/assets/admin_dashboard/edit_user_info.png)
     \*\* _Snippet of inviting the user(not registered to initializ.ai) to the organization_.


    - After making the necessary changes, click "Save."

    ![Compliance_scan](/assets/admin_dashboard/edit_user_info_save.png)
     \*\* _Snippet of inviting the user(not registered to initializ.ai) to the organization_.

    After clicking "Save," the changes will be applied successfully.

- ### Remove user from the organization
    
    To remove the user, follow these steps:

    - Open the Settings section you will get the list of existing users.
    - Click on the three dots next to the user you wish to delete.
     
    ![Compliance_scan](/assets/admin_dashboard/user_edit_threeDot.png)
    \*\* _Snippet of delete the user_.

    - Select "Delete" from the menu

    ![Compliance_scan](/assets/admin_dashboard/user_delete.png)
    \*\* _Snippet of delete the user_.

    - click on "Yes".

    ![Compliance_scan](/assets/admin_dashboard/delete_user_org.png)
    \*\*_Snippet of delete the user_.

    After clicking "Yes", the user will be successfully removed from the organization.



:::note
- An **admin** will not be able to edit or remove to himself.
- One admin can edit or remove to another admin.
:::