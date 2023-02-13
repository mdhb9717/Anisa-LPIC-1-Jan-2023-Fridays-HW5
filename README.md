# Anisa-LPIC-1-Jan-2023-Fridays-HW5

## MohammadALi Heidari-LPIC1-Fridays-HW4

## Task 1: What's the meaning of dot`.` and plus`+` after permission

`.` character indicates a file with an SELinux security context, but no other alternate access method.

A file with any other combination of alternate access methods is marked with a `+` character. `+` suffix indicates an access control list that can control additional permissions.

## Task2: `yum history` `rollback?`/`redo?`/`undo?`

+ **`yum history rollback ID_NUMBER`:**
This command has more versatility than the “undo” option has available. The rollback option essentially allows us to completely revert all of the updates that have taken place, back to a specific ID number.

+ **`yum history redo ID_NUMBER`:**
we can use the “yum redo” command to redo the specific transaction that you did in the past. It's useful to reinstall something's older version or exact version the at you installed in the past.

+ **`yum history undo ID_NUMBER`:**
Much like the rollback command noted above, we are going to expand on the last transaction and demonstrate how the “history undo” command functions. To undo an operation, we need to run the “yum history undo” command with the specific “ID” number of the transaction that you want to revert back to. 
