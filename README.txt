HOW TO INSTALL AND RUN APPLICATION

Step 1: Install XAMPP/WAMP


Step 2: Add php to windows environment variables:
		GOTO Environment Variables in System Control
		GOTO PATH
		CLICK NEW
		PASTE THE php.exe directory (C:/xampp/php)
		
Step 3: Install Symfony

		GOTO htdocs directory (C:/xampp/htdocs) in CMD or Powershell
		type ==>> php -r "file_put_contents('symfony', file_get_contents('https://symfony.com/installer'));"
		
		
Step 4: Check if symfony has appeared in htdocs
		If it did: GOTO Step 5,
		else, GOTO Step 3
		
Step 5: Generate New Symfony Project
		type ==>> php symfony new todoListUsingSymfony

		If gives an error of version then do:
		type ==>> php symfony new todoListUsingSymfony 3.0
		
		
Step 6: Check in localhost

		Open XAMPP Control Panel and Turn on Apache
		
		GOTO link localhost/todoListUsingSymfony
		
		View your project
