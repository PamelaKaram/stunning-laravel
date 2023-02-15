
//Comands:
sudo apt install <package> for every package 

//Note: mcrypt package was depreciated so I had to follow these steps: 
//	 https://computingforgeeks.com/install-php-mcrypt-extension-on-ubuntu/

sudo a2enmod rewrite 
sudo systemcl1 restart apache2 


cd /var/www/html
pwd
sudo git clone 

 
curl -sS https://getcomposer.org/installer | sudo php -- -- installdir=/usr/local/bin -- -- filename=composer
sudo composer install 


pwd
sudo cp .env.example .env
sudo vim.env
// i to insert : change APP_NAME to ScriptingProject
// esc then :wq to save and quit
sudo php artisan key:generate


which apache 2 
cd /usr/sbin
cd /etc/apache2/ 
//(because apache2.conf wasn't in the previous dir)

sudo vim apache2.conf
// added the line
cd /etc/apache2/sites-enabled 
sudo vim 000-defaut.conf 
//edited the currentServerAdmin and DocumentRoot
//restart apache2: sudo /etc/init.d/apache2 restart

cd /var/www/html/stunning-laravel
sudo chgrp -R www-data storage bootstrap/cache
sudo chmod -R ug+rwx storage bootstrap/cache


