# migrate the aquia site
* cp /var/www/html/[site name]-files/docroot/* /var/www/htmls/[site name]
* vi settings.php
** modify $databases = array { 'host' = ' [ aws db reference]'

# enable site, restart apache
* sudo a2disite default
* sudo a2ensite [ aws site instance ]
* sudo systemctl restart apache2
* in browser enter http://public ip 

# migrate aquia site files
* cp the place-these-two-dirs-in-sites-default.tar from the s3 bucket
* untar
* sudo mv downloads/FILES-DIR/files [ aws instance of the site ]/sites/default
* sudo mm downloads/FILES-DIR/files-private [ aws instance of the site ]/sites/default
* in browser enter http://public ip 
