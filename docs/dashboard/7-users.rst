Users
=====
The FLOW dashboard is a place where lots of things happen: surveys get created, edited and distributed, incoming data is edited, cleaned and exported, new users are added and deleted. As Akvo FLOW is a tool meant to be used by organisations, it is important that means exist to restrict who can do what. Users, roles and permissions keep this order on the dashboard. 

You can define any number of users on the FLOW dashboard. Roles and Permissions describe the different levels access a user has on the Akvo FLOW dashboard. Access can be restricted either by activity, such as creating or editing a survey, making a report, or deleting data, or by survey or folder of surveys. A set of user permissions is called a 'role'. Roles can be changed and customised, in order to fit the workflow of a particular organisation. 

In the user tab, the dashboard user subtab displays the user name, email address, and roles for all users. In addition, it shows whether this user has an API key (please refer to :doc:`../api` for more information), and the actions 'edit' and 'delete'.

 .. figure:: img/7-users_main.png
   :width: 1000 px
   :alt: image of dashboard
   :align: center 

   The users list.


Adding and editing a user
--------------------------
To add a user, click on the 'Add new user' button. In the screen shown, provide a user name and an email address. The email address needs to be connected to a Google account, as the user needs to authenticate with google before he/she can log in. 

You can give user an administrator role by checking the checkbox. Administrators are given full permissions on all survey folders. Only administrators can manage users and their roles.

Click 'Save user info' to save the new user. A new user who doesn't have the 'administrator' role starts without any roles, so those need to be added separately in the next step.

 .. figure:: img/7-user_new.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

The user information for an existing user can be edited by clicking the 'edit' action in the user list.

 .. figure:: img/7-user_edit.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 


Adding roles to a user
-----------------------
A new user who doesn't have the 'administrator' role starts without any roles. To add roles to an existing user, click 'edit' in the list, as shown in the image above. Below the user information, there is a section Roles and Permissions.

 .. figure:: img/7-users_roles_area.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

To add a role, first select a role from the dropdown list. Second, select the folder or survey to which you want to apply this role. When you select a specific folder you can continue to select subfolders. Alternatively, you can simply select 'All folders'. In the image below, we have given the user the role 'editor' in the folder 'Burundi'. This means that the user has the permissions that go with the role 'editor' in all surveys and subfolders in the folder 'Burundi'.

 .. figure:: img/7-users_burundi_role.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   The user now has editor role in the /burundi folder

Editing roles and permissions
-----------------------------
To change the permissions for an existing role, or to create entirely new custom roles, go to the 'Roles and permissions' subtab.

 .. figure:: img/7-users_roles_subtab.png
   :width: 750 px
   :alt: image of dashboard
   :align: center 

   The roles and permissions subtab.

To edit an existing role, click 'edit' in the list. This will display a list of permissions associated to this role. The checkboxes indicate which permissions this role has. You can also edit the name of the role here. When you are done, click 'Save permission set' to save.

 .. figure:: img/7-users_edit_perms.png
   :width: 500 px
   :alt: image of dashboard
   :align: center 

To create a new role, click 'Add new role' in the roles list. You can provide a name for the role, and select the permissions you want to include.

Effect of roles
---------------
If a user doesn't have permissions to do something, the relevant icons or items will simply not be displayed.
