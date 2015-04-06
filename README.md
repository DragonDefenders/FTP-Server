# FTP-Server

Open Server Manager 
Add Roles and Feature

Server Roles > Web Server (IIS) >> FTP Server >> FTP Extensibility/Service > Restart automatically>> Close

Tools > Internet Information Services > Sever1 >Sites > Right Click> Add FTP Site > Choose Specific Path >FTP Folder 

IP ADDRESS PORT 21

FTP > SSL or no SSL > 

Authentication > Basic > Allow access to specified users > add that specific users > click fnish. 

Select FTP website that we created. 

Check IP address of the server 

Windows Firewall > Advanced Settings > Inbound Rules > FTP Server turn on port 21 

Client Machine > filezilla > File > Site Manager > New Site >Name site as FTP on  > Host : IP ADDRESS of SERVER > port: 21 by default so do not need to change > Logon Type: Ask for password > user (user that needs access) > Trasnfer Settings > Defaut > 

If Error Open Site > Transfer Settings > Active Mode >passive mode is blocked by default on the firewall. 
