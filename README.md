# Keylogger
Be the m@st3r of ur Targ3ts PC

Keylogger For PC
![K3yl00g3r f0r PC](https://miro.medium.com/max/1400/1*jYfK0N7SjIfZF1StmZekOQ.gif)
    Disclaimer:This Page does not promote or encourage any illegal activities,all contents in this page is meant for EDUCATIONAL PURPOSE only.

What is keylogger?

Keyloggers are a type of monitoring software designed to record keystrokes made by a user. One of the oldest forms of cyber threat, these keystroke loggers record the information you type into a website or application and send to back to a third party.
Criminals use keyloggers to steal personal or financial information such as banking details, which they can then sell or use for profit. However, they also have legitimate uses within businesses to troubleshoot, improve user experience, or monitor employees. Law enforcement and intelligence agencies also uses keylogging for surveillance purposes.

How to create a keylogger?

Lets create the Listening Shell first:

Run your Kali machine,
You will notice,in ‘Applications’ menu under ‘Exploitation tools’, ‘social engineering toolkit’ will be preinstalled.
![path to social engineering toolkit](https://miro.medium.com/max/1172/1*GDPYPzULQEWZ2BUA4qZohw.png)

Run that ‘social engineering tool’
![social engineering tool](https://miro.medium.com/max/664/1*PEdMGlybbyyeQlyuFH_7aA.png)

Then press ‘1’ to choose ‘Social-Engineering Attacks’.

Then choose ‘Powershell Attack Vectors’, i.e. option number ‘9’.

Then choose ‘Powershell Alphanumeric Shellcode Injector, i.e. option number ‘1’.

Now, they will be asking for our IP address,So, open a new tab in terminal,and type the command ‘ifconfig’ , then you will notice ‘eth0’,in that you will notice ‘inet’ and that is your ip address(192.168.XXX.XXX). Then press enter, now they will ask for port number type as mentioned,443. Then press enter.

Then they will ask that if we want to start the listener now,we will say ‘yes’.
Now after pressing enter, it will start ‘Metasploit Framework’.

Now lets locate the keylogger file:

Open the ‘root’ folder, in the navigation bar go to view and then mark ‘Show Hidden Files’, or just press ‘ctrl+H’ in the root folder.

Then find ‘.set’ folder,open ‘reports’ folder,then again open ‘powershell’ folder.

Then you will notice a text file named as ‘x86_powershell_injection.txt’.
![](https://miro.medium.com/max/672/1*0Jon-oFk-AH7411bFvESuA.png)

Copy that file and paste it in the ‘Desktop’.

Now rename the file to “x86_powershell_injection.bat”

Now you are ready for the attack.
Take the ‘.bat’ file in pen drive or with some social engineering techniques send that ‘.bat’ file in your target and run it in that computer.

And then you are the master of that machine.

Switch back to your terminal then you will notice your terminal has started to respond then,type ‘sessions’ and check for the available sessions.

type

    sessions -i 1

type 

     help 

then press enter. And check for the available options, and now you are good to go.

Enjoy!!

Cheers!❤
-VirusZZWarning

    Connect to me:
    GitHub
    LinkedIn
