# pfSensePackageNotification
copied from https://forum.netgate.com/topic/158754/installed-packages-notification/2?_=1693093818421&amp;lang=en-US

Install the pfSense cron package.

Place the file (pkg_check.php) in the /root/ folder by going to diagnostics, edit file. and save the file.

Create a new cron job with this command.
/usr/local/bin/php -q /root/pkg_check.php 
