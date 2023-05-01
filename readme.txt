#sudo apt-get install apache2
#sudo cp -r eks-test/ /var/www/html/
#sudo mv /var/www/html/index.html /var/www/html/index_backup
# sudo mv  /etc/apache2/sites-available/000-default.conf /etc/apache2/sites-available/back-default
# sudo mv apache2/000-default.conf  /etc/apache2/sites-available/

#sudo a2enmod
--- past the following line 

proxy proxy_ajp proxy_http rewrite deflate headers proxy_balancer proxy_connect proxy_html

#sudo systemctl restart apache2

# docker-compose up

you can access the on the browser http://0.0.0.0/ 
