# $${\color{blue}Linux\ Interview\ Questions}$$


<p align="right">  Shreyas Mane</p>

----------------------------------------------------------------------------------------------------------------

The following 15 Linux interview questions are suitable for freshers because these 
questions will have basic information about Linux.

**1. What is Linux?**
   
Linus Torvalds developed Linux, a Unix-like, free, open-source, and kernel operating 
system. Mainly it is designed for systems, servers, embedded devices, mobile devices, 
and mainframes and is also supported on major computer platforms such as ARM, 
x86, and SPARC.

**2. Explain the basic features of the Linux OS.**

Some basic features of Linux are:

•Linux is free and easily available.

• It is more secure than other operating systems because it uses security 
auditing and password authentication features.

•Linux has its personal software repository.

• It includes multiple languages throughout the world. Hence Linux supports 
different language keyboards.

• It offers CLI and GUI to use different commands and applications such as 
Firefox, VLC.

**3. Name some Linux Distros**

There are various Linux distros but the following are the most commonly used:

•Ubuntu

•Debian

•CentOS

•Fedora

•RedHat

**4. What are the major differences between Linux and Windows?**

Here's a comparison of the major differences between Linux and Windows:

| **Feature**               | **Linux**                                                | **Windows**                                            |
|---------------------------|----------------------------------------------------------|--------------------------------------------------------|
| **Source Code**           | Open-source                                              | Closed-source (Proprietary)                            |
| **Customization**         | Highly customizable with numerous distributions          | Limited customization with standard versions           |
| **Cost**                  | Generally free                                           | Paid (with some free versions like Windows 10/11 Home) |
| **Security**              | Considered more secure, less targeted by malware         | More targeted by malware, regular security updates     |
| **User Interface**        | Varies by distribution (e.g., GNOME, KDE, etc.)          | Consistent (Windows Explorer)                          |
| **Software Availability** | Extensive open-source software, fewer commercial options | Wide range of commercial software, extensive gaming    |
| **File System**           | Supports multiple file systems (ext4, XFS, Btrfs, etc.)  | Primarily NTFS                                         |
| **Hardware Support**      | Good support, especially for older hardware              | Excellent hardware support, especially for new devices |
| **Package Management**    | Uses package managers (e.g., APT, YUM, Pacman)           | Uses installers (e.g., EXE, MSI)                       |
| **Community Support**     | Strong community support, numerous forums and resources  | Paid support through Microsoft, with community forums  |
| **Command Line**          | Powerful command-line interface (Bash, Zsh)              | Command Prompt and PowerShell, less integral           |
| **Performance**           | Generally lighter and faster on older hardware           | Heavier, especially with newer versions                |
| **Gaming**                | Limited support, improving with tools like Proton        | Strong gaming support, wide range of titles available  |
| **Updates**               | User-controlled updates, no forced reboots               | Regular updates with possible forced reboots           |
| **Corporate Use**         | Widely used in servers and development environments      | Dominant in desktop environments and corporate IT      |

This table outlines some of the core differences between Linux and Windows, highlighting their strengths and weaknesses in different areas.

**5. Define the basic components of Linux.**

Majorly there are five basic components of Linux:

•Kernel: Linux kernel is a core part of the operating system that works as a 
bridge between hardware and software.

•Shell: Shell is an interface between a kernel and a user.

•GUI: Offers different way to interact with the system, known as the graphical 
user interface (GUI).

•Application programs: It is designed to perform a bundle of tasks through a 
bundle of functions.

•System Utilities: It is the software functions through which users manage the 
system.

**6. Elaborate all the file permission in Linux.**

There are three types of file permissions in Linux:

•Read: Users open and read files with this permission.

•Write: Users can open and modify the files.

•Execute: Users can run the file.

**7. What is the Linux Kernel? Is it legal to edit it?**

It is known as a low-level software system. TheLinux kernel tracks the resources and 
provides a user interface. This OS is released under GPL (General Public License). 
Hence every project is released under it. So, you can edit the Linux kernel legally.

**8. Explain LILO**

LILO, i.e., Linux Loader and is a Linux Boot loader. It loads the Linux operating system 
into memory and starts the execution. Most operating systems like Windows and 
macOS come with a bootloader. While in Linux, you need to install a separate boot 
loader, and LILO is one of the Linux boot loaders.

**9. What is Shell in Linux?**

In Linux, five Shells are used:

•csh (C Shell): This shell offers job control and spell checking and is similar to 
C syntax.]

•ksh (Korn Shell): A high-level shell for programming languages.

•ssh (Z Shell): This shell has a unique nature, such as closing comments, 

startup files, file name generating, and observing logout/login watching.

•bash (Bourne Again Shell): This is the default shell for Linux.

•Fish (Friendly Interactive Shell): This shell provides auto-suggestion, web based configuration, etc.

**10. What is a root account?**

The root is like the user’s name or system administrator account in Linux. The root 
account provides complete system control, which an ordinary user cannot do.

**11. Describe CLI and GUI in Linux.**

CLI, i.e., command line interface. It takes input as a command and runs the tasks of 
the system. The term GUI refers to the Graphical User Interface or the human computer interface. It uses icons, images, menus, and windows, which can be 
manipulated through the mouse.

**12. What is Swap Space?**

Linux uses swap space to expand RAM. Linux uses this extra space to hold 
concurrently running programs temporarily.

**13. What is the difference between hard links and soft links?**

Here is the table that shows the difference between soft links and hard links:

| **Hard Links**                                                      | **Soft Links**                                                      |
|---------------------------------------------------------------------|----------------------------------------------------------------------|
| It includes the original content.                                   | It includes the original file location.                              |
| Hard links are faster compared to soft links.                       | Soft links are slower.                                               |
| It shares similar inode numbers.                                    | It shares different inode numbers.                                   |
| There is no relative path for hard links.                           | Relative paths are used for soft links.                              |
| It doesn’t link directories.                                        | It links directories.                                                |
| Any change in this link reflects other files directly.              | Every change in this link reflects its hard link and the actual file directly. |
| It uses less memory.                                                | It uses more memory.                                                 |

**14. How do users create a symbolic link in Linux?**

Symbolic links, symlink, or soft links are shortcuts to files and directories. Users can 
create the symbolic link in Linux through the’ ln’ command. The general command to 
create a symbolic link is as follows:

ln -s <existing_source file> <optional_symbolic link>

**15. What do you understand about the standard streams?**

Output and input in Linux OS are divided into three standard streams:

•Stdin (standard input)

•stdout(standard output)

•stderr (standard error)

Under Linux, these standard streams channel communication of output and input 
between programs and their environment.

## $${\color{blue}Intermediate-Level\ Linux\ Interview\ Questions:}$$

The next 15 questions are the best suitable for those who have an intermediate level 
of experience in Linux:

**16. How do you mount and unmount filesystems in Linux?**

In this case, you can use the ‘mount’ and ‘umount’ commands.
For mounting:

•First, identify the partition through the fdisk -l command. You can also use the 
lsblk command for it.

•After identifying the partition, create the directory which will work as the mount 
point. For example, running the mkdir /mnt/mountpnt will create the 
mountpnt directory as the mount point.

•Finally, you can run sudo mount <partition> <mount_point_directory> to 

complete the mounting.

For Unmounting:

Once you check if the specific filesystem is in use, you can run the `sudo umount 
<mount_point_directory>` for unmounting. If you want to learn more about the mount 
command in Linux.

**17. How do you troubleshoot network connectivity issues in Linux?**

There are multiple ways to troubleshoot the network connectivity and find the issue 
correctly:

Check the Internet Connectivity:

First of all, please check if the internet connection option is on and also check the 
cables to find if there is any issue with it.

Verify the Network Configuration:

•Please check that your network is configured correctly and the network 
interface has your IP address. You can check it by running the ip addr or 
ifconfig commands.

•You can also run the ip route command to check if the default gateway is set 
properly.

•Finally, verify the DNS server configuration in the /etc/resolv.conf file.

Check the Firewall:

Sometimes, firewall rules block the internet connection for the system’s security. 
Hence, you can run the ufw or iptables command to modify the firewall rules.

Network Interface:

You can restart your network interface through the ifup and ifdown commands. Once 
you restart the network interface, please reboot the system to make changes 
successful.

**18. How do you list all the processes running in Linux?**

You can list the currently running process in Linux through various commands such 
as:

ps Command:
The ps command displays brief information about the running processes. You can use 
the ps -f or ps -f command because the -f option shows the full-format result, and the 
-e option displays all processes. Moreover, you can use the ps auxf command to get 
a detailed list of processes.

top and htop Command:

•The top command displays the real-time details about the system process and 
the complete resource usage.

•The htop command is the improved version of the top command because it 
displays the color-coded list with additional features such as sorting, 
filtering, sorting, etc.

**19. What is the chmod command in Linux, and how do you use it?**

You can use the chmod command to change the file permissions of the directories. It 
offers a simple way to control the read and write permissions. For instance, if you want 
to change the permission of the ABC.sh script and give it the write and executable 
permission, you can run the below command:

chmod u+wx ABC.sh

The chmod command is not limited to the write (w), read (r), and executable (x) 
permissions because there are symbolic modes and numeric modes.

**20. How do you check disk space usage?**

There are some simple commands you can use to check disk space usage, such as:

df Command:

The df or disk-free command shows the used and the available disk space. You can 
use the additional options to check disk space differently. For instance, you can use 
the df -h command to check the disk usage in the human-readable format.

du Command:

The du or disk usage command estimates and shows the disk space usage, so 
running the du command with no option shows the disk usage of your current directory. 
However, you can run the following command to check the disk usage of a specific 
directory:

du -sh ~/<directory> 

ncdu Command:

The NCurses Disk Usage, or ncdu command, displays more interactive disk usage. 
Similar to the du command, the ncdu command also requires the path of the specific 
directory to check its space.

**21. How do you find the process ID (PID) of a running process?**

You can use the following command to find the Process ID or PID of the currently 
running process:

pgrep Command:

The pgrep command shows the PID of a process through its name or other different 
attributes. For example, you can find the PID of process_1 using the below command:

pgrep <process_1>

ps Command:

ps command not only displays the currently running process but also shows the 
process’s PID. However, if you want to check the PID of a specific process, you can 
combine the ps with the grep command:

ps -e | grep -i <process_1> 

**22. What is the rsync command, and how do you use this command for synchronization?**

The rsync command is used to synchronize and transfer the files in Linux. It 
synchronizes files between two local systems, directories, or a network. The basic 
rsync command contains the following:

rsync <options> <source> <destination>

For example, let’s synchronize between Documents and the Downloads directory. For 
this, you need to run the following command:

rsync -av ~/Documents ~/Downloads

If you want to go one step further, then you can use the below command:

rsync -avz --delete ~/Documents ~/Downloads

In the above command:

•The -a option preserves all the permissions and other attributes

•The -v option displays the detailed output of the synchronization

•The -z allows compression that decreases the bandwidth use.

•The –delete option removes the file in the Downloads that do not exist in the 
Documents directory.

**23. How do you create a user account?**

You can use adduser and useradd commands to create a user for the system.

useradd Command:

Let’s create a username, “Ron,” and provide a password for accessing the system:

useradd Ron 

passwd Ron 

You can also explore the useradd command’s additional options to modify the new 
user’s permissions and privileges.

adduser Command:

The adduser command is similar to the useradd command, so let’s create a username 
“Shawn”:

adduser Shawn

passwd Shawn

**24. How do you format a disk in Linux?**

The mkfs or make file system command helps format the disk in the Linux system. All 
you need to do is use the following method to format the disk:

First, run the lsblk command to list the available partitions and identify which disk you 
want to format.

If the selected disk is mounted, then unmount it through the following command:
umount <partition>

Now, find the file system type of the disk, like EXT4, NTFS, or XFS. Once you are 
done then, run one of the following commands according to the file system type:

mkfs.ext4 <partition>

mkfs.xfs <partition>

mkfs.ntfs <partition>

Finally, mount the disk again through the mount command after the successful format. 
Moreover, please ensure that you have created a complete disk backup to eliminate 
the chances of data loss.

**25. How do you change the password for a user account?**

Changing the password of a user account is simple because all you need to do is use 

the passwd command:

passwd username 

For example, let’s change the password of a user “Ron” through the below command:

passwd Ron 

Once you run the command, the system will ask you to enter and confirm the new 
password.

**26. What is the difference between a process and a thread?**

Here is the table that shows the difference between processes and threads:

| **Comparison Factors** | **Process**                                                 | **Thread**                                                |
|------------------------|-------------------------------------------------------------|-----------------------------------------------------------|
| **Creation Time**      | Creation time is higher                                     | Creation time is less.                                    |
| **Dependency**         | It is independent because it does not share memory.         | It depends on other threads because they share some memory with other threads. |
| **Resource Usage**     | Resource use is higher                                      | Requires lesser resources.                                |
| **Termination Time**   | The termination time is higher                              | The termination time is less.                             |

**27. What is the ulimit command, and how do you use it?**

The ulimit command controls the resource limit for the user process. You can use 
the ulimit command to set the limit on the system resource to prevent consuming the 
higher resources. This command contains multiple options to set the limit. For 
example, you can use the u option to set a maximum number of processes to 50:

ulimit -u 50 

You can explore more options of the ulimit command.

**28. What is the find command, and how do you use it?**

The find command searches for files based on different factors such as name, size, 
permissions, etc. Here is the basic command:

find <directory> <file>

For example, let’s find a Linux.txt file located in the Downloads directory through the 
below command:

find ~/Downloads -name Linux.txt

Once you run the above command, the find command will start finding the Linux.txt in 
the Downloads directory and subdirectories.

**29. What is RAID in Linux?**

The full form of RAID is the Redundant Array of Independent Disk that allows the 
system to combine the different physical disk drives into a logical unit. RAID is used 
to improve the system’s disk performance and data integrity. There are different RAID 
levels you can configure according to the requirements. Here is the detailed 

Here is the information about RAID levels in table format:

| **RAID Level** | **Description**                                                                                                                                         |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| **RAID 0**     | It is called striping, which allows you to split the data into multiple disks without redundancy.                                                       |
| **RAID 1**     | It is called mirroring, which allows you to create a complete copy of data on multiple disks.                                                           |
| **RAID 5**     | It distributes the parity information and data on multiple disks.                                                                                       |
| **RAID 6**     | It is the improved version of RAID 5 as it uses two sets of parity information to provide higher data redundancy.                                       |
| **RAID 10**    | It combines RAID 0 and RAID 1 to generate the set of mirror disks to improve performance and redundancy.                                                |

**30. What are the challenges of using Linux?**

There are numerous challenges that a user faces while using Linux:

•Linux shows hardware compatibility issues in certain devices because 
manufacturers prioritize Windows compatibility.

•Learning Linux is not easy because the configuration and commands require 
proper knowledge.

•Although Linux supports Steam, it still needs to be impressed regarding game 
compatibility and availability.

•Sometimes users face driver and firmware-related issues.

## $${\color{blue}Advanced-Level\ Linux\ Interview\ Questions:}$$

These 15 questions will revolve around your experience and help you in preparing for 
the advanced-level Linux interview:

**31. What is the /proc file system?**

/proc (Proc File System) is the virtual file system that shows information about the 
system and the Kernel data structures. It is the essential interface to access the 
system, perform debugging tasks, check the Kernel functioning, find process-related 
information, and many more.

Therefore, you can use /proc file system in Linuxto get information about the system 
and modify the particular Kernel parameters at the runtime.

**32. How do you secure a Linux server?**

There are multiple methods to secure the Linux server and protect it from data 
breaches, security threats, and unauthorized access. Here are some of these 
methods:

•Create a strong password

•Update the server and apply security patches.

•Use secured protocols like SSH and configure it to use key-based 
authentication for higher security.

•Use the intrusion detection system (IDS) to monitor network traffic and 
prevent malicious activities.

•Configure the firewall to limit the inbound and outbound traffic on the server.

•Disable all unused network services.

•Create regular backups.

•Review logs and perform regular security audits.

•Encrypt network traffic and enable monitoring.

**33. What is strace command?**

The strace command is the diagnostic utility by which you can trace and monitor the 
system calls generated by the process. It allows you to find how programs interact with 
Kernel and can be used for debugging and troubleshooting. For example, let’s find the 
system calls generated by the ls command:

strace ls

Once you run the above command, the system will start tracing the list command and 
show the system calls generated by it. Output from the above command includes 
information like call name, argument, and return values.

**34. How do you optimize Linux system performance?**

You can optimize the Linux performance through various strategies to improve 
resource usage and efficiency. So some of the strategies are:

•Updates the system as per the latest one available.

•Optimize the disk, enable the caching, and optimize the access pattern.

•Manage memory and CPU usage.

•Disable the necessary services and use lightweight alternatives of the tools.

•Monitor the system resources regularly.

•Perform the Kernel parameter tune-up.

•Use tools like Performance Co-Pilot (PCP) to monitor system-level 
performance.

**35. How to administer Linux servers?**

Administering a Linux server requires different strategies and management to 
maintain the overall functionalities. Here are some major strategies you can follow:

•Handle user account management and assign appropriate access 
permissions.

•Configure the system to optimize the performance, improve the security and 
maintain the network connectivity.

• Implement the backup strategy to perform regular backups of the server.

• Implement the monitoring tools to track resource usage, system performance, 
and network.

•Set up monitoring tools to track system performance, resource usage, and 
network activity.

•Configure firewall, set up intrusion detection, manage user permissions and 
configure the SSH.

•Create a proper recovery planning that must include regular backup, critical 
configuration documentation, recovery process testing, and offsite storage.

**36. What is a Linux virtual memory system?**

Virtual memory is a great memory management utility in any OS. You can use the 
virtual memory system as secondary memory. This memory is used by both software 
and hardware in Linux so that your system can cope with the lack of physical memory. 
Moreover, virtual memory is also used to compensate for the RAM usage by 
transferring the data temporarily from RAM to disk storage.

**37. What do you understand about process scheduling in Linux?**

Process scheduling is the mechanism that identifies the order of processes running 
on the system. In other words, process schedulingdetermines the order and 
execution time of multiple processes running on the system concurrently. This process 
scheduler of Linux is priority-based and uses a preemptive algorithm. It allocates CPU 
time for different processes to ensure efficient CPU resource usage. These 
processes are dynamic, and their order can change depending on many factors, such 
as resource usage, process behavior, and scheduling policies.

**38. What are the most important Linux commands?**

There are a ton of useful commands in Linux, and here are some of the commonly 
used commands:

• ls: Display directory contents such as folders and files.

•mkdir: Used to create a new directory.

•pwd: Shows the current directory.

• top: Display system running processes and resource usage.

•grep: Search a specific pattern in a file.

•cat: Through this command, users can add multiple files and also display the 
content of the files.

• tar: Archives directories and files into a tarball.

•wget: Download files from the browser or web.

• free: Shows memory usage.

•df: Shows disk space usage.

•man: Gives a manual page for a specific command that displays instructions 
and details.

**39. What is the iptables command, and how to use it for network filtering?**

The iptables command configures Netfilter firewall rules providing the network 
address translation, packet filtering, etc. iptables inspects the network packet and 
then manages them according to the defined rules. Here is how you can use the 
iptables command for network filtering:

Run the below command to display the current iptables rules, including policies, 
chains, and other actions for the network:

iptables -L

The iptables configuration uses the predefined set of chains to process the network 
packages at different stages. So you can define rules to these chains for 
manipulating the network packets:

iptables -A  <chain>  <options> -j  <target>

In the above command:

• <chain> : Specifies the chain where you want to define a new rule.

• <options> : Defines the conditions for the rule, like ports, protocols, etc.

• -j <target> : Defines the target action when the packet matches the rule.

By default, iptables rules get automatically removed after the system reboot, but you 
can use the following command to make the rules persistent:

iptables-save > /etc/iptables/rules.v4

(check the file code for this question)

**40. How do you troubleshoot a Linux OS that fails to boot?**

In case of the system boot failure, you can follow various approaches such as:

•Check the warning and error messages you get during the boot process 
because it can help you diagnose the issues.

•Check the boot logs to find the exact reason behind the boot error.

•Open the GRUB bootloader and check the boot options to solve the booting 
problems.

•Check the hardware connections like cables, RAM, cooling fan, etc.

• If the system shows an error message related to the Kernel, try to boot it with 
the older Kernel version from GRUB.

• Identify the last changes you made in the system before the boot.

**41. What is the init process in Linux?**

The init or also called the initialization process is the first process that begins 
during the system boot. It is responsible for initializing and processing the system in 
its functional state. Hence, init works as the parent process because its process ID is 
1. Originally Linux systems used to have SysV init, but now it is developed as the 
systemd init (an improved version of SysV).

**42. What is SMTP?**

SMTP stands for Simple Mail Transfer Protocol. This set of communication guidelines 
allows the software to transmit electronic mail online. The main aim of SMTP is to set 
communication rules between servers. There are two models of SMTP:

•End-to-end model: This model is used to connect different organizations.

•Store-and-forward model: This model is used within an organization.

**43. What is LVM in Linux?**

The full form of LVM is Logical Volume Manager, which provides an advanced disk 
management approach in Linux. It is a subsystem that allows a user to efficiently 
allocate the disk space on the physical storage device.
You can use the LVM to create the logical volume for easy storage 
management through various features like resizing, volume mirroring, and snapshots. 
LVM is a powerful utility for disk management where you need dynamic storage 
allocations.

**44. What is the difference between UDP and TCP?**

The following table shows the difference between UDP and TCP:


| **Factors**           | **UDP**                                                                 | **TCP**                                                                                  |
|-----------------------|-------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| **Connection-oriented**| UDP does not establish a proper connection.                            | TCP is connection-oriented because it establishes a connection between the sender and receiver. |
| **Reliability**        | UDP does not provide a reliability mechanism.                          | It guarantees reliable data delivery by retransmitting corrupt packets or lost packets.  |
| **Usage**             | It is used in low overhead, speed, and real-time communication applications. | It is used where ordered data is delivered, and reliable data must be delivered.          |
| **Applications**      | Video/voice conferencing, DNS, online gaming, streaming media, etc.     | File transfers, email, web browsing, database transactions, etc.                         |


**45. What is /etc/resolv.conf file?**

The /etc/resolv.conf is the config file used for the DNS server resolution process. 
This config file is used to specify the DNS server, set up the search directive for 
domains, and configure the resolver options.

**46. What is the difference between absolute and relative paths in Linux?**

Absolute path = It specifies the exact location of a file or directory from the root 
directory (“/”). We will notice that they always start with a forward slash (“/”).

For Example: `/home/user/shree/geeksforgeeks.txt`

Relative paths = It specifies the location relative to the current working directory. In 
this we do not start with a forward slash (“/”).

For Example: `documents/file.txt`

**47. What is the grep command used for in Linux?**

The grep command is used to search for specific patterns within files or input 
streams. It allows us to find and print lines that we give to match the pattern.

For example: If we want to search `test` in a text file name “file.txt”. We use the 
following command

grep "test" file.txt

This command will search for the word `test` in the file named “file.txt” and print the 
matching lines.

**48. How do you check the status of a service or daemon in Linux?**

To check the status of a service or daemon, we can use the `systemctl` command 
followed by the service name.

For example: If we want to display the status of the Apache Web server. We use the 
following command.

systemctl status apache2

It will show whether the service is running, stopped, or in an error state.

**49. What is the difference between /etc/passwd and /etc/shadow files?**

The /etc/passwd file stores essential user information like usernames, user IDs, 
home directories, and default shells. Each line in the file represents a user account.

The /etc/shadow file contains encrypted passwords and other security-related 
information. It is only accessible by the root user or privileged processes

**50. How do you compress and decompress files in Linux?**

To compress files in Linux, you can use the tar command along with gzip 
compression.

For example: If we want to create a file name “shree” with gzip compression. We 
use the following command.

tar -czvf shree.tar.gz files

This command will create a compressed archive file containg the specified “files”
To decompress the same, we use the following command.

tar -xzvf shree.tar.gz

**51. What is the difference between a process and a daemon in Linux?**

A process is an executing instance of a program. It can be a foreground process that 
interacts with the user or a background process started by a user or another 
process.

A daemon is a background process that runs independently of user sessions. It is 
typically started at system boot time and performs system tasks or provides services. 
Daemons often have no user interaction and continue running even when users log 
out.

**52. How do you schedule recurring tasks in Linux?**

We can use `crontab` command for performing recurring tasks in Linux. By adding 
entries to the crontab file, we can specify when and how frequently a command or 
script should be executed

For Example: If we want to execute a script name “geeks.sh” every day at 3:30 AM. 
We use the following command.

crontab -e

This command opens the crontab file in an editor.
30 3 * * * /path/to/geeks.sh

**53. What is the sed command used for in Linux?**

The sed command is used to perform text transformations on files. It can search for 
specific patterns and replace them with desired text.

For Example:

sed `s/foo/bar/g` file.txt

This command replaces all occurrences of “foo” with “bar” in the file name “file.txt”

**54. What are runlevels in Linux?**

Runlevels in Linux define different system states, such as single-user mode or multiuser mode with or without a GUI. They determine which services start or stop during 
system startup and shutdown. The default runlevel is often set to a multi-user mode 
with a GUI (runlevel 5). Runlevel 3 is commonly used for a multi-user mode without a 
GUI.

## $${\color{blue}Bonus\ Linux\ Interview\ Questions:\}$$

The next 16 Linux interview questions are the most common ones recruiters ask.

**55. What is sudo in Linux?**

The word “sudo” is the short form of “Superuser Do” that allows you to run the 
command with system privileges. With this command, you can get the system’s 
administrative access to perform various tasks. The sudo command requires a 
password before the execution to verify the user’s authorization.

**56. What is umask?**

It is used for user file creation mode. When a user creates any file, then it has default 
file permission. Umask specifies restrictions for these permissions on the file, i.e., 
controls the permissions.

**57. How to find and kill a process in Linux?**

You can use different commands to kill a process, but first, you must find the PID of 
that specific process. So, please run the below command:

ps aux | grep <process>

Once you get the PID of the process then run the kill command to end it:

kill <PID>

If you don’t want to find the PID, then you can use the pkill command to kill a process 
by its name:

pkill <process>

The pkill command sends a signal (by default, SIGTERM) to the matched processes, 
causing them to terminate.

**58. What is network bonding in Linux?**

Network bonding is the process of creating a single network by combining two or more 
network interfaces. This combination of networks improves redundancy and 
performance by increasing bandwidth and throughput. The major benefit of network 
bonding is that the overall network works fine even if a single network in the bonding 
does not work properly.

**59. What is SELinux?**

SELinux or also known as Security-Enhanced Linux, is the security framework. It 
offers an additional layer of security to improve access control and strengthen security. 
SELinux was developed to improve the security policies to prevent unauthorized 
access and exploitation. However, learning about SELinux is essential before working 
on it can create serious security issues.

**60. What is the purpose of the SSH protocol in Linux, and how do you securely connect to a remote server using SSH?**

The Secure Shell (SSH) is a protocol in Linux which is used to establish a secure 
encrypted connection between a local and remote machine. It allows to securely 
access and manage remote servers. If we want to connect to a remote server using 
SSH. We can use the following command.

ssh username@remote_ip

Here replace the `username` with the desired username of the remote server and 
replace the `remote_ip` with the IP address of the remote server.

**61. How do you check the contents of a file without opening it in Linux?**

In Linux we can use the `cat` command to view the content of a file without opening 
it in an editor form.

For example: If we want to check content of a file with file_name = `geeks.txt`

cat geeks.txt

**62. What is the purpose of the crontab file in Linux, and how do you  schedule recurring tasks using cron jobs?**

The crontab file in Linux is used to schedule recurring tasks or cron jobs. It contains 
a list of commands or scripts that are executed at specified time intervals. To edit the 
crontab file, you can use the 

crontab -e command.

For example: If we want to run a script name `shree.sh` every day at 5 AM, we can 
use the following procedure.

First, we need to open the crontab in editorial format.

crontab -e

Secondly, add the entries in the crontab file.

0 5 * * * /path/to/shree.sh

**63. How do you find and replace text in a file using the sed command in Linux?**

The sed command (stream editor) can be used to find and replace text in a file. The 
basic syntax is sed ‘s/pattern/replacement/g’ filename.

For example: to replace all occurrences of “true” with “False” in a file

sed 's/true/False/g' file_name

**64. What is the purpose of the sudoers file in Linux, and how do you configure sudo access for users?**

The sudoers file in Linux controls the sudo access permissions for users. It 
determines which users are allowed to run commands with superuser (root) 
privileges. To configure sudo access, you can edit the sudoers file using the visudo 
command.

For example:

sudo visudo

Now add this line anywhere in the file. For instance, if we want to grant a user full 
sudo access.

user_name ALL=(ALL) ALL

**65. How do you change the ownership of a file or directory in Linux using the chown command?**

In Linux, you can change the ownership of a file or directory using the chown 
command. The basic syntax is chown new_owner: new_group filename.

For example: If we want to change the ownership of a file to user “shree” and 
group “users”.

chown shree:users file_name

**66. What is the purpose of the ping command in Linux, and how do you test network connectivity to a remote host?**

Ping command is used to test the network connectively between the local and 
remote hosts. It basically sends an ICMP echo request packet to the remote host 
and waits for the corresponding echo reply packet.

For example: If we want to check the connectivity to a remote host, we use the 
following command.

ping remote_host_ip

Here replace `remote_host_ip` with the Ip address of the host

**67. How do you recursively copy files and directories in Linux using the cp command?**

In linxux we can simply use `-R` option with the `cp` command to recursively copy 
the file and directories.

For example:

cp -R sourece_durectory destination_directory

**68. What is the purpose of the netstat command in Linux, and how do you view network connections and listening ports?**

The netstat command in Linux is used to display active network connections, routing 
tables, and listening ports. To view network connections and listening ports, use the 
netstat command with appropriate options.

For example: If we want to display all listening TCP ports, we can use the following 
command.

netstat -tuln

**69. How do you set up a static IP address in Linux using the command-line interface?**

To set up a static IP address in Linux using the command-line interface, you need to 
modify the network configuration file. The location and name of the file may vary 
depending on the Linux distribution, but commonly it is /etc/network/interfaces. Open 
the file with a text editor and modify the configuration to set a static IP address, 
subnet mask, gateway, and DNS servers.

For example:

iface eth0 inet static

address 192.168.1.100

netmask 255.255.255.0

gateway 192.168.1.1

dns-nameservers 8.8.8.8 8.8.4.4

Save the file and restart the network service or reboot the system for the changes to 
take effect.

**70. How to copy a file to multiple directories in Linux?**

We can copy a file to multiple directories in Linuxby these methods and 
command xargs, find, tee and shell loop.

•xargs command on Unix/Linux operating system converts input from 
standard input into an argument list for a specified command.

•The command find initiates a search and allows actions to be performed 
based on the search results.

•The tee command reads standard input and copies it to both standard 
outputs and to one or more files.

## $${\color{blue}Linux\ Admin\ Interview\ Questions:}$$

**71.How are files organized in Linux?**

Linux follows a hierarchical file system structure. The root directory is denoted by “/”, 
and files are organized in directories or folders within the root directory.

**72.How can you find the IP address of a Linux system?**

The ‘ifconfig’ or ‘ip addr show’ command can be used to display the IP address of a 
Linux system.

**73.What is the distinction between a hard link and a symbolic link in Linux?**

A hard link is a direct reference to a file, whereas a symbolic link is a reference to the 
file’s path. Deleting a hard link does not affect the file, but deleting a symbolic link 
breaks the link between the file and its path.

**74.How do you check the amount of disk space being used in Linux?**

The ‘df’ command displays information about the disk space usage on Linux, 
including the total, used, and available space on filesystems.

**75.How do you start and stop a service in Linux?**

The ‘systemctl start <service>’ command is used to start a service, and ‘systemctl 
stop <service>’ is used to stop a service in Linux.

**76.What are common causes of file permission issues in Linux?**

Common causes of file permission issues in Linux include incorrect ownership, 
improper permissions set for users or groups, and conflicts between different users’ 
permissions.

**77.How do you troubleshoot a Linux system that cannot connect to a remote server?**

Possible troubleshooting steps include checking network connectivity using tools like 
‘ping’, verifying firewall rules, checking DNS settings, and examining relevant log 
files for error messages.

## $${\color{blue}Linux\ Troubleshooting\ Interview\ Questions:}$$

**78.What steps would you take to fix a network connectivity issue in Linux?**

Steps would include checking physical connections, verifying IP configuration, 
checking firewall settings, ensuring DNS resolution is working, and using network 
troubleshooting tools like ‘ping’, ‘traceroute’, or ‘tcpdump’.

**79.How do you check the system logs in Linux?**

System logs can be checked using the ‘tail’ or ‘less’ command to view the contents 
of log files located in the ‘/var/log’ directory, such as ‘syslog’, ‘messages’, or 
‘auth.log’.

**80.What are the possible reasons for a Linux system running out of memory?**

Possible reasons include memory leaks in applications, excessive memory usage by 
running processes, inadequate memory allocation, or high memory demands from 
large datasets.

**81.How would you troubleshoot a slow-performing Linux server?**

Troubleshooting steps might involve checking system resource usage with tools like 
‘top’ or ‘htop’, monitoring disk I/O, analyzing network traffic, identifying memory or 
CPU bottlenecks, and reviewing application logs.

**82.What are common causes of a Linux system running out of disk space?**

Common causes include large log files, excessive data storage, uncontrolled growth 
of temporary files, improper cleanup of old files, or runaway processes generating 
excessive output.

**83.How can you identify and terminate a process that is using a lot of CPU in Linux?**

The ‘top’ or ‘htop’ command can display the processes using the most CPU. To 
terminate a process, the ‘kill’ command followed by the process ID (PID) can be 
used.

**84.How would you troubleshoot a Linux system that cannot boot up?**

Troubleshooting steps might include checking hardware connections, verifying 
BIOS/UEFI settings, booting into a recovery mode or live system, analyzing boot 
logs, and diagnosing disk or file system errors.

##  $${\color{blue} Linux\ Networking\ Interview\ Questions:}$$

**85.What does the ‘ifconfig’ command do in Linux?**

The ‘ifconfig’ command is used to configure or display network interfaces in Linux. It 
can be used to view or modify IP addresses, netmasks, and other network interface 
parameters.

**86.How do you set up a fixed IP address in Linux?**

A fixed IP address can be set up in Linux by editing the network configuration file 
(e.g., ‘/etc/network/interfaces’ or ‘/etc/sysconfig/network-scripts/ifcfg-<interface>’) 
and assigning the desired IP address to the interface.

**87.How do you configure a DNS server in Linux?**

DNS server configuration involves editing the ‘/etc/named.conf’ (BIND) or 
‘/etc/named/named.conf.options’ (ISC BIND) file to specify the server’s zone 
information, name resolution options, and defining forwarders or root hints.

**88.What is a firewall in Linux, and how do you set it up?**

A firewall is a network security system that filters and controls network traffic. In 
Linux, ‘iptables’ or newer ‘nftables’ can be used to set up firewall rules by defining 
filtering criteria, network zones, and desired actions.

**89.How do you check the network connectivity between two Linux systems?**

Network connectivity between two Linux systems can be checked using tools like 
‘ping’ or ‘traceroute’, which send packets to the target system and report on the 
round-trip time and the path taken.

**90.What is the purpose of the ‘route’ command in Linux?**

The ‘route’ command is used to view or modify the IP routing table on a Linux 
system. It displays information about the network routes and allows adding or 
deleting routes.

**91.How do you configure a Linux system to act as a router?**
To configure a Linux system as a router, IP forwarding must be enabled by setting 
the appropriate value in the ‘/proc/sys/net/ipv4/ip_forward’ file. Additionally, network 
interfaces and routing tables need to be configured accordingly.
