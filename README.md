 NAME        : admin_cmd_interface.sh

 SYNOPSIS    : This intractive script shall provide various menu on out put and let user to select the menu to execute.
  	

 DISCRIPTION : On Executing this script, this script will diplay list of menu and ask user to select the menu to execute.
               Below is the menu list.
               1) CHANGE PASSWORD:	On selecting this meniu user can change his/her password.

               2) DISK SPACE: On selecting this menu, script will ask for path/mount where it will find disk usage.

               3) LOGIN TO OTHER BOX: On Selecting this menu , Script will ask for you to enter user name and hostname/IP
	
               4) SEE ALL SERVICES RUNNING ON THE SERVER: On Selecting this menu script will list all running services. 

               5) SHOW THE PORTS OPEN TO USE:On selecting this menu script will list open port list.
              
               6) SHOW ALL JAVA APPLICATION RUNNING:On selecting this menu script will list all java applications.
		
               7) KILL A APPLICATION : On selecting this option user has to provide process ID to kill
           
               8) EXIT FROM MENU : On Selecting this menu script will exit with status 1.


 EXIT CODE  : On selecting exit by user exit code will be non-zero.

 LOGS       : Considering this script are mostly use for Admistation task so are info and error logs are log in 
              local3.info and local3.err syslog priority. if this priority is not define in syslog.cfg file it will not log
              but it will give common error on STDERR ouput.
