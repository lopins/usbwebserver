# <center>USBWebserver</center>

## Introduction

Most light weight local **portable web server** with Apache, PHP, MySQL and PHPMyAdmin for **Windows** on the Web. Just unzip enywhere (including USB flash drive), run and start using.		

## Preview

| VERSION | PHP | UPDATE |
| :----- | :-----: | -----: |
| v8.6.4 | PHP 8.0 | 02/20/2022 |
| v8.6.3 | PHP 7.4 | 02/20/2022 |
| v8.6.2 | PHP 7.1 | 11/11/2017 |
| v8.6.1 | PHP 5.6 | 11/11/2017 |
| v8.6.0 | PHP 5.4 | 11/11/2017 |

## Download

[usbwebserver_v8.6.5.zip](https://github.com/lopins/usbwebserver/blob/main/downloads/usbwebserver_v8.6.5-PHP8.1.zip) - **PHP 8.1**

[usbwebserver_v8.6.4.zip](https://github.com/lopins/usbwebserver/blob/main/downloads/usbwebserver_v8.6.4-PHP8.0.zip) - **PHP 8.0**

[usbwebserver_v8.6.3.zip](https://github.com/lopins/usbwebserver/blob/main/downloads/usbwebserver_v8.6.3-PHP7.4.zip) - **PHP 7.4**

[usbwebserver_v8.6.2.zip](https://github.com/lopins/usbwebserver/blob/main/downloads/usbwebserver_v8.6.2-PHP7.1.zip) - **PHP 7.1**

[usbwebserver_v8.6.1.zip](https://github.com/lopins/usbwebserver/blob/main/downloads/usbwebserver_v8.6.1-PHP5.6.zip) - **PHP 5.6**

[usbwebserver_v8.6.0.zip](https://github.com/lopins/usbwebserver/blob/main/downloads/usbwebserver_v8.6.0-PHP5.4.zip) - **PHP 5.4**

## Change log

> 02/20/2022

  - PHP 8.1.3
  
  - Apache 2.4.52
  
  - PhpMyAdmin 5.1.3
  
  - MySQL 5.7.36

> 11/11/2017

  - **Update:** Apache version - 2.4.29

  - **Update:** PHP versions - 5.6.32 for 8.6.1 and 7.1.11 - for 8.6.2

  - **Update:** PHPMyAdmin version - 4.7.5

  - **Update:** MySQL version - 5.6.34

  - **Change:** Set default port from **8080** to **80**
  
  - **Change:** Set default MySQL port from **3307** to **3306**

## Why?

I very like [USBWebServer](http://www.usbwebserver.net/) and very often used it for development. But it's author have stopped update it.
			
I made this update by myself and tried to connect to the author and send updated version to him but has no luck. So I decide to put updated version here.			

## HOWTO

- Download and Unzip USBWebserver.
				
- Go to unzipped folder and run **usbwebserver.exe**.
				
- If needed, allow your server processes in Windows Defender popup window.
				
- Choose your language at first start of USBWebServer.
				
- If you have other local web servers installed and they's ports conflicts with USBWebServer ports you can allways change default ports in **Settings** tab of your USBWebServer window.
				
- Put your project files in **root** folder or create subfolders here if you need create multiple projects in your site root.
				
- Go To [http://localhost/](http://localhost/) to view your site root and to [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/) for manage your databases.
				

## FAQ

**Where do i need to put the files?**

You need to put your files in the **root** directory.
				
After that you can reach your website at this link:  [http://localhost/](http://localhost/).

**Where can i find the setting files?**

You can change your settings in main USBWebServer window.
				
Also you can edit your settings manually: all the settings files a placed in the **settings** directory. You need to restart USBWebserver after changing the settings.
			

**What are the settings for PhpMyAdmin?**

Username is '**root**' and the password '**usbw**'.

You can reach PHPMyAdmin at this link: [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/)
