# Q&A time! 

1. Which shell runs in my terminal?
It´s GNU! Version 5.3.15(2)-release

2. Where am I?  
I want to know which absolute path my home directory has in comparison to my downloads folder.  
home directory: /c/Users/<user>  
download folder: /c/Users/<user>/downloads

3. Where do commands come from?  
I have **24** directories in my PATH and the directory that is searched first is /c/Users/<user>/bin.  
Also, curl is installed in /ucrt64/bin, git is installed in /ucrt64/bin as well.  python3 is installed in /c/Users/<user>/AppData/Local/Microsoft/WindowsApps.  
Asking for the version of git results in git version 2.56.0.windows.4

4. My Disc Space  
The size of my disc is 238G of which 95G are used. So I still have 143G available.

5. Stopping a runaway process  
After running the command sleep 600 in one terminal, nothing happened. In a second window the command ps aux | grep sleep showed four three digit numbers " 304  161  304 428". Using "-ef" instead of "aux" in the prior command results in less numbers.  
As google suggests the difference in the amount of processes shown lies in syntax that is used. ps aux uses BSD-style syntax and displays columns like %CPU, %MEM, VSZ, RSS, STAT and COMMAND. ps -ef displays UID, PID, PPID, STIME and CMD due to its use of of UNIX-style syntax.  
After killing the sleep process the first window shows Terminated sleep 600 and can process a new command. 






