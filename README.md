# E-Moodles
E-Moodles is Moodle message plug-in that connects the Moodle forum with sever mail. He allow user's to send and response to message that are sending from the Moodle's forum.
Develop by : Shani Shalel, Shirel Israelov and Shani Hayik.

### Overview  
The mail Address is mail that the specific university that connects the plug-in is created,
example: Ariel_University+12.6@gmail.com.   
Take a look at our video that represents the user side: https://www.youtube.com/watch?v=hXYRmv0WJvY.

### Installation :

In order for the script to run you should use Windows version 7 and up, install php version 7.2 and up, and Moodle version 3.11 , also E-moodles use PHP-Mailer ,you should notice when you download the file there is a PHP-Mailer file as well.


  1.Open Gmail address- first you should open a gmail account so the plug-in will use it as the email address for all the mail he will get. 
    notice that the IMAP and the POP are enabled on the settings.

  2.Download the script of the Plug-In. 
  
  3. Change the mail address and the password on the script.
  
  4.Change the DB settings to your settings on the script .
  
  5.Add the script to the Task Scheduler: 
    Open up notepad, add this command, with your own attributes:
	  "PATH_TO_PHP.EXE" -f "SCRIPT_TO_RUN.PHP"
    "PATH_TO_PHP.EXE" should be the path to the php.exe
		[ So it may look like this: "C:\Program Files (x86)\PHP\v5.3\php.exe" -f "C:\emoodles_plugin\gmail.php") ]
    Save this file as a .bat file (Batch file).
    Open up Task Scheduler 
    Create a task.
    Give it a name, Create a trigger and check the daily option.
    Now go to the Actions tab, hit New and it should say 'Start a program' by default.
    Browse to the batch file that you just made, click OK and you're done.

### Language Support:
This plugin includes support for the English and Hebrow language and has been tested for right-to-left (RTL) language support. 

### Features:
* sending forum messages from the user email account to all the group classes.
* Error reply email:in case of a student who is trying to send mail to the wrong course number ,an error message email is sent to the user .
  reply to a specific message box in the forum from the user email.


### Display
Please look at the E-Moodles Description How To Install.pdf file 


  
  
