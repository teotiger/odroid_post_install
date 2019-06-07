# ODROID_POST_INSTALL

## Introduction
With ODROID_POST_INSTALL you can install and configure on a fresh ODROID (tested with [ODROID N2](https://www.hardkernel.com/blog-2/odroid-n2/) and Ubuntu 18.04) the following software:
- Apache web server with PHP and MySQL database
- [Certbot](https://certbot.eff.org/) packages and certificate for HTTPS/SSL
- [Ampache](http://ampache.org/) music web streaming server
- DLNA media server ([MiniDLNA](https://help.ubuntu.com/community/MiniDLNA/))
- File share and collaboration platform [Nextcloud](https://nextcloud.com/)

It also update the whole system and remove unnecessary desktop apps like LibreOffice or Thunderbird. See the script for further information.

The whole installation process take about 5 minutes.
After that you need 15 minutes more for configuration.

## Installation
Simply download the script and make it executable.

```bash
wget https://raw.githubusercontent.com/teotiger/odroid_post_install/master/odroid_post_install
chmod u+x odroid_post_install
sudo ./odroid_post_install
```

## License
ODROID_POST_INSTALL is released under the [MIT license](https://github.com/teotiger/odroid_post_install/blob/master/license.txt).

## Version History
Version 1.0 – June 7, 2019
* Initial release
