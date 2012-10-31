Users
================

Requirements
---------------------
	* All dashboard users can view current users and their permission levels, but only Organisation administrators can see [+ Add New Users] button or Action column
	* Given appropriate permissions, current users can add new users and set their permission levels, edit permission levels of existing users, and delete users.
	* Given appropriate permissions, a user cannot delete another user without a warning message.
	* Users should only see the elements that they have permission to interact with according to their permission level.
	* The default user level should be User.
	* Akvo staff level users (Super Users) should be hidden on the user listing on all pages other than flowakvo.
	* Email address entry field should be formatted to receive valid email address formats, and for now only gmail addresses, since they are required for user log-in
	* Username entry field should limit users to entering text and numbers, with no spaces, tabs or special characters

Permission Level Details
-----------------------------
	* User
	* Project Editor
	* Organisation Administrator
	* Super User (Akvo staff only)

These levels are matched with RSR permission levels, http://rsrhelp.akvo.org/kb/getting-started/user-accounts-and-rights

More detailed permission role descriptions are coming soon (from CMO)

Mock-up(s)
---------------------
users_home.bmml