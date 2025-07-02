
# DARKBOSS1-DEFACE
This is a simple tool to automatically deface vulnerable websites.


It uses WebDav vulnerability to exploit.
This script sends a PUT requests to the websites given in the targets.txt file. Unauthenticated requests will be accepted and your html script will be uploaded in the website. You will get the link with your script whch you can see it. (sometimes it defaces the homepage directly.)

You need to put your website urls in the targets.txt file and put your deface script in the same folder ie: white-deface. then use the tool


# Note

⚠️Only defaces websites with WebDAV vulnerability(Accepts unauthenticated PUT requests)⚠️

Thank you [darkboss1](https://serialkey.top) for your source code.


# Installation
____________________

    $ apt update -y && apt upgrade -y
    $ pkg install git -y
    $ pkg install python -y
    $ pip2 install requests
    $ git clone https://github.com/darkboss1/darkboss1-deface.git
    $ cd darkboss1-deface
    $ pip install -r requirements.txt
    $ git pull
    $ python darkboss1-deface.py
   
   
# Single installation command
_______________________________________

apt update -y && apt upgrade -y && pkg install git -y && pkg install python -y && pip2 install requests && git clone https://github.com/darkboss1/darkboss1-deface.git && cd darkboss1-deface && pip install -r requirements.txt && git pull && python darkboss1-deface.py
  
Tool used for vulnerable website defacing

Tool devoloped by darkboss1


Telegram : https://t.me/darkboss1bd

***Visit Our Website. Click [here](https://serialkey.top) to go to the project.***
