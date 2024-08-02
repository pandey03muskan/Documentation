---
title: "Admin Dashboard"
description: ""
sidebar_position: 8
---

# Admin Dashboard

## All About Admin Settings

   The admin dashboard allows the admin to invite new users to the organization and manage existing users.

- ### Accessing the Dashboard

   You can access the Admin Dashboard by selecting the "Settings" option in the left sidebar of the Initializ.ai console. Only the admin can access the Admin Dashboard. The user who initially creates the organization will be designated as the initial admin.

   An admin can invite new users for the roles of admin, workspace-admin, or developer, and all invited admins will have the same privileges as the initial admin.

   ![Compliance_scan](/assets/admin_dashboard/AccessDashboard.png)
   \*\* _Snippet of accessing the admin dashboard_.

- ### Inviting the user to the organization
   
   To invite the user to the organization, open the settings and click on the option of "Add New User".

    ![Compliance_scan](/assets/admin_dashboard/add_user.png)
    \*\* _Snippet for inviting a user to the organization_.

    There are two possible scenarios
    #### 1. The user is already registered with Initializ.ai
    In this instance, you need to enter the user's email address, select their role, and choose the specific workspace to which you wish to invite them. The username will be automatically retrieved from the user's account.

    ![Compliance_scan](/assets/admin_dashboard/registered_user.png)
     \*\* _Snippet for inviting a user (already registered with Initializ.ai) to the organization_.

    After clicking 'Save,' the user will be successfully invited to the organization. 

    #### 2. The user is not registered with initializ.ai 
    In this instance, you need to enter the user's email address, select their role, enter their username, and choose the specific workspace to which you wish to invite them.

    ![Compliance_scan](/assets/admin_dashboard/not_registered_user.png)
     \*\* _Snippet for inviting a user (not registered with Initializ.ai) to the organization_.

    After clicking "Save," the user will be successfully invited to the organization and the user will receive two emails -
    1. To verify their email address.
    2. To Reset the password.


    After verifying their email and resetting their password, the user will be able to log in to the specific organization in Initializ.ai.

- ### Update the User
    To update a user, follow these steps:

    - Open the Settings section, and you will see the list of existing users.
    - Click the three dots next to the user you wish to update.

    ![Compliance_scan](/assets/admin_dashboard/user_edit_threeDot.png)
    \*\* _Snippet for editing the user_.

    - Select "Edit" from the menu.

    ![Compliance_scan](/assets/admin_dashboard/user_edit.png)

    - The admin can update only the user’s role and workspace.

    ![Compliance_scan](/assets/admin_dashboard/edit_user_info.png)

    - After making the necessary changes, click "Save".

    ![Compliance_scan](/assets/admin_dashboard/edit_user_info_save.png)

    After clicking "Save," the changes will be applied successfully.

- ### Remove the user from the organization
    
    To remove the user, follow these steps:

    - Open the Settings section, you will get the list of existing users.
    - Click on the three dots next to the user you wish to delete.
     
    ![Compliance_scan](/assets/admin_dashboard/user_edit_threeDot.png)
    \*\* _Snippet for deleting the user_.

    - Select "Delete" from the menu.

    ![Compliance_scan](/assets/admin_dashboard/user_delete.png)
   

    - Click on "Yes".

    ![Compliance_scan](/assets/admin_dashboard/delete_user_org.png)


    After clicking "Yes", the user will be successfully removed from the organization.



:::note
- An **admin** will not be able to edit or remove to himself.
- One admin can edit or remove another admin.
:::