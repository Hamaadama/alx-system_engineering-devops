# Shell Redirection Scripts

This repository contains a collection of basic shell scripts focused on various tasks related to shell redirections. Each script demonstrates the utilization of shell features for effective text manipulation. Below is an overview of each script:

## Scripts:

1. **0-hello_world:**
   - Prints "Hello, World" followed by a new line to the standard output.

2. **1-confused_smiley:**
   - Displays a confused smiley "(Ôo)'.

3. **2-hellofile:**
   - Displays the content of the /etc/passwd file.

4. **3-twofiles:**
   - Displays the content of /etc/passwd and /etc/hosts.

5. **4-lastlines:**
   - Displays the last 10 lines of /etc/passwd.

6. **5-firstlines:**
   - Displays the first 10 lines of /etc/passwd.

7. **6-third_line:**
   - Displays the third line of the file iacta.

8. **7-file:**
   - Creates a file named \*\\'"Best School"\'\\*$\?\*\*\*\*\*:), containing the text Best School ending with a new line.

9. **8-cwd_state:**
   - Writes the result of the command `ls -la` into the file ls_cwd_content. Overwrites the file if it already exists; creates it if it does not.

10. **9-duplicate_last_line:**
    - Duplicates the last line of the file iacta.

11. **10-no_more_js:**
    - Deletes all regular files (not directories) with a .js extension in the current directory and its subfolders.

12. **11-directories:**
    - Counts the number of directories and sub-directories in the current directory.

13. **12-newest_files:**
    - Displays the 10 newest files in the current directory.

14. **13-unique:**
    - Takes a list of words as input and prints only words that appear exactly once.

15. **14-findthatword:**
    - Displays lines containing the pattern "root" from the file /etc/passwd.

16. **15-countthatword:**
    - Displays the number of lines containing the pattern "bin" in the file /etc/passwd.

17. **16-whatsnext:**
    - Displays lines containing the pattern "root" and the 3 lines after them in the file /etc/passwd.

18. **17-hidethisword:**
    - Displays all lines in the file /etc/passwd that do not contain the pattern "bin".

19. **18-letteronly:**
    - Displays all lines of the file /etc/ssh/sshd_config starting with a letter.

20. **19-AZ:**
    - Replaces all occurrences of characters A and c from the input with Z and e, respectively.

21. **20-hiago:**
    - Removes all occurrences of letters c and C from the input.

22. **21-reverse:**
    - Reverses its input.

23. **22-users_and_homes:**
    - Displays all users and their home directories, sorted by users.

## Additional Commands:

- **100-empty_casks:**
    - Finds all empty files and directories in the current directory and all sub-directories.

- **101-gifs:**
    - Lists all files with a .gif extension in the current directory and all its sub-directories.

- **102-acrostic:**
    - Decodes acrostics that use the first letter of each line.

- **103-the_biggest_fan:**
    - Parses web server logs in TSV format as input and displays the top 11 hosts or IP addresses with the most requests.
