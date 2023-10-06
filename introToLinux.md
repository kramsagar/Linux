
⦁	What is mean by operating system?
⦁	It is a software
⦁	It is interface between user and computer hardware
Two main reasons need of OS:
⦁	Binary conversion –
We human send instruction in text. So OS knows how to convert the text to binary conversion
⦁	Resource allocation
Any task (closing browser, opening note pad) any process running in the system , it is required some cpu, memory to be allocated. As a human I don’t how much capacity I need to allocate for each process. But someone is allocating the resources to process.

⦁	We have 600+ linux distributions like –
⦁	Redhat enterprise linux
⦁	Fedora
⦁	Centos
⦁	Ubuntu, kubuntu, kali linux, linux mint, suse linux etc.,

⦁	Why special interest showing redhat linux? 
⦁	Example buying laptop store vs individual person:
 
⦁	If in case of issue store help you out all warranty related issues and fixes. But other you cannot expect the same.
⦁	So based on the subscription plan the company will provide the support.
⦁	We need to get commercial subscription
⦁	In Redhat – 
⦁	It provide 24 * 7 support
⦁	Trusted customer packages (no vulnerable) 
⦁	In fedora, developed by fedora community, but source code sponsored by redhat
⦁	Redhat privides – every 3 years we get one new version – v9, v10…
⦁	For any new redhat version release, they implement the changes and test it first in other linux like fedora. Before pushing it to redhat customers

⦁	What is architecture of Linux?
There are two ways we can control system -> GUI (using mouse or cursone) or CUI (commands)
What is the interface we have for CUI that is terminal.


 
⦁	Via terminal enter the command
⦁	Shell checks the commands exist or not. If it is right then converted it into binary format
⦁	Kernal allocate resource to execute the command
⦁	Once the output read send it back to shell.
⦁	Shell display on top of terminal

Terminal -> it is UI for user to enter commands
Shell -> it is interface between user and kernel, also it is interpreter to execute all commands in a sequence
Kernel -> kernel is heart of operating system, kernel is responsible for allocate resource. It is written c++ but kernel is not code, it is an image. The image gets loaded into memory and runs the whole system

Open source:
Code can be read by any user, modify, redistribute the code, sell the code under gpl (general public licence)
Commercial products cannot be modifiable. Like redhat they don’t share code and it cannot be modifiable

 
how security gets implemented?
⦁	firewall is the first security
⦁	but for linux, in front of firewall there is another protected feature called selinux (Security-Enhanced Linux)
⦁	along with additional kernal features:
⦁	pid namespace, uid namespace.
⦁	cgroup - cpu, memory, io etc., if system provides 100% resources to single process then it will be a problem. so we need some feature to controls the usage and distribution.
						

how SE linux works?
⦁	SELinux defines access controls for the applications, processes, and files on a system.
⦁	It uses security policies, which are a set of rules that tell SELinux what can or can’t be accessed, to enforce the access allowed by a policy. 
⦁	When an application or process, known as a subject, makes a request to access an object, like a file, SELinux checks with an access vector cache (AVC), where permissions are cached for subjects and objects.
⦁	If SELinux is unable to make a decision about access based on the cached permissions, it sends the request to the security server. 
⦁	If permission is denied, an "avc: denied" message will be available in /var/log.messages.

System setup:
downlaod boot - for exam; dvd for local setup practice.
https://developers.redhat.com/products/rhel/download
 

virtualization
 

vdi disk size - 100GB uses for swamp.. need to discuss.

setup steps:
 
by default 100gb alloted to root. leave it as it.

Enable the kdump
 

 
network & host just connected.

now create root user password and unlock: 
then create one normal user. in internet ssh with root account is not recommended to access to system. hence create one normal user.

 

it will take 20-30 min for redhat setup
 

user:
1. privileged user or admin users 
2. normal user
 

describe temrinal
 
 
once installation done, reboot.
 


 
highligted the ip of the vm to connect via remote ssh
enable bridge network in vm oracle box to enable host systemt to connect vm.

 

 
192.168.1.2

normal user:
 
privileged user:
 


command :
1.  su
2. pwd
3. ssh rkyasan@mahcineip
4. poweroff
5. ip address / ip a

------------------------------------------------------------------------------------------------------------------------

File types: ls -ltr
 
tty -> the type of communicaiton from keyboard to filesystem 















