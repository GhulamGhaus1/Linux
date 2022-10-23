make direcrtory for webfiles
**mkdir -p /var/www/domain.com/public_html**

set folder permission
**chmod -R 755 /var/www**

Copy the conf file 
**cp /etc/apache2/sites-available/000-default.conf /etc/apache2/sites-available/domain.com.conf**

Enable site

**a2dissite 000-default.conf**
**a2ensite domain.com.conf**
