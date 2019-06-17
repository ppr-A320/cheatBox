# Linux cheat sheat  
## Basic File Operations  
* ls - List files in a directory   
* cp - Copy a file  
* mv - Rename ("move") a file  
* rm - Delete ("remove") a file  
* ln - Create links (alternative names) to a file 

## Directory Operations
* cd-  Change your current directory 
* pwd - Print the name of your current directory, i.e., “where you are now” in the filesystem  
* basename - Print the final part of a file path  
* dirname - Remove the final part of a file path  
* mkdir - Create a directory  
* rmdir - Delete an empty directory  
* rm -r - Delete a nonempty directory and its contents  

## File Viewing  
* cat - View files in their entirety  
* less - View files one page at a time  
* head - View the first lines of a file  
* tail - View the last lines of a file  
* nl - View files with their lines numbered  
* od - View data in octal (or other formats)  
* xxd - View data in hexadecimal  
* gv - View Postscript or PDF files  
* xdvi - View TeX DVI files   

## File Creation and Editing  
* emacs - Text editor from Free Software Foundation  
* vim - Text editor, extension of Unix vi  
* umask - Set a default mode for new files and directories  
* soffice - Office suite for editing Microsoft Word, Excel, and PowerPoint documents  
* abiword - Edit Microsoft Word documents  
* gnumeric - Edit Excel spreadsheets  

## File Properties  
* stat - Display attributes of files and directories  
* wc - Count bytes, words, lines in a file  
* du - Measure disk usage of files and directories  
* file - Identify (guess) the type of a file  
* touch - Change timestamps of files and directories  
* chown - Change owner of files and directories  
* chgrp - Change group ownership of files and directories  
* chmod - Change protection mode of files and directories  
* chattr - Change extended attributes of files and directories  
* lsattr - List extended attributes of files and directories  

## File Location  
* find - Locate files in a directory hierarchy  
* slocate - Create an index of files, and search the index for string  
* which - Locate executables in your search path (command)  
* type - Locate executables in your search path (bash builtin)  
* whereis - Locate executables, documentation, and source files  

## File Text Manipulation  
* grep - Find lines in a file that match a regular expression  
* cut - Extract columns from a file  
* paste - Append columns  
* tr - Translate characters into other characters  
* sort - Sort lines of text by various criteria  
* uniq - Locate identical lines in a file  
* tee - Copy a file and print it on standard output, simultaneousl  

## More Powerful Manipulations  
* awk  
* sed   
* m4  

## File Compression and Packaging  
* gzip - Compress files with GNU Zip  
* gunzip - Uncompress GNU Zip files  
* compress - Compress files with traditional Unix compression  
* uncompress - Uncompress files with traditional Unix compression  
* zcat - Compress/uncompress file via standard input/output (gzip or compress)  
* bzip2 - Compress files in BZip format  
* bunzip2 - Uncompress BZip files  
* zip - Compress files in Windows Zip format  
* unzip - Uncompress Windows Zip files  
* uuencode - Convert file to uuencoded format  
* uudecode - Unconvert file from uuencoded forma  

## File Comparison  
* diff - Line-by-line comparison of two files or directories  
* comm - Line-by-line comparison of two sorted files  
* cmp - Byte-by-byte comparison of two files  
* md5sum - Compute a checksum of the given files (MD5  

## Disks and Filesystemn  
* df - Display available space on mounted filesystems   
* mount - Make a disk partition accessible  
* umount - Unmount a disk partition (make it inaccessible)  
* fsck - Check a disk partition for errors  
* sync - Flush all disk caches to Disks  

## Partitioning and Formatting Disks  
* parted, fdisk,or sfdisk - Partition a hard drive. Any of these programs will do: they simply have different user interfaces.  
* mkfs - Format a hard disk, i.e., create a new filesystem.  
* floppy - Format a floppy disk  


## Backups and Remote Storage
* mt - Control a tape drive  
* dump - Write a disk partition to tape  
* restore - Restore the results of a dump  
* tar - Read and write tape archives  
* cdrecord - Burn a CD-R  
* rsync - Mirror a set of files onto another device or hos  

## Spelling Operations  
* look - Look up the spelling of a word quickly  
* aspell - Interactive spelling checker  
* spell - Batch spelling checke  

## Viewing Processes    
* ps - List process  
* uptime - View the system load  
* w - List active processes for all users  
* top - Monitor resource-intensive processes interactively  
* xload - Monitor system load graphically in an X window  
* free - Display free memor  

## Controlling processes  
* kill - Terminate a process (or send it a signal)  
* nice - Invoke a program at a particular priority  
* renice - Change a process’s priority as it runs  

## Users and Their Environment
* logname - Print your login name  
* whoami - Print your current, effective username  
* id - Print the user ID and group membership of a use  
* who - List logged-in users, long output  
* users - List logged-in users, short output  
* finger - Print information about users  
* last - Determine when someone last logged in  
* printenv - Print your environmen  

## Working with User Accounts  
* useradd - Create a new account  
* userdel - Delete an account  
* usermod - Modify an account  
* passwd - Change a password  
* chfn - Change a user’s personal information  
* chsh - Change a user’s shell  

## Working with Groups  
* groups - Print the group membership of a user  
* groupadd - Create a new group  
* groupdel - Delete a group  
* groupmod - Modify a group   


## Basic Host Information  
* uname - Print basic system information  
* hostname - Print the system’s hostname  
* dnsdomainname - Same as hostname -d  
* domainname - Same as hostname -y  
* nisdomainname - Same as hostname -y   
* ypdomainname - Same as hostname -y  
* ifconfig - Set and display network interface informatio  