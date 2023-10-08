# Pangya Suite Tools Configuration
 
 Application usage tutorial

- [Configuration](#appconfig)
- [Login](#applogin)
- [Menu](#appmenu)
- [Icon](#appshowicons)
### AppConfig

Question: I can't access the app, what should I do?

Response:

look for this file: 'Pang Modern Tools.exe.config'

open with a normal text editor

edit the following parameters (if necessary)

  DataSource=127.0.0.1,1433;
  
  Initial Catalog=pangya;
  
  Network Library = DBMSSOCN;
  
  UserID=sa;
  
  Password=84872060


save and then try to run the application. If successful, the application continues to run
### AppLogin

Question: I'm stuck at the login part, what should I do?

Response:
Here you must enter your account

Access is only allowed if it is a GM account (capability = 4)

![login](https://cdn.discordapp.com/attachments/774375484498640907/1160260914747031612/image.png?ex=6534042e&is=65218f2e&hm=2c82f8e28b64a0b5457515ab14e5caa651cc7e79e51c53277dcd6338d484d246&)

Click on 'ok' if you have filled in the necessary data in the fields
 and if you have not connected to an internet network, you cannot connect to the application
### AppMenu

see this simple menu

![menu](https://cdn.discordapp.com/attachments/774375484498640907/1160261049925242920/image.png?ex=6534044e&is=65218f4e&hm=882b3d2ec334f970a545a30800a800cce873de00f0efe86fac75aedd19c7405d&)

Language.dat = you edit the client's *.dat file

Image.tga = you can view/save the game's *.tga files

Caddy.Talk = you edit the client's *.Talk file

ShitList.bin = you edit the client's *.bin file (prohibit words in the game)

IFF Editor = you edit the client's *.iff file

GM Tools = Tool to manage the acrisio super ss dev server

Gen TypeID = IFF TypeID Generator (next version will disappear)

About App = About the app, creators and contributors


### AppShowIcons


![icons](https://cdn.discordapp.com/attachments/774375484498640907/1152356744853471294/image.png?ex=6532f259&is=65207d59&hm=ed04c7c382026e30bc8d6cbb14154b62c64359750fdee9c333bb7afaa0872790&) 


Question: How do I see item icons?

Answer: Download the 'Images.rar' file in the main part of the project

extract the folder and place it next to the Application
It is not necessary to restart the application for the icons to appear in the IFF Editor
