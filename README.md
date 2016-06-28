# userdbadm
Perl program for managing a userdb database with user names and crypted passwords, as used e. g. by PAM's pam_userdb module.

With userdbadm, such a list can be easily maintained. It takes the database's file name as the first command line argument, then a command (one of list, add, edit and del):

* list
  * List all users in the database
* add <user>
  * Adds <user> to the database. You will prompted for a password.
* edit <user>
  * The the password for <user>. You will prompted for a password.
* del <user>
  * Removes <user> from the database.

This is software is written by Tobias Leupold <tobias.leupold@web.de>, all credits go to him.
