# Recovering Passwords From Icloud Backup File

The Goal of this demo was to attain any information from your computer that would allow you to decrypt an Itunes backup file from an Apple Device. This can be useful for extracting your own personal information or when investigating someone.

# Getting Icloud Backup From Itunes
Use the settings below to create a backup of your apple device, only if you do not have any backups on your machine.
![itunes settings](Screenshots/ItunesBackupSettings.PNG)

# Finding Passwords Already On Your Machine And Saving Them To A Dictionary
Open Passware Digital Forensic Kit and select 'Internet and Network' from the home page.
![](Screenshots/findYourPasswords1.PNG)
Click on Websites and it should begin searching for any passwords stored by any internet browser on the local machine.
![](Screenshots/findYourPasswords2.PNG)
Copy and paste all the passwords it found on your machine into a text file and save it somewhere you can find it.
NOTE: Make sure you delete this file at the conclusion of the demo if you have current passwords saved in the text file.

Now go to the home screen of the Passware software and click 
'Dictionary Manager' under tools. A known passwords dictionary is allowed in the full version, so we are going to make our own dictionary of known passwords using the ones we found in the above steps.
![](Screenshots/findYourPasswords3.PNG)
Inside Dictionary Manager Click 'add dictionary' and use the below screenshot as a template for adding your found passwords as a dictionary
![](Screenshots/findYourPasswords4.PNG)
Once you have your dictionary of found passwords added, it can be used within the other passware tools and you are ready for the next step.