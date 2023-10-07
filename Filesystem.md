/usr/bin - > any command try to find the binary from this folder
/boot/ -> 
    •	Once we press the power button and until we get login screen, in between the duration our system is taking booting process.
    •	It is trying load kernel into memory
    •	Starting the system startup services (systemd)
    •	For booting process, system required bootable files, it will store under /boot directory
o	/boot has kernel image
o	And boot loader files
/dev -> all hardware info stored as files inside machine. All these info stored under /dev directory
/etc/ -> all system level configuration and users info etc
/home -> inside system we have privileged and non-privileged user. 
    •	Whenever a non-privileged user trying to login into system then it needs a home directory
    •	/home every normal user has directories
/root is home directory of root user
Q. Difference between storing the files inside / directory and /root ?
    •	/ -> this location based on the privilege of the file all user inside system can access the file
    •	/root -> so only root can access these files
/run -> 
once u turn system, while running it stores some data. It stores run time data. Once your rebooted it wipe up all the data. Ex: temporary log files
the logs here maintain called journals.
/sbin -> system also run lot of command, these all are placed under sbin.  Ex: network related, mount related etc.,
/tmp -> store the temp data by all users. After 10 days it will wiped off if it untouched
/usr/ ->  this contains different things. As a user we installed lot of apps. All the application code files stored under this. 
	/lib – internet download software etc., installation code files keep here
	/local – you customized apps code files
	why do we need again one more /usr/bin , as we have already bin & sbin under root. 
	/usr/bin usr/sbin ->   this is like if someone deleted /bin, /sbin deleted, then this is another copy of files stored here. So user commands can work from here.  This is not a links. It is just another copy
/var -> inside /run and /var both places system maintained some logs. Inside /run non persistent logs it maintain. But inside /var it can hold logs for longer period.
	Example:  security, authentication log, selogs, boot logs, user related logs.
/var/tmp -> the life time of these files are 30 days. But /tmp life time is 10 days
