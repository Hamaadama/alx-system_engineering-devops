# Shell Permissions Scripts

This repository includes a set of shell scripts designed to manage file and directory permissions effectively. Each script performs specific tasks related to user, group, and other permissions. Below is an overview of each script:

## Scripts:

1. **0-iam_betty:**
   - Switches the current user to the user betty.

2. **1-who_am_i:**
   - Prints the effective username of the current user.

3. **2-groups:**
   - Prints all the groups the current user is part of.

4. **3-new_owner:**
   - Changes the owner of the file hello to the user betty.

5. **4-empty:**
   - Creates an empty file called hello.

6. **5-execute:**
   - Adds execute permission to the owner of the file hello.

7. **6-multiple_permissions:**
   - Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

8. **7-everybody:**
   - Adds execution permission to the owner, the group owner, and other users for the file hello.

9. **8-James_Bond:**
   - Sets permissions for the file hello as follows: Owner - no permission, Group - no permission, Other users - all permissions.

10. **9-John_Doe:**
    - Sets the mode of the file hello to -rwxr-x-wx.

11. **10-mirror_permissions:**
    - Sets the mode of the file hello the same as olleh’s mode.

12. **11-directories_permissions:**
    - Adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.

13. **12-directory_permissions:**
    - Creates a directory called my_dir with permissions 751 in the working directory.

14. **13-change_group:**
    - Changes the group owner to school for the file hello.

15. **100-change_owner_and_group:**
    - Changes the owner to vincent and the group owner to staff for all files and directories in the working directory.

16. **101-symbolic_link_permissions:**
    - Changes the owner and the group owner of _hello to vincent and staff, respectively.

17. **102-if_only:**
    - Changes the owner of the file hello to betty only if it is owned by the user guillaume.

18. **103-Star_Wars:**
    - Plays the StarWars IV episode in the terminal.

Feel free to customize it further based on your preferences and any additional details you'd like to include.
