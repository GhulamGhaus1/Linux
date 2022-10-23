make direcrtory for webfiles
**mkdir -p /var/www/domain.com/public_html**

set folder permission
**chmod -R 755 /var/www**

Copy the conf file 
**cp /etc/apache2/sites-available/000-default.conf /etc/apache2/sites-available/domain.com.conf**

Enable site

**a2dissite 000-default.conf**
**a2ensite domain.com.conf**

make sure you enable port 80 in traffic rules 

![image](https://user-images.githubusercontent.com/55359967/197382008-44eae51f-e6c3-42f8-95f0-359f3ee221fe.png)
