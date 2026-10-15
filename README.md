# Ancora-Education-Ucertify-Lab24
# Securing the FTP Service

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=7]

## Instructions
In this lab, you will learn to secure the File Transfer Protocol (FTP) service. The FTP service runs on a computer to provide basic, unencrypted file transfer capability for connecting users. It is most commonly used for anonymous FTP, providing public files to anyone. To secure the FTP service, here's what you need to do:

1.From the taskbar, open File Explorer.

2.In the This PC window, double-click Local Disk (C:) to open its window. 

3.In the Local Disk (C:) window, right-click in the empty area and navigate to New > Folder. 

4.Rename the New Folder as ftpfiles. 

5.Click Start and in the start menu, scroll down and click the XAMPP dropdown arrow, and then select XAMPP Control Panel. 

6.In the XAMPP Control Panel v3.2.2 window, ensure that the Apache, MySQL, and FileZilla services are running. If they are not, click the Start button to begin these services.

7.Click the Admin button for FileZilla. 

8.The Connect to Server dialog box will appear. Click OK to close this dialog box and display the FileZilla Server window.

9.In the FileZilla Server window, go to the Edit tab and select Users to display the Users window. 

10.In the Users window, perform the following steps:

Under the Page section, click the Shared folders link. 

Under the Users section, click Add.

In the Add user account window, in the Please enter the name of the user account that should be added textbox, type administrator to add a user account named Administrator, and click OK. 

Under the Shared folders section, click the Add button. 

In the Browse for Folder window, navigate to Local Disk (C:) > ftpfiles and click OK. 

Ensure that C:\ftpfiles is selected, click the Set as home dir button to make ftpfiles as the home directory, and then click OK.

## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
