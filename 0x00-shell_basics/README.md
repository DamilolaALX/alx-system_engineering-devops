Shell Basics - Script Descriptions

This directory contains a collection of shell scripts that perform various tasks related to navigating the filesystem and working with files and directories. Below is a description of each script:

0-current_working_directory.sh
Description: This script prints the absolute path name of the current working directory.

1-listit.sh
Description: This script displays the contents list of the current directory.

2-bring_me_home.sh
Description: This script changes the working directory to the user's home directory.

3-listfiles.sh
Description: This script displays the current directory contents in long format.

4-listmorefiles.sh
Description: This script displays the current directory contents, including hidden files, in long format.

5-listfilesdigitonly.sh
Description: This script displays the current directory contents in long format with user and group IDs displayed numerically, including hidden files.

6-firstdirectory.sh
Description: This script creates a directory named "my_first_directory" in the /tmp/ directory.

7-movethatfile.sh
Description: This script moves the file "betty" from /tmp/ to /tmp/my_first_directory.

8-firstdelete.sh
Description: This script deletes the file "betty" located in /tmp/my_first_directory.

9-firstdirdeletion.sh
Description: This script deletes the directory "my_first_directory" from the /tmp directory.

10-back.sh
Description: This script changes the working directory to the previous one.

11-lists.sh
Description: This script lists all files in the current directory, the parent of the working directory, and the /boot directory in long format.

12-file_type.sh
Description: This script prints the type of the file named "iamafile" in the /tmp directory.

13-symbolic_link.sh
Description: This script creates a symbolic link to /bin/ls named "ls" in the current working directory.

14-copy_html.sh
Description: This script copies all HTML files from the current working directory to the parent of the working directory if they do not exist or are newer than the versions in the parent directory.