#Use below commands in Jenkins Build steps

sudo git clone https://github.com/saurabh80877/wordpress.git
mkdir nginx-conf
cp wordpress/nginx.conf nginx-conf/nginx.conf
chmod 774 /home/azureuser/wordpress/composer.sh 
sudo wordpress/composer.sh
