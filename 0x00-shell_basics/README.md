# Shell Script Collection

This repository contains a set of shell scripts designed to perform various tasks efficiently. Below is a brief overview of each script:

## Scripts:

1. **0-current_working_directory:**
   - Prints the absolute path name of the current working directory.

2. **1-listit:**
   - Displays the contents list of your current directory.

3. **2-bring_me_home:**
   - Changes the working directory to the user's home directory.

4. **3-listfiles:**
   - Displays current directory contents in a long format.

5. **4-listmorefiles:**
   - Displays current directory contents, including hidden files (starting with .) in the long format.

6. **5-listfilesdigitonly:**
   - Displays current directory contents in the long format with user and group IDs displayed numerically, including hidden files.

7. **6-firstdirectory:**
   - Creates a directory named my_first_directory in the /tmp/ directory.

8. **7-movethatfile:**
   - Moves the file betty from /tmp/ to /tmp/my_first_directory.

9. **8-firstdelete:**
   - Deletes the file betty.

10. **9-firstdirdeletion:**
    - Deletes the directory my_first_directory in the /tmp directory.

11. **10-back:**
    - Changes the working directory to the previous one.

12. **11-lists:**
    - Lists all files (including hidden ones) in the current directory, the parent of the working directory, and the /boot directory in long format.

13. **12-file_type:**
    - Prints the type of file named iamafile, which will be in the /tmp directory when running the script.

14. **13-symbolic_link:**
    - Creates a symbolic link to /bin/ls, named __ls__, in the current working directory.

15. **14-copy_html:**
    - Copies HTML files from the current working directory to the parent directory, only copying newer files or those that do not exist in the parent directory.

16. **100-lets_move:**
    - Moves all files beginning with an uppercase letter to the directory /tmp/u.

17. **101-clean_emacs:**
    - Deletes all files in the current working directory that end with the character ~.

18. **102-tree:**
    - Creates the directories welcome/, welcome/to/, and welcome/to/school in the current directory.

19. **103-commas:**
    - Lists all files and directories of the current directory, separated by commas.

## Additional Files:

- **school.mgc:**
    - A magic file (school.mgc) for use with the `file` command to detect School data files. School data files always contain the string SCHOOL at offset 0.
