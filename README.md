# LinuxUpskillChallenge
This is a challenge to improve my Linux skills by completing sysadmin tasks.
This challenge is comprised of 21 'days' of tasks, for users to complete in their own time, as a way to 
expand their knowledge working with Linux servers.
This is aimed for people that aspire to get Linux-related jobs in industry.

So far in this challenge i have completed 11 Days.

To help prepare for this challenge i turned an old laptop into an ubuntu Linux lab to act as my remote server.
I then edited the Netplan config file to ensure the laptop was using a static ip for easier SSH access.

For each day i will create and link a notion dictionary to cover any key commands and concepts learned.

Day 1:
  This day involved connecting to the server from my main windows pc through a Windows PowerShell terminal.
  I connected through the command "SSH user@<ip address>" where i inputted my selected username and the ip i 
  configured in the Netplan config file.
  This day of the challenge focused on learning the commands used for viewing the server info such as: ip addresses, 
  users, the architecture, devices, resource comsumption and bandwidth.
  Notion dictionary for day 1:
  https://www.notion.so/Day-1-Dictionary-239d21d4828a80b48c3efb4cf0711a58

Day 2:
  This day focused on the basic navigation and manipulation of the Linux system.
  This involved finding, creating, moving, and deleting directories and files.
  As well as this it introduced me to manuals through the "man" command showing me how to troubleshoot when im stuck
  and learn more about the system.
  Notion dictionary for day 2:
  https://www.notion.so/Day-2-Dictionary-239d21d4828a8037ae53fb59014162c4

Day 3:
  Day 3 talks about Global vs Local changes, and types of Linux users. As well as this it goes into detial about
  permissions including sudoing to change the user, password, computers hostname, and time info.
  Notion dictionary for day 3:
  https://www.notion.so/Day-3-Dictionary-23fd21d4828a805b82a3ce2697c2b6fe

Day 4:
  This day focuses on using 'apt' to install packages such as 'mc' and the use of 'mc' to explore the layout and the 
  contents of the standard directories in a Linux system.
  Notion dictionary for day 4:
  https://www.notion.so/Day-4-Dictionary-23fd21d4828a80bca3facfdd7ca15504

Day 5:
  This day focuses on an introduction to tab completion, searching the command history and reading a dot file.
  Notion dictionary for day 5:
  https://www.notion.so/Day-5-Dictionary-23fd21d4828a80158680f0a05bf1e546

Day 6:
  This day focuses on learning about and practicing the use of the vim editor, the use of vimtutor assisted in my 
  learning.
  Notion dictionary for day 6:
  https://www.notion.so/Day-6-Dictionary-246d21d4828a802680ead4e3303e2c89

Day 7:
  This day involved installing and using apache2 including stopping, restarting, checking status, loating the html 
  file and altering it.
  Notion dictionary for day 7:
  https://www.notion.so/Day-7-Dictionary-247d21d4828a80f99e6ad5ed93ede444

Day 8:
  This day focused on the grep command, using a pipe symbol and using the cut command to get desired info from files.
  Notion dictionary for day 8:
  https://www.notion.so/Day-8-Dictionary-24dd21d4828a80029c74f8b74836c34d

Day 9:
  This day involves looking at ports and enabling firewalls to give these ports rules to increase security.
  Notion dictionary for day 9:
  https://www.notion.so/Day-9-Dictionary-250d21d4828a80598dd5dd57b2f4c1a5

Day 10:
  This day focuses on scheduling tasks using 'at' and 'crontab' and all their usecases including creating, deleting and
  timestamping archives. I learned about individual crontab files, system crontab files and crontab files for daily, weekly
  and monthly tasks. I added cronjobs to automatically create backups at a regular inteval and to delete backups older 
  than a few weeks.
  Notion dictionary for day 10:
  https://www.notion.so/Day-10-Dictionary-253d21d4828a8067b997e60dd608d533

Day 11:
  This day focuses on searching the system using 'locate' and 'find' to find files with certain filenames, 
  sizes, last edited date and extensions. I also learned to use 'grep -R' to recurively serach directories 
  for specific phrases, and i also used the 'which' command to find where commands are run from.
  Notion dictionary for day 11:
  https://www.notion.so/Day-11-Dictionary-254d21d4828a80429791c0335031a4be
  
Day 12:
  In day 12 i installed WinSCP to use as a GUI assistant to transfer files from my Linux server to my windows PC via SFTP. 
  I could also create folders under the home directory and upload data such as images.
  There was no dictionary for day 12

Day 13:
  Day 13 talks about adding new users to the system and groups like sudo.
  Notion dictionary for day 13:
  https://www.notion.so/Day-13-dictionary-256d21d4828a80039c74f51f06065991

Day 14:
  Day 14 talks about permissions including viewing them using “ls -l”, changing the ownership of a file with “chown” and 
  changing permissions using “chmod”. As well as this i learned to read the UGO output of “ls -l” so that I can understand 
  what it means so I can change the relevant ownership details.
  Notion dictionary for day 14:
  https://www.notion.so/Day-14-Dictionary-259d21d4828a80e299e1fa256e6250f1

Day 15:
  This day focuses on repositories, it talks about the file /etc/apt/sources.list.d/ubuntu.sources which contains a list of 
  repositories or software channels. The guide I am following seemed to be out of date for this day so I needed to do deeper 
  research into multiverse and universe to understand how to enable them and found they were already enabled on my 
  installation of ubuntu.
  Notion dictionary for day 15:
  https://www.notion.so/Day-15-Dictionary-25ed21d4828a80ddae1ad3d4f6f6210a

Day 16
  This day focuses on compression of files in more detail, involving how to compress using tar (same as day 10) but includes 
  how to archive and compress separately using gzip. This day also talks about how to extract from both uncompressed and 
  compressed files
  Notion dictionary for day 16:
  https://www.notion.so/Day-16-Dictionary-25ed21d4828a8049ac8fcc7e8ae951f2

Day 17:
  In day 17 I looked at installing files/packages from the internet instead of using ‘apt install’ command 
  (practicing by installing nmap). This involved the use of ‘wget’, tar extraction of bzip2 compressed files, as well as 
  reading source files and following the installation instructions and what the standard process for this is, understanding 
  each step.
  Notion dictionary for day 17:
  https://www.notion.so/Day-17-Dictionary-262d21d4828a80eb96d6f7069dcd21d8

Day 18:
  Day 18 didn’t include any new commands but instead explored the systems log files including cron.daily and logrotate to 
  understand how the system keeps logs in check by managing how many days of logs to keep, splitting them into manageable 
  files and compressing them to save space. As well as this i discovered that ‘la’ can be used instead of ‘ls -a’
  There was no dictionary for day 18

Day 19:
  This day talks about soft/symbolic links and hard links giving details on how they work, when they would be used, how to 
  create them and how to check they exist.
  Notion dictionary for day 19:
  https://www.notion.so/Day-19-Dictionary-264d21d4828a8061ac43dffd4281ea72
  
Day 20:
  This day talks about bash scripting: creating file and making them executable to either automate or make tasks easier and 
  quicker to run.
  Notion dictionary for day 20:
  https://www.notion.so/Day-20-Dictionary-266d21d4828a808dae49fdecd33fc814
