# VestaCP-to-Rainloop-Cync
Simple PHP script to sync VestaCP domains to the Webmail client Rainloop

# Install instructions
Edit config.php with required information

Upload both files to your webserver

Go to http(s)://your.rainloopdomain.com/rainloopsync.php

Check created synclog.log to see if it worked


# Cron instructions
Edit config.php with required information

Upload both files to your server

Create cronjob "php -q /path/to/rainloopsync.php" with your desired sync frequency

