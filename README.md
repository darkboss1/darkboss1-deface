# darkboss1-deface

# DARKBOSS1-DEFACE
This is a simple tool to automatically deface vulnerable websites.

(Tutorial video link at last of this page ⚠️)

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

apt update -y && apt upgrade -y && pkg install git -y && pkg install python -y && pip2 install requests && git clone https://github.com/darkboss1/darkboss1-deface.git && cd white-deface && pip install -r requirements.txt && git pull && python white-deface.py
  

Tool used for vulnerable website defacing

Tool devoloped by whxite


Telegram : https://t.me/darkboss1bd


# What the code does


The code is a Advanced program in Python that attempts to upload a provided HTML file to multiple websites as specified in a target file named "targets.txt". The uploaded HTML file is intended to replace the content of the index page on the target websites. The program uses the "requests" library to handle the HTTP requests. The user is asked to input the name or path of the HTML file to be uploaded. If the file is found, the program then reads the contents of the file and the "targets.txt" file, which contains a list of target websites. The program then loops through each website in the list and attempts to upload the HTML file using a HTTP PUT request. If the upload is successful, a message is displayed indicating that the upload was successful. If the upload fails, a message is displayed indicating that the upload failed.


***Visit Our Website. Click [here](https://serialkey.top) to go to the project.***
