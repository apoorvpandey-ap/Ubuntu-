# Ubuntu-
			INDEX		Problems																								
	Login																												
	Move																												
	Copy from one/server TO /other/server																												
	Make a New Directory																												
	how to go in FOLDER or SUB-Folder or go back in Directory																												
	Path set																												
	Nano and Cat																												
	How to give a permisssion to  diractory[full control]																												
	Unzip and ZIp																												
	Add user Account	or remove user																											
	Code Repositery [SVN]																												
	Schedular check 																												
	Migrati BECHTEL	nba																											
	"Install wodpress and  lamp 
"																												
	How to remove php .apache ,mysql completely																												
	"How to install smaba 
"																												
	How to install mysql updated version																												
	How to set root password ,or swith to other account																												
	HOw to know the activity of the command which you type [man]																												
	Install ssl certificate 		and also redirect it 	Can't load random.rnd into RNG																									
	How to maka a mjultiple file in same folder 																												
	Delete multiple file with same extension																												
	Find file  in same folder																												
	How to make Github repository																												
	Size[of file or directory]																												
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
1	" Login
"				Things to do ?																								
	User name 	apoorv																											
	Pc name 	apoorv			How to add user in root group																								
	Password	vdoxx999			sudo apt install samba		whereis samba	"mkdir home/<user_name>/shambashare/ [user_name is used to smake  a path directly]
"																					
	Name	apoorv@apoorv	username@pcname		How to create a Diractory and also move one file to other at same time 				?																				
					where we set a path of java,ant,mavan				?																				
2	For move one file to other 				Why we use maven and m2 to path 				?																				
	sudo mv /home/apoorv/apache-ant-1.8.4-bin.zip /home				Why we need to extract zar file always 				?																				
					server name 																								
3	Copy from one/server TO /other/server				How to backup file				<file_name >.bak																				
	sudo scp rupesh@www6c.virtualdoxx.com:/home/openjdk-11.0.1_linux-x64_bin.tar.gz /home			Downloads open_jdk via this path 																									
																													
4	Make a New Directory		Multiple Directory	Remove Directory																									
	mkdir folder_name		mkdir folder_name1 folder_name2 folder_name3	rm -R folder_name																									
																													
																													
5	how to go in FOLDER or SUB-Folder or go back in Directory					java																							
	"apoorv@apoorv:/usr/local/java$ cd ..
"		 ===>After using cd .. ===>    	"apoorv@apoorv:/usr/local$
"																									
																													
6			Installing Java							Maven							ANT						<JAVA_HOME>  < ANT_HOME>   <MAVEN_HOME>   <M2_HOME>						
	Step-1	get ant file from www.virtualdoxx.com		installer guide						We set MAVAN as two PATH MAVAN & M2					Step-1	get ant file from www.virtualdoxx.com													
								Step-1	get ant file from www.virtualdoxx.com																				
	sudo scp rupesh@www.virtualdoxx.com:/ssd/var/www/html/vdoxx/download/_tools/2020/openjdk-11.0.1_linux-x64_bin.tar.gz  /home/rupesh																												
	" sudo cp -r openjdk-11.0.1_linux-x64_bin.tar.gz /user/local/java
"			pre-define directory /user/local/java				sudo cp -r apache-maven-3.1.0-alpha-1-bin.tar.gz //usr/local/apache-maven-3.1.0-alpha-1-bin			pre-define directory /usr/local/apache-maven-3.1.0-alpha-1-bin				sudo scp rupesh@www.virtualdoxx.com:/ssd/var/www/html/vdoxx/download/_tools/apache-ant-1.8.4-bin.zip  /home/rupesh														
	Step -3 extract gunzip file																												
	/usr/local/java$ sudo tar xvzf openjdk-11.0.1_linux-x64_bin.tar.gz 			unzip it first 				/usr/local/apache-maven-3.1.0-alpha-1-bin$ sudo tar xvzf apache-maven-3.1.0-alpha-1-bin.tar.gz 			unzip it first 				Step-2 copy apache-ant-1.8.4.tar.gz to /usr/local														
												/home/apoorv/.ssh/			"sudo cp -r apache-ant-1.8.4-bin.zip /usr/local/apache-ant-1.8.4-bin
"			pre-define directory /usr/local/apache-ant-1.8.4-bin											
								Set a Path [unziped file]							Step -3 extract gunzip file			unzip it first 											
	6.2	go to etc/profile and edit profile ===> set Environment and Path ===>		"JAVA_HOME=/usr/local/java/jdk-11.0.1
PATH=$PATH:$JAVA_HOME/bin
export JAVA_HOME
export PATH"				6.2	go to etc/profile and edit profile ===> set Environment and Path ===>		"MAVEN_HOME=/usr/local/apache-maven-3.1.0-alpha-1-bin
M2_HOME=/usr/local/apache-maven-3.1.0-alpha-1-bin
PATH=$MAVEN_HOME/bin:$M2_HOME/bin
export MAVEN_HOME
export M2_HOME
export PATH"				"cd /usr/local/apache-ant-1.8.4-bin
/usr/local/apache-ant-1.8.4-bin$ sudo unzip apache-ant-1.8.4-bin.zip
"							"JAVA_HOME=/usr/local/java/jdk-11.0.1
ANT_HOME=/usr/local/apache-ant-1.8.4-bin
MAVEN_HOME=/usr/local/apache-maven-3.1.0-alpha-1-bin
M2_HOME=/usr/local/apache-maven-3.1.0-alpha-1-bin
PATH=$PATH:$JAVA_HOME/bin:$ANT_HOME/bin:$MAVEN_HOME/bin:$M2_HOME/bin
export JAVA_HOME
export ANT_HOME
export MAVEN_HOME
export M2_HOME
export PATH"							
															Step-4 Set a Path [unziped file]														
7	Use of nano and cat [view and edit]														6.2	go to etc/profile and edit profile ===> set Environment and Path ===>		"ANT_HOME=/usr/local/apache-ant-1.8.4-bin
PATH=$ANT_HOME/bin
export ANT_HOME
export PATH"											
		  	directory_name nano file_name																										
																													
	vi is also used for edit																												
	cat is used for  view 		directory_name cat file_name																										
																													
8	How to give a permisssion to  diractory[full control] and change owner also 																												
	chmod -R 755 /usr/local/apache-maven-3.1.0-alpha-1-bin/			change owner																									
	chmode	change mde 		chown user_belone:user_to_change file_name																									
	-R	Retrive all the folders ,sub folder inside it 																											
	755 or 777	rwx rwx rwx ==>	  read write execute																										
	/usr/local/apache-maven-3.1.0-alpha-1-bin/	path_name																											
																													
9	Unzip and ZIp the .zip formate																												
	step:1																												
	sudo unzip apache-maven-3.1.0-alpha-1-bin.zip																												
	sudo 	command	permission																										
	unzip	argument	for .zip formate related																										
	apache-maven-3.1.0-alpha-1-bin.zip	file_name	file_name																										
	gzip /new_filename																												
	gunzip		for .gz file /file_name.gz																										
10	Add user account		Remove user																										
	sudo adduser username		sudo deluser --remove-home pc_name																										
	usermod -aG sudo username																												
11	Migration 																												
	1.First copy the file from a given location,  log in from the local machine 																												
	      Open the downloaded file and search the given (name) using (ctril+f)																												
	"        ssh rupesh@                                                                                                                                                                                                
1        copy files to your local machine                                                                                                                                                                                                
        scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_init/UserLayouts.properties /home/apoorv/label_design                                                                                                                                                                                                
2        search for username Ecopetrol in this file                                                                                                                                                                                                
        line no 13049 and 13053 will give you file names  ECO001Layout.properties  and ECOPETROL002Layout.properties                                                                                                                                                                                                
        copy these new files                                                                                                                                                                                                 
        scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_layouts/ECOPETROL002Layout.properties /home/apoorv/label_design                                                                                                                                                                                                
        scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_layouts/ECO001Layout.properties /home/apoorv/label_design/                                                                                                                                                                                                
3        search for LabelDesignProperties inside ECO001Layout.properties                                                                                                                                                                                                
        scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_designs/ECO001Design.properties /home/apoorv/label_design                                                                                                                                                                                                
        scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_designs/ECOPETROL002Design.properties /home/apoorv/label_design                                                                                                                                                                                                
4        your machine should have 5 files like below                                                                                                                                                                                                
                                                                                                                                                                                                        
                                                                                                                                                                                                        
                                                                                                                                                                                                                                                                             
                                                                                                                                                                                                        
                                                                                                                                                                                                        "																												
	"apoorv@dell:~$ scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_init/UserLayouts.properties /home/apoorv/LabelDesign/kosmos/                                                                                                                                                                                                        
                                                                                                                                                                                                        
rupesh@virtualdoxx.com's password:                                                                                                                                                                                                        
                                                                                                                                                                                                        
apoorv@dell:~$ scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_layouts/KOS004Layout.properties /home/apoorv/LabelDesign/kosmos/                                                                                                                                                                                                        
rupesh@virtualdoxx.com's password:                                                                                                                                                                                                        
                                                                                                                                                                                                        
apoorv@dell:~$ scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_designs/KOS004Design.properties /home/apoorv/LabelDesign/kosmos/                                                                                                                                                                                                        
rupesh@virtualdoxx.com's password:                                                                                                                                                                                                        
KOS004Design.properties                                                                                                                                                                                                        "																												
																													
	DART MIGRATION																												
Step-1	apoorv@dell:~$ scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_init/UserLayouts.properties /home/apoorv/LabelDesign/DART																												
	rupesh@virtualdoxx.com's password:																												
Step-2		"open the downloaded file UserLayouts.properties and find the DART Layout.properties 
DART001Layout.properties
DART002Layout.properties
DART003Layout.properties"																											
	Download one by one 																												
Step-3	apoorv@dell:~$ scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_initDART001Layout.properties /home/apoorv/LabelDesign/DART																												
		"apoorv@dell:~$ scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_layouts/DART001Layout.properties /home/apoorv/LabelDesign/DART
rupesh@virtualdoxx.com's password: 
DART001Layout.properties                      100% 1187     1.5KB/s   00:00    
apoorv@dell:~$ scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_layouts/DART002Layout.properties /home/apoorv/LabelDesign/DART
rupesh@virtualdoxx.com's password: 
DART002Layout.properties                      100% 1649     5.2KB/s   00:00    
apoorv@dell:~$ scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_layouts/DART003Layout.properties /home/apoorv/LabelDesign/DART
rupesh@virtualdoxx.com's password: 
DART003Layout.properties  "																											
Step-4	Search for LabelDesignProperties1 inside *layout .properties																												
		DART001Design.properties																											
		DART002Design.properties																											
		DART003Design.properties																											
	scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_designs/DART001Design.properties /home/apoorv/LabelDesign/DART																												
	scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_designs/DART002Design.properties /home/apoorv/LabelDesign/DART																												
	scp rupesh@virtualdoxx.com:/ssd/var/www/html/vdoxx/_designs/DART003Design.properties /home/apoorv/LabelDesign/DART																												
Step-5	Go to https://dc.virtualdoxx.com/html5 and login with -u rupesh and -p vdoxx999																												
Step-6	Create customer 		DART																										
		Create Project	Labels																										
		Create Layout	 open downloaded DART001Layout.properties			DART001Layout.properties DART002Layout.properties DART003Layout.properties																							
			search for layoutname and paste in create layout ID																										
																													
		Create Label design 	DART001Design.properties																										
			DART002Design.properties																										
			DART003Design.properties																										
																													
		Create User 	DART1	label																									
Step-7	Login with new user id password																												
Step7.1	Create user layout																												
Step7.2	Check customer name in layout 																												
Step-8	Go to labell design and download images																												
Step-9	Try to print spreadsheet and send to rupesh@virtualdoxx.com																												
																													
12   SVN is on http://www5e.virtualdoxx.com/																													
-->	rupesh-windows																												
-->	www6b	Step-1	ssh rupesh@www6b.virtualdoxx.com																										
		Step-2	cd /home/rupesh/svn/vdoxx-1.6-on-jboss-7/antbuild																										
		Step-3	ant																										
		Step-4	ant html5																										
		Step-5	scp /opt/vdoxx/jboss/standalone/deployments/vdoxx-html5-0.0.war  root@www.virtualdoxx.com:/var/www/html/vdoxx/download/_tools																										
-->	www6c																												
	-->	Step-1	ssh rupesh@www6c.virtualdoxx.com																										
		Step-2	cd /home/rupesh/vdoxx-2020-A/antbuild																										
		Step-3	ant																										
		Step-4	ant html5																										
		Step-5	scp /opt/vdoxx/jboss/standalone/deployments/vdoxx-html5-0.0.war  root@www.virtualdoxx.com:/ssd/var/www/html/vdoxx/download/_tools/2020																										
																													
																													
13	/etc/crontab  [is used to check the schedular activity ]																												
	Task Name	isActive (yes/no)	timing UTC	timing in IST																									
	vdoxx scheduler test	"yes
"	1:00	11:00																									
	VDOXXSCANLISTENER DAEMON	"yes
"	every 3 minutes	every 3 minutes																									
	MySQL DB Backup	"yes
"	5:00	15:30																									
																													
14	"INSTALL WORDPRESS AND LAMP 
"																												
"
"		OS -Ubuntu 18.4																											
		Before install wordpress we have to install lamp																											
		"lamp - linux- apache -mysql-php
"																											
		"sudo apt-get update -y
"																											
"
"		First we have to install apache 		Setup webserver in linux		"
"																							
		sudo apt install apache2 -y																											
"
"		Second install mysql		For wodpress databases																									
		sudo apt-get update																											
		sudo apt-get install mysql-server																											
		"Please enter 0 = LOW, 1 = MEDIUM and 2 = STRONG: 0
"																											
				select 0																									
		y																											
		y																											
		y																											
		y																											
		Third install php																											
		sudo apt install php -y		make sure to install php 7 or updated version																									
		apache2 -v		check for activate or not																									
		php -v		check for activate or not																									
		sudo mysql -v		check for activate or not																									
																													
"
"		"sudo apt install wget

"																											
		wget https://wordpress.org/latest.zip		installing wordpress																									
		ls		chek the file name "latest.zip"																									
		sudo apt install unzip		unzip package 																									
		unzip latest.zip																											
		ls		for check the directory create "wordpress"																									
		cd wordpress/																											
		ls																											
		sudo cp -r * /var/www/html		if not copy to var/www/html GIVE a permission using chmode -R 777 /var/www/html																									
		cd /var/www/html																											
		ls		remove file index.html																									
		sudo rm -rf index.html																											
		ls																											
		INstall some php module 																											
		sudo apt install php-mysql php-cgi php-cli php-gd -y			it help to connect with databases																								
		sudo systemctl restart apache2			for restart the apache server																								
		sudo chown -R www-data:www-data /var/www/html			change the permission because apache want to www																								
		ip a			user your local host ip to start WORDPRESS intall suceesfully put localhost/ on address bar																								
																													
		"                sudo mysql  -u root -p                                                                                                                                                                                                 
                CREATE database wordpress;                                                                                                                                                                                                
                CREATE USER 'vdoxx'@'localhost' IDENTIFIED BY 'vdoxx999';                                                                                                                                                                                                
                GRANT ALL PRIVILEGES ON * . * TO 'vdoxx'@'localhost';                                                                                                                                                                                                
                 flush privileges;                                                                                                                                                                                               
                SHOW GRANTS FOR 'vdoxx'@'localhost';                                                                                                                                                                                                
                quit                                                                                                                                                                                                "																											
																													
		LAST fill the wordpress  form																											
	Video link	https://www.youtube.com/watch?v=na-fT9ZgWPM																											
																													
15  How to remove php .apache ,mysql completely																													
																													
sudo apt-get remove –purge php*																													
sudo apt-get purge php*																													
sudo apt-get autoremove																													
sudo apt-get autoclean																													
sudo apt-get remove dbconfig-php																													
sudo apt-get dist-upgrade																													
																													
sudo dpkg --get-selections | grep php | cut -f 1																													
sudo apt-get remove --purge <package name from the previous command output>																													
sudo whereis php																													
sudo rm -rf <directory/file path from the previous command output>																													
																													
"Remove apache completey
"																													
sudo service apache2 stop																													
sudo apt-get purge apache2 apache2-utils apache2.2-bin apache2-common				dont use this line it will delet apache predefined from  ubuntu /usr																									
sudo apt-get autoremove																													
																													
sudo apt-get remove --purge <package name from the previous command output>																													
sudo whereis apache																													
sudo rm -rf <directory/file path from the previous command output>																													
																													
To uninstall MySQL																													
																													
sudo apt-get remove –purge mysql*																													
sudo apt-get purge mysql*																													
sudo apt-get autoremove																													
sudo apt-get autoclean																													
sudo apt-get remove dbconfig-php																													
sudo apt-get dist-upgrade					Check version 																								
			-------------------------------------------.>>>>>>>>	"post fix 
"	apache2 -v 																								
sudo dpkg --get-selections | grep mysql | cut -f 1					php -v 																								
sudo apt-get remove --purge <package name from the previous command output>					"mysql -v 
"																								
sudo whereis mysql																													
sudo rm -rf <directory/file path from the previous command output>																													
																													
website link																													
																													
																													
																													
Install Samba ubuntu maket place																													
Conf some file name with share folder path 																													
Conf User name and User group for Samba acess																													
Try to ping apoorv laptop to rupesh laptop 																													
Try to ping rupesh laptop to apoorv laptop 																													
																													
																													
17	How to install samba																												
	sudo apt update																												
	"sudo apt install samba
"																												
	whereis samba																												
	"samba: /usr/sbin/samba /usr/lib/samba /etc/samba /usr/share/samba /usr/share/man/man7/samba.7.gz /usr/share/man/man8/samba.8.gz
"																												
	mkdir /home/<username>/sambashare/																												
	sudo nano /etc/samba/smb.conf																												
		"[sambashare]
    comment = Samba on Ubuntu
    path = /home/username/sambashare
    read only = no
    browsable = yes"		Then press Ctrl-O to save and Ctrl-X to exit from the nano text editor.																									
	sudo service smbd restart																												
	sudo ufw allow samba																												
	sudo service smbd restart																												
	sudo ufw allow samba																												
	sudo smbpasswd -a username			Username used must belong to a system account, else it won’t save.																									
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
																													
	you can type ip address of other device it wll connect 																												
	user 	device which you have to connect																											
	password	device which you have to connect																											
																													
reference from																													
																													
18            How to install mysql latest verion																													
	ref link																												
																													
19            How to set root password ,or swith to other account																													
	swith user 	sudo -i or su																											
	change password	sudo passwd	change and user password																										
																													
20	what is differance between less and man comman																												
	less command is used to display the line in one screen or page 																												
	man command is used for check or know the activity of the command which you execute 				for ex -man adduser																								
																													
21	Install SSL certificate in Apache2																												
																													
Step-1	Pre-installation																												
	Install Apache 2 on Ubuntu Linux																												
	Update system repositories				sudo apt-get update																								
	Install Apache 2 with the apt command				sudo apt install apache2																								
	Verify the Apache installation				apache2 -version																								
	Configure the Firewall Settings				sudo ufw app list																								
	Allow Apache on UFW [Uncomplicated Firewall] and verify its status				sudo ufw allow 'Apache'																								
	 Verify that the Apache service is running				sudo systemctl status apache2																								
	 Verify that Apache is running properly and listens on your IP address				hostname -I																								
																													
																													
Step-2	Post-Installation				apoorv.virtualdoxx.com																								
	Set up a domain name				sudo mkdir -p /var/www/sampledomain.com/html																								
	Then assign the ownership of the directory through the following commands:																												
					sudo chmod -R 755 /var/www/sampledomain.com																								
	Let us now create an index page that we can later access to test if Apache is running our domain name. Create an HTML file either through the Nano editor or any of your favorite text editor																												
					nano /var/www/sampledomain.com/html/index.html																								
	Enter the following HTML for the index page				"<html>
<head>
<title>Welcome to the page sampledomain.com!</title>
</head>
<body>
<h1>You got Lucky! Your sampledomain.com server block is up!</h1>
</body>
</html>"																								
	You can save a file in nano by using Ctrl+X and then enter Y and hitting Enter.																												
										       																			
	Apache needs a virtual host file to serve the contents of your server. 				sudo nano /etc/apache2/sites-available/sampledomain.com.conf					"<VirtualHost *:80>        
          ServerAdmin admin@sampledomain.com        
          ServerName sampledomain.com        
          ServerAlias www.sampledomain.com        
          DocumentRoot /var/www/sampledomain.com/html        
          ErrorLog ${APACHE_LOG_DIR}/error.log        
          CustomLog ${APACHE_LOG_DIR}/access.log combined        
</VirtualHost> "																			
	To activate the new configuration, you need to run:				systemctl reload apache2																								
	 Enable the domain configuration file				sudo a2ensite sampledomain.com.conf			important for activation sites																					
					systemctl reload apache2																								
	The output will suggest activating the new configuration				sudo a2dissite 000-default.conf																								
	Now restart the Apache service:				sudo systemctl restart apache2																								
																													
																													
																													
																													
																													
																													
																													
Step 3	Finally go to 				sudo nano /etc/hosts																								
					"127.0.0.1       localhost
127.0.1.1       wwwc1
127.0.1.1       apoorv.virtualdoxx.com
127.0.1.1       sampledomain.com
# The following lines are desirable for IPv6 capable hosts
::1     ip6-localhost ip6-loopback
fe00::0 ip6-localnet
ff00::0 ip6-mcastprefix
ff02::1 ip6-allnodes
ff02::2 ip6-allrouters"																								
																													
Step 4	Last Giving Path of SSL certificater 				sudo mkdir /home/vdoxx/ssl																								
	insert 3 files																												
		name.cer																											
		name.key																											
		name.conf																											
	Give the path of SSL certificate 				nano /etc/apache2/sites-enable/apoorv.virtualdoxx.com.conf																								
	And redirect it http to https 																												
					"<VirtualHost *:80>
        ServerAdmin apoorv@apoorv.virtualdoxx.com
        ServerName apoorv.virtualdoxx.com
        ServerAlias www.apoorv.virtualdoxx.com
        DocumentRoot /var/www/apoorv.virtualdoxx.com/html
        Redirect permanent / https://apoorv.virtualdoxx.com/
        ErrorLog ${APACHE_LOG_DIR}/error.log
        CustomLog ${APACHE_LOG_DIR}/access.log combined
</VirtualHost>

<VirtualHost apoorv.virtualdoxx.com:443>
        ServerAdmin apoorv@apoorv.virtualdoxx.com
        ServerName apoorv.virtualdoxx.com
        ServerRoot /var/www/apoorv.virtualdoxx.com/
        ServerAlias www.apoorv.virtualdoxx.com
        DocumentRoot /var/www/apoorv.virtualdoxx.com/html/
        SSLEngine on
        SSLCertificateFile /home/vdoxx/ssl/leaf.cer
        SSLCertificateKeyFile /home/vdoxx/ssl/private_key.pkcs8
        SSLCertificateChainFile /home/vdoxx/ssl/intermediate.cer

        <Directory ""/var/www/apoorv.virtualdoxx.com/html"">
                AllowOverride None
                Order allow,deny
                allow from all
                AllowOverride All
                DirectoryIndex index.htm
        </Directory>
</VirtualHost>"					click hear for self signed certificate if you get PROBLEM like  Can't load random.rnd into RNG click here			yrtytrty																
	refferance from																												
																													
22	How to make a multiple file in one folder 																												
	touch a.text b.text c.cpp d.cpp																												
																													
23	Delete multiple file with same extension																												
	"rm ./*.cpp
"			rm -rf folder_name 			rf == recursive folder																						
	Attention - It will work only when you are in the same diractory			It will delet the folder 																									
																													
24	Find  command 																												
	Search FInd file extension																												
	find -type f -name "*.txt"			find . -type f -iname "*.txt"																									
																													
	*.txt"  = = using extension to find the similar file type 			iname is used to find the similar type of file  it doesnt matter it should be UPPER or LOWE case																									
																													
	Find file with permission 																												
	find -type f -perm 0644																												
																													
	Find file with size 																												
	find -type f -size +1kb																												
																													
25	Top / Process																												
																													
	it help to see the process in real time running 			it will not work on real time 			help to show the process id of firefox			it help to close the programm bu name or pwd process id 																			
	top			ps aux			pgrap firefox			kill firefox																			
										or																			
										kill 1194																			
26	Service																												
	sudo service service_name start		OR	systemctl start service_name																									
	sudo service service_name stop																												
	sudo service service_name  restart	n Py																											
																													
27	Github repositery																												
																													
	Step -1 	Download Python and its Jdk or java jdk for run																											
		Open Pycharm and make on programm and save it 																											
		remember the location of save file  																											
																													
	Step-2	cd /home/vdoxx/PycharmProjects/pi/venv																											
		cd /home/vdoxx/PycharmProjects/pi/venv																											
		"sudo apt-get install git git-extras
"																											
		git init																											
		"sudo git remote add origin
"																											
		"sudo git remote add origin https://github.com/apoorvcreate/python.git
"																											
					Make a new repository 																								
					Initialize this repository with a README [SELECT IT]																								
					create repository																								
					you got a new link on that copy it and paste on terminal				"https://github.com/apoorvcreate/python.git
"																				
																													
																													
		"sudo git remote add origin https://github.com/apoorvcreate/python.git
"																											
		git config --global user.name "apoorvcreate"																											
		"git config --global user.email apoorvcreate@gmail.com
"																											
		 git pull																											
		"pull origin master
"																											
		"git branch --set-upstream-to=origin/master
"																											
		git add -A																											
		" git commint -m ""Update readme, added hello.py ""
"																											
		  git push origin master 																											
																													
	reff from https://www.youtube.com/watch?v=wBp0Rb-ZJak&t=12529s			https://www.youtube.com/watch?v=wBp0Rb-ZJak&t=11931s																									
																													
																													
																													
																													
																													
																													
28	sudo du -h --max-depth=1 /path/name																												
																													
			we can change depth=1 according to that how much file to run																										
	find $HOME -type f -printf '%s %p\n' | sort -nr | head -10																												
																													
			help to search 10 most size file in your laptop 																										
			if you you to increase you size just put the value after		head -10 or head -20																								
																													
	du -sh		file size 					
