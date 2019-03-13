# Mantis app for YunoHost
Mantis Server

**Shipped version:** 2.19.0

- [Yunohost project](https://yunohost.org)
- [Mantis website](https://www.mantisbt.org/)

![](https://www.mantisbt.org/images/mantis_logo_262x90.png)


[![Install Mantis with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=mantis)

### Installing guide

 1. App can be installed by YunoHost **admin web-interface** or by **running following command**:

         $ sudo yunohost app install https://github.com/YunoHost-Apps/mantis_ynh
         
         After install :
 
        1. Login in mantis
        2. put your sql user and password (you can find them via ```nano /var/www/mantis/config/config_inc.php.sample``` in cli mode)
        3. Admin user for db is same user for sql same for password
        4. First login is user: administrator pwd: root
        5. sudo rm -r /var/www/mantis/admin

 
### Upgrade this package:

        $ sudo yunohost app upgrade mantis -u https://github.com/YunoHost-Apps/mantis_ynh

