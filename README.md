# Aoyama
A New version of Python3 P2P botnet, old version: http://github.com/Leeon123/Python3-botnet

***PLS Don't scan the executable file generated from pyinstaller or py2exe in any virtual scanner(such as VirtualTotal), if you want to keep using this project(i will continue update the code) and not be detected*** 
# News&Features
**BOT:**
- [x] Added Slowloris attack
- [x] Improved attack process
- [x] Auto enable ssl when attack
- [x] Encrypted traffic(xor)
- [x] Deamon(only linux)(PS: You can use pyinstaller option '--noconsole' on windows)
- [x] Hide itself(linux: Deamon + delete itself | windows: Hide sys.argv[0])

**CNC:**
- [x] Encrypted traffic(xor)
- [x] Coloured CNC
- [x] Using login.txt to check account.(Need improve, sometime may have bugs)
- [x] Keep-alive connection
- [x] Using putty raw-mode login(on windows) and telnet(on linux)
- [x] Using 'ping/pong' to check bot connection status(use 'scan' to check it by yourself or it checks every min.)

## Usage:
***Edit*** the cnc server ip and port into the client.py **at first**.

Then, edit the password of cnc.py and run the cnc.py:

    python3 cnc.py <port>
    
At Last, run the bot.py in any python3 environment(IDE, codeanywhere,etc.) or u can use pyinstaller to help u

then the **Bot** is online.

***To login cnc***, using **putty raw-mode** or telnet(**in linux**) to connect it then

click enter key will show the login parameters

        Username:
At this moment, u should create a text called login.txt and input the username and password in it

Like this:

        Leeon123 test

After that, Just input ur username and password.
        
                    
            Username:Leeon123
            Password:test
            
**Welcome to Aoyama C&C Server.**