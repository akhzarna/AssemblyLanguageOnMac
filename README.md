# AssemblyLanguageOnMac
Run Assembly Language Code on MAC Using DosBOX
I have downloaded DosBox for MacOS and feeling the best way to run assembly language on MacOS. 
Let me share some steps to do this. 
1- Download DosBox.dmg for MAC and install 
2- Copy folder named Assembly to any place in your computer in my case i have copy assembly folder to desktop. 
(Download this folder from my repository) 
3- run command "mount c: /users/akhzar/desktop/Assembly" in DosBOX then write c: and press enter. 
4- Now you are in drive c to run Assembly Language Commands
5- Now run .asm file using following command c:\> nasm a.asm -o a.com -l a.lst (this will create two files one is .lst and other is .com) 6- Now run AFD to see this in Debug Mode c:\> afd a.com (use f1,f2 function keys to run and the program till terminate) 
7- To go back from debugger use the following command quit

