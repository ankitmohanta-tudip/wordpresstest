#Use below commands in Jenkins Build steps

sudo git clone https://github.com/saurabh80877/wordpress.git
cd wordpress
chmod 774 /home/azureuser/wordpress/composer.sh 
sudo wordpress/composer.sh
