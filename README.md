# Hacker-Helper
-[ h4k3r h3lp3r]-

Its just a simple program to solve a simple problem. When I practice my CTFs, I noticed that there are some commands that I always use. With ever session, I end up copying an empty template of said commands, and replacing the IP address of each one.

Hacker Helper helps solves that issue for me. This program will ask me for the IP that I am targeting, it will then place it in the correct area of all my common commands, and gives me a text file with all the commands ready for me to simply copy and paste into the terminal.

The commands appended in this version are for:
Nmap / Masscan / Nikto / GoBuster / Enum4Linux / Hydra (FTP - HTTP - SSH)


NOTE:
The text file will be created in the location you run the executeable from.
Please give it a few minutes to start.
Its coded 100% in Python, and I used PyInstaller to create the executible.


Like I said, a simple program to solve a simple problem.
I hope you find it useful.

-ryn0f1sh


----------------
UPDATE 3: There is an updated version, which is rebranded as <b>HLPR</b>.
</br>It is part of the <b>CTF Ware</b> toolkit that is pinned on the front of this page.
</br><b>HLPR</b> will be released as its own tool later this year (2022) from the team at <b>exeCODEable</b>.

----------------
UPDATE 2: I figured it out. Apprently, when using VS Code to compile the .py file, it automatically creates the output text file in the /home directory. When you use PyCharm to compile the .py file, it will create the output in the same location as the .py file. Looks like I need to create a version 2 to allow you choose the location of the file.

----------------
UPDATE 1:
I have come across an intresting issue. I coded the application in PyCharm, and it runs fine when compiled in it. Yet, if I tried to run it using VS Code, it would not produce the text file, not sure why.


