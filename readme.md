![Not maintained](https://img.shields.io/badge/maintained%3F-no!-red.svg?style=flat)

NEWVHOST SCRIPT
====================

Simple script to help you create new Apache virtual hosts quickly and pain free. With the optional step to also create a mysql database and user for your new virtual host.

Requirements
---------------------
- Apache 2.4+
- MySQL 5+
- User with sudo access

Installation
---------------------

1. Download the [latest release] (https://github.com/SilverBull/Newvhost/releases/latest) 
(optionaly you can use `wget --no-check-certificate --content-disposition https://github.com/SilverBull/Newvhost/releases/download/0.02/package.zip`.
2. Extract the files where you want and navigate inside the folder
3. Edit the first section of *newvhost* after your needs.
4. Give the *installer* script execution permission with `chmod +x vhinstaller`
5. Run the installer with `sudo ./vhinstaller`
6. Use the now available `sudo newvhost` command to create your first virtual host.

When finished the installation you can safely delete the files you downloaded.

Uninstallation
---------------------

1. Give the *uninstaller* script execution permission with `chmod +x vhuninstaller`
2. Run the uninstaller with `sudo ./vhuninstaller`
3. Done

Configuration
---------------------

| Variable      | Default value | Description                                                                                     |
|---------------|---------------|-------------------------------------------------------------------------------------------------|
| tSERVERUSER   | root          | User to user for permissions                                                                    |
| tLOCATION     | /var/www/html      | Location to host all virtual hosts (recommended is the home folder of the user specified above) |
| tLOCATIONSAFE | \/var\/www/html    | Safe ocation path, must be same as tLOCATION!                                                   |
| tDBPW         | null          |                                                                                                 |


Special thanks
---------------------

Special thanks to the original creator

[darkwhispering](https://github.com/darkwhispering/Newvhost)
