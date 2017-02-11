                                KMSmicro v4.0.WO 
 Local KMS activation server for Windows 7, Windows 8 Professional and Enterprise, 
                          Office 2010, Office 2013. 

 System requirements: Any PC/x86 compatiable PC (works even inside virtual machine), 
 200 MB on HDD, 350 MB RAM, a keyboard, a mouse optionally, also runs from USB flash drive. 

 Windows Activation: 
 1.Run "Start-KMSmicro-WO.vbs", waiting for the server to load. If for any reason the server won`t start, 
   try to run "KMSdebug.cmd" in qemu folder to start it. 
 2.Set your time zone, by pressing "Z". 
 3.Run as Administrator "Activation Helper .exe" to activate Windows. 
   That`s it!, the system activated for 180 days. 

 Office 2010-2013 Activation: 
   Since v3.00 KMSmicro has an Office 2010-2013 activation server built in. 
   Read "Office 2010&2013 Install & Activate.txt" for details. 

 Activation may fail for the following reasons : 

 1. Wrong product key installed or not installed at all. 
 2. The KMS Server Client Count value is insufficient to activate a system 
    (the counter is not "boosted"). 
    Execute the Server menu option: "Increasing KMS Server Client Count" 
 3. Port 1688 is used by another application, so that The Server can`t connect a PC, 
    Uninstall all previous "activators" and "cracks" for Office 2010&2013. 
 4. Your time zone differs from the Server`s one. 
    Set the server`s time zone or set on your PC UTC+7 time zone. 
 5. Our KMSmicro v3.12 is incompatiable with your PC. 
    Such a thing never happened before, so you are extremly unlucky person  
 6. Somethig utterly unpredictable happened, beyond the scope of this FAQ. 

 The Server operation basic instructions: 
   "T" - Time syncronization via the internet. 
   "H" - Displays a Windows server activation status. 
  "10" - Displays an Office 2010 server activation status . 
  "13" - Displays an Office 2013 server activation status . 
   "Z" - Sets a time zone and current time. 
   "C" - The Server Client Count "boosting". 
   "S" - The Server shutdown. 

 Ctrl+Alt+U - Alignes the server`s window, if you changed it by mouse. 
 Ctrl+Alt - Toggles cursor: server`s window / system. 

 Advice: All instructions can be executed with a keyboard without a mouse . 

                                   ------------------- 

 KMS Server IP 127.0.0.1-2, port 1688. The Server access the internet to syncronize time. 


                                   ------------------- 

 After a first version release, a lot of clones with alternative system and script files can be found in the internet. 
    Beware of fake ones. If something will go wrong after using them , I`m, Ratiborus, not guilty.  
                                   ------------------- 
 New scripts, last builds, and dicussion can be found at forum.ru-board.com, new scripts also at MDL forum. 
                                   ------------------- 
 Send my regards: "Evgeny972", "DM", "Hybernaculum", "vincome" from forum.ru-board.com., heldigard, 
    ColdZero, s1ave77, CODYQX4 from MDL forum. You are engaged in captivating work, the results of 
    which I use in my developments. 

 Changelog v4.0.WO: 
    + - Changed time zone settings menu. 
    + - Count "boosting" added. 
    + - Some subtle changes 