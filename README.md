# php-drupal-onboarding
Simple step by step tutorial to learn php and drupal. #MayTheForceBeWithYou
To Download XAMPP (Windows) use thr following link : 
https://www.apachefriends.org/download.html
Follow the steps, I did not need Perl, mail server so I suggest that you download what is absolutely required. 
Once the installion is complete. Go to the following path to find the root of your project. 
C://xampp/htdocs

Traditionally, on the c-panel provided by xampp, we "start" the Apache server. However, PHP (current versions) come with an in-built server. In this project, until we move on to Drupal and more complex topics we will use the PHP'server. To use this follow the below steps : 
Open XAMPP and ensure that Apache is not running
Open C://Users/location/<create folder names Sites>
Create your website folder structure within Sites. 
That should comprise of index.php which local host will be pointing to. 
  
To point the localhost to pick up files from sites do the following : 
Open XAMPP and click on cmd and type the following commands: 
cd C:\Users\Shri Rachana\Sites\firstwebsite
php -S localhost:8000

Hence you have started the PHP7.1.26 server and it is listening to http://localhost:8000
Document root is C:\Users\Shri Rachana\Sites\firstwebsite

When all the work is complete Press Ctrl-C to quit from the server


Ensure that the server is started evertime you want to use PHP and quit once the work is complete. 
