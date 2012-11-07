Users
================

Overall Requirements
----------------------------
	* All dashboard users can view current users and their permission levels
	* Only Organisation administrators can see [+ Add New Users] button or Action column
	* Given appropriate permissions, current users can add new users and set their permission levels, edit permission levels of existing users, and delete users.
	* Users should only see the elements that they have permission to interact with according to their permission level.
	* The default user level should be User.
	* Akvo staff level users (Super Users) should be hidden on the user listing on all pages other than flowakvo.


Detailed Requirements
--------------------------------
	* **Deleting Users** - Given appropriate permissions, a user cannot delete another user without a warning message.
	* **Email address entry field** - should validate email address format, and for now only gmail addresses are allowed, since they are required for user log-in. Only @gmail.com and @googlemail.com are accepted.
	* **Username entry field** - should limit users to entering letters and numbers in the ISO basic Latin Alphabet (http://en.wikipedia.org/wiki/ISO_basic_Latin_alphabet), with no spaces, tabs or special characters. Username should be case-insensitive. Character limit for username should be XXX.

Permission Level Details
-----------------------------
	* User
	* Project Editor
	* Administrator
	* Super User (Akvo staff only)

These levels are matched with `RSR permission levels <http://rsrhelp.akvo.org/kb/getting-started/user-accounts-and-rights>`_

`More detailed permission role descriptions <https://docs.google.com/document/d/16bCHzJ6Lyi4YmULZ5dG3hHoYxdWVLZkj4rUvEc_7__M/edit>`_ (can view with Akvo permission only)


Mock-up(s)
---------------------
users_home.bmml

LAST UPDATE : 7 November 2012 cmo