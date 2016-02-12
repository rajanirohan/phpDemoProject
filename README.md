# phpDemoProject

PHP Environment Installation Guide:

PHP Installation:
1.	Download PHP 5 or above version (Thread Safe).
2.	Extract downloaded file to environment folder.
3.	Set PATH variable with php.exe folder path in environment variable.

Apache Installation 
1.	Download Apache from http://www.apachelounge.com/download/ 
2.	Extract downloaded file to environment folder.
3.	Find Start > All programs > Accessories > Command Prompt...... BUT, right click, and select 'Run as administrator'.
4.	Enter the following commands:
•	cd \Apache24\bin
•	httpd -k install
•	httpd -k start


PhpStorm Installation
1.	Download and install php storm from JetBrains official site.

X-Debug Setup
1.	X-Debug is already installed with php packages. Check it with running “phpinfo();”  from project code.
2.	Add “JetBrains IDE Support” and “Xdebug helper” extensions to google chrome.
3.	Specify Debugger as X-Debug in File>Settings>Languages & Framework>PHP>Server and specify port number too.
4.	Make sure “listening for php debug connection” is on right most corner of navigation bar.

PHP Unit
1.	PHP Unit is inbuilt with PHPStorm. You just need to configure it.
2.	Download phpunit.phar file from internet. And put it in to environment folder.
3.	 Go to File>Settings>Languages&Framework>PHP>PHPUnit
4.	Select PhpUnit library as “Use custom auto loader”.
5.	Give path of phpunit.phar file to “path to script”. 
