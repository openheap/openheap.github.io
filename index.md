---
　　layout: default
　　title: Uplusware
---

![UplusFtp](http://openheap.github.io/images/openheap.png)

# About

To provide the stable and free software for people.

The free software and open source code is forbidden to use for commercial purpose directly(for example, integrating them to some selling product). 
Anybody can enhance or modify them, but please don't delete or modify any logo, license, link and so on about Uplusware/Openheap.

https://github.com/openheap

![UplusFtp](http://openheap.github.io/images/uplusware.jpg)

***Contact***

Any problem or cooperative please contact uplusware@gmail.com

***
![erisemail](http://openheap.github.io/images/erisemail.gif)
# eRisemail Server
* A free e-mail server based on the Linux and MySQL.
* Support GB2312, UTF-8 and UCS2 Format
* Support Web UI Management System
* Supported Protocol: SMTP, POP3, IMAP, WebMail(HTTP/HTTPS)
* Support iCalendar Format(RFC2445) / Mozilla Thunderbird Lightning Plugin
* Support multiple authentication way. (CRAM-MD5 DIGEST-MD5 APOP)
* Support Mailer Group
* Support multiple user policy
* Support auditing mails
* Support loading and extending Anti-junk Engine dynamically
* Support the mail with huge size attachment( Maximum size is 2G )
* Support mail rapid index and access
* Recommended platform: CentOS

***Binary***
* The Lastest version: v1.6.07
 * [简体中文版](https://github.com/openheap/erisemail/raw/master/centos7-erisemail-bin-cn-utf8-x86_64-linux-1.6.07.tar.gz)
 * [English](https://github.com/openheap/erisemail/raw/master/centos7-erisemail-bin-en-utf8-x86_64-linux-1.6.07.tar.gz)

***Source Code***
* https://github.com/openheap/erisemail

***Installation***
* Run release.sh to generate the installation files package
* run intsall.sh in installation package
* configure /etc/erisemail/erisemail.conf
* /etc/init.d/eriseutil --install
* /etc/init.d/erisemail start

***
![UplusFtp](http://openheap.github.io/images/easyftpsrv.gif)
# UplusFtp Server
* Free and green FTP server based on Windows
* Support multi-user & multi-directory
* Support Web File Access
* Support NT Service Mode.

***Binary***
* The lastest Version: 1.7.3.3
 * [简体中文版](http://openheap.github.io/uplusftpsrv-cn-1.7.3.3.zip)
 * [English](http://openheap.github.io/uplusftpsrv-en-1.7.3.3.zip)

***Run as minimal***
* Use the following VBScript code
```VBScipt
Set WshShell = WScript.CreateObject("WScript.Shell")
FSO = CreateObject("Scripting.FileSystemObject")
FTP = FSO.GetFile(Wscript.ScriptFullName).ParentFolder.Path
WshShell.Run FTP&"\ftpadmingui.exe", 0
```

***
![niuhttpd](http://openheap.github.io/images/niuhttpd.png)
# Niuhttpd Server
* HTTP/HTTPS Server and C++ web service framework
* Support internal API, CGI/FastCGI, PHP/PHP-FPM and WebSocket
* Support 2ndary development.

***Binary***
* The lastest Version: [0.3](https://github.com/openheap/niuhttpd/raw/master/centos7-niuhttpd-bin-mon-x86_64-linux-0.3.tar.gz)

***Source Code***
* https://github.com/openheap/niuhttpd

***Installation***
* Run release.sh to generate the installation files package
* run intsall.sh in installation package
* configure /etc/niuhttpd/niuhttpd.conf
* /etc/init.d/niuhttpd start

***Code Sample***
* cd api and make install (it's for API code sample, including a MySQL acesss sample)
* cd cgi and make install (it's for CGI code sample)
* cd ws and make install (it's for WebSocket code sample)

***NIU***
* NIU means 钮(niǔ)
