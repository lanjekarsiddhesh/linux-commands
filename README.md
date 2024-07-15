# Linux Command Reference

### File and Directory Management
- ls: Lists the content of a directory.
- pwd: Shows the current working directory's path.
- cd: Changes the current directory.
- mkdir: Creates a directory.
- rmdir: Removes an empty directory.
- rm: Removes files.
- rm -r: Removes a directory with all files inside.
- cp: Copies files and directories, including their content.
- mv: Moves and renames files.
- touch: Creates an empty file.
- cat: Lists, combines, and writes a file's content to the standard output.
- file: Checks the file type.
- zip: Creates a zip archive.
- unzip: Extracts files from a zip archive.
- tar: Creates an archive without compression.
- vi, nano, jed: Text editors.
- source [file_name]: Read and execute the file content in the current shell.
- gpg -c [file_name]: Encrypt a file.
- gpg [file_name].gpg: Decrypt an encrypted .gpg file.
- less [file_name]: Show the contents of a file with navigation using the less command.
- more [file_name]: Display contents of a file page by page.
  
### Text Processing
- grep: Searches for a specific string within files.
- sed: Finds, replaces, or deletes patterns in files.
- head: Displays the first 10 lines of a file.
- tail: Displays the last 10 lines of a file.
- awk: Finds and manipulates patterns in files.
- sort: Sorts file content.
- cut: Sections and prints lines from a file.
- diff: Compares two files and shows differences.
- tee: Prints command outputs to both the terminal and a file.
  
### System Information and Management
- locate: Finds files from the system's database.
- find: Outputs the location of a file or directory.
- sudo: Runs a command as a superuser.
- su: Runs programs in the current shell as another user.
- chmod: Modifies a file's read, write, and execute permissions.
- chown: Changes a file, directory, or symbolic link's ownership.
- useradd: Creates a new user account.
- userdel: Removes a user account.
- df: Displays the system's disk space.
- du: Checks a file or directory's storage consumption.
- fdisk -l: Display disk partitions, sizes, and types with the command.
- top: Displays running processes and system resource usage.
- htop: Provides an interactive interface for monitoring system processes.
- ps: Creates a snapshot of all running processes.
- uname: Prints information about the machine's kernel, name, and hardware.
- hostname: Shows your system's hostname.
- time: Calculates commands' execution time.
- systemctl: Manages system services.
- watch: Runs another command continuously.
- jobs: Displays a shell's running processes.
- kill: Terminates a running process.
- shutdown: Turns off or restarts the system.
- wget: Downloads files from a URL.
- curl: Transmits data between servers using URLs.
- scp: Securely copies files or directories to another system.
- rsync: Synchronizes content between directories or machines.
- Mount: Show currently mounted file systems.
- Findmnt: Display target mount point for all file systems.
- Uptime: Display system uptime, including the load average.
- Timedatectl: Query and change the system clock.
- W: List of logged-in users.
- Whoami: See which user you are using.
- finger [user_name]: Show information about a particular user.
- Wait: Pause the terminal or a Bash script until a running process is completed.
- Pmap: Display a memory usage map of processes.
- Bg: List and resume stopped jobs in the background.
- Fg: Bring the most recently suspended job to the foreground.
- Passwd: Change the current user's password or another user's password.
- Groupadd: Add a new group.
- Groupdel: delete a group.
- Last: Show the last system logins.
- Id: See details about the active users.
- whereis [command]: Use the whereis command to find the source.
- lscpu: See CPU information.
- Lsblk: See information about block devices.
- Lshw: List hardware configuration information.
 
### Network Information
- netstat: Shows the system's network information, like routing and sockets.
- traceroute: Tracks a packet's hops to its destination.
- nslookup: Queries a domain's IP address and vice versa.
- dig: Displays DNS information, including record types.
- ip addr show : List IP addresses and network interfaces.
- ip address add [IP_address]: Assign an IP address to interface eth0.
- whois [domain_name]: Display more information about a domain.
- ifconfig: Displays the system's network interfaces and their configurations.
- ssh [user_name]@[remote_host]: 	Connect to a remote host as a user via SSH.
- Sftp: Interactive file transfer over encrypted SSH session using SFTP protocol.
- telnet [host]: Connect to the host via Telnet default port 23.
- ping: Checks the system's network connectivity.
  
### Other Useful Commands
- history: Lists previously run commands.
- man: Shows a command's manual.
- echo: Prints a message as a standard output.
- ln: Links files or directories.
- cal: Displays a calendar in the terminal.
- alias: Sets and removes aliases for files or commands.
- apt-get: Manages Debian-based distributions' package libraries.
