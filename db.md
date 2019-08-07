To back up the Catcher_In_The_Wifi database,
from the path where mysql.exe is located, enter mysqldump -u YOUR_USER_ID -p --databases Catcher_In_The_Wifi > YOUR_PATH_NAME\citw.sql, 
where YOUR_PATH_NAME is the full path to where the citw.sql file should be located,
YOUR_USER_ID is the mysql user you are using to create the file. You will be prompted for the password.
<!-- mysqldump.exe -u root -p --databases catcher_in_the_wifi > c:\Users\theClubhou.se\Desktop\backup.sql -->
-----------------
To restore the Catcher_In_The_Wifi database,
1. download the citw.sql file and 
2. place it in the directory on your workstation where your app files are located.
3. Within the mysql command line, enter source YOUR_PATH_NAME\citw.sql and press enter, where YOUR_PATH_NAME is the full path to the citw.sql file.
4. Once completed, a SHOW DATABASES command should show the Catcher_In_The_Wifi database.
