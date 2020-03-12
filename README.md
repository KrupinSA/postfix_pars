# POSTFIX LOG ANALIZER

[![N|Solid](http://www.postfix.org/mysza.gif)](http://www.postfix.org)

Log analyzer of the Postfix mail system.  
You can run *without* parameters,the main thing is that the **maillog** file is in the same directory.  

*By default*, the entire **maillog** file is parsed.  
A report is generated *.xlsx about domains and the number of messages.  

**Required python3.8 or later**

**From packages required**
- openpyxl

**Startup Methods**
```sh
$ ./senders_mail.py
```
**or** 
```sh
$ python3 senders_mail.py
```