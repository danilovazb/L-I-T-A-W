L-I-T-A-W
=========

L.I.T.A.W v1.0

## Description ##

This script sends a sequence to whatsapp the victim so it locks the application, tested only on Android 4.3 Jelly Bean

## Requirements ##

* python-dateutil
* python-argparse

### How to use ###

To use is simple, just type: 
$ Python litaw.py 

It will bring an interactive menu with locking options.
---

##### Login Whatsapp #####

To enter the login Whatsapp, edit the file from line 8 to 11 in st4wa.py

To enter a number and get a whatsapp password, you can follow the tutorial on this site:

http://unknownsec.wordpress.com/2014/04/29/yowsup-tricks-com-whatsapp/

```
password = ""                                           
password = base64.b64decode(bytes(password.encode('utf-8')))
username = ''                                               
keepAlive= False                                            
```

### Where it was created ###

Debian GNU/Linux 7 3.2.0-4amd64
