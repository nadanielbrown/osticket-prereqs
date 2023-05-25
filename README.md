<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com/watch?v=dEvGaxOgqf0&t=18s)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Rewrite Module
- osTicket
- PHP Manager for IIS
- MySQL 5.5.62

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS)
- Installing Web Platform
- Installing MySQL & Set Up Username/Password
- Installing C++ Redistributable 
- Configure permission and installing OsTickets

<h2>Installation Steps</h2>

Create a Resource Group

<img src="https://i.imgur.com/bSD9nsZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Create

<img src="https://i.imgur.com/mV6PtRv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Name the Resource Group (ex: RG-01)

<img src="https://i.imgur.com/bELXke4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

For the Region use (US) East US

<img src="https://i.imgur.com/bELXke4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Next:Tags >

<img src="https://i.imgur.com/ZBdCivx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Next: Review + create

<img src="https://i.imgur.com/lDLtzaO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

After Validation passed. Click create

<img src="https://i.imgur.com/NeUudNQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Next objective is to create a Virtual machine

Click the Home link in the upper left corner

<img src="https://i.imgur.com/HprxhIH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Virtual machines

<img src="https://i.imgur.com/ZhTOazm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click on Azure Virtual machine

<img src="https://i.imgur.com/nVwmK1S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Select your Resource Group (ex: RG-01) and name your Virtual machine 

<img src="https://i.imgur.com/WMhRWYG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Use Windows 10 Pro

<img src="https://i.imgur.com/hSFw4uW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go to Administrator account. Type in a Username and Password.

<img src="https://i.imgur.com/QGFavuv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Check the Licensing box and then click Next : Disk

<img src="https://i.imgur.com/4B7unkn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Next : Management 

<img src="https://i.imgur.com/VckEEl7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Review + create

<img src="https://i.imgur.cAom/VckEEl7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

After Validation has passed. Click Create

<img src="https://i.imgur.com/4g1Ukbm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

After Vitural machine has been created, click inside of your tool bar and go to Virtal machines

<img src="https://i.imgur.com/cNhNacn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click the Virtual machine (ex: VM-01)

<img src="https://i.imgur.com/AJA35Un.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Copy Virtual machine Public IP address

<img src="https://i.imgur.com/5mBiyZq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go to Start Menu and type in Remote Desktop Connection

<img src="https://i.imgur.com/e9AvtUk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Paste the IP Address and click Connect

<img src="https://i.imgur.com/7V8Y0qJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Hit More Choices and then click Us a different User

<img src="https://i.imgur.com/tGw5Gi1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Type in your Username and Password that was created and then hit OK

<img src="https://i.imgur.com/enGmedL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Choose "NO" for all of the settings then hit Accept

<img src="https://i.imgur.com/eCtdua4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Open Microsoft Edge

<img src="https://i.imgur.com/H7Bil3T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Select Start without your data 

<img src="https://i.imgur.com/jGWhRpB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Continue without this data

<img src="https://i.imgur.com/58678ZK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Select Confirm and start browsing

<img src="https://i.imgur.com/F4rQViE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Copy osTicket Installation Files and paste inside of browser:
https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6

<img src="https://i.imgur.com/8Xww8Xy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go to Start Menu and enter lookup Control Panel 

<img src="https://i.imgur.com/A6fnrsK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Next go to Programs

<img src="https://i.imgur.com/Ezk5VnF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Turn Windows features on or off

<img src="https://i.imgur.com/K6X98PC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click on Information System Security

<img src="https://i.imgur.com/jCqBCej.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click on Worldwide Web Services, Applicaton Development Features and CGI and click OK

<img src="https://i.imgur.com/m1u15s6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Hit CLosed

<img src="https://i.imgur.com/mTDN1gc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Download PHPManagerForllS

<img src="https://i.imgur.com/udWK6i9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Right CLick on Download to open it up 

<img src="https://i.imgur.com/ipgaWtC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click DOWNLOAD ANYWAY

<img src="https://i.imgur.com/di48t8K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Cancel

<img src="https://i.imgur.com/di48t8K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go to File 

<img src="https://i.imgur.com/oVI8hZP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Downloads

<img src="https://i.imgur.com/hIBqoMl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Double click on PHPManager so that it begins to RUN

<img src="https://imgur.com/a/I7S2sno" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Next

<img src="https://i.imgur.com/5m6i0nu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Select Agree and then Click Next

<img src="https://i.imgur.com/5m6i0nu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Close

<img src="https://i.imgur.com/Q4SlAIk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Download rewrite_amd64

<img src="https://i.imgur.com/V5MnDey.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Downlaod Anyway

<img src="https://i.imgur.com/tqGurVS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Double Click on rewrite_amd64

<img src="https://i.imgur.com/liqLsrs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Install Rewrite Module
Check the box: I accept the terms of te License Agreement and hit Install

<img src="https://i.imgur.com/B6UABsU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Finish

<img src="https://i.imgur.com/ACCodAw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Download all

<img src="https://i.imgur.com/RH1qqma.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go to File 

<img src="https://i.imgur.com/oVI8hZP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
Right Click on Installation Files and click Extract ALl

<img src="https://i.imgur.com/DtD6M6Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Extract

<img src="https://i.imgur.com/e1t0FPo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Double Click on Installation Files

<img src="https://i.imgur.com/brFe6zy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Copy the files in Installation Folder 

<img src="https://i.imgur.com/OUMsc7K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go back to Downloads

<img src="https://i.imgur.com/vHxYxW5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Delete all Folders except Installation Files

<img src="https://i.imgur.com/YcI6NSu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/iynCLqX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Exit out of Control Panel 

<img src="https://i.imgur.com/rjA6457.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Create a New Folder named PHP
Go to This PC. Double click on Windows (C:) 

<img src="https://i.imgur.com/4xtrnjA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Right click, go to New and select Folder and name it php 7.3 

<img src="https://i.imgur.com/Tg70Wl2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go to Downloads, double click Installation, then double click Installation again, then Right click on php-7.3.8 Compressed (zipped)

<img src="https://i.imgur.com/wkU2Lmx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Hit Browse

<img src="https://i.imgur.com/Gof4YGc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click This PC, next click Windows C, then click PHP Folder, Select Folder, then Hit Extract. Your screen should end up looking like this. 

<img src="https://i.imgur.com/9Tx2PNw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Installing Microsoft Visual C++
Click on Downloads, double click on Installation, then double click Installation, double click on VC__redist.x86, check "I agree to the license terms and conditions, click Install

<img src="https://i.imgur.com/TS3qh6A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click close

<img src="https://i.imgur.com/dItRJ5c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Install MySQL
Right click on mysql-5.5.62-win

<img src="https://i.imgur.com/ZOdql38.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Next, check the box "I agree the terms in the License Agreement, click Next, 

<img src="https://i.imgur.com/ZOdql38.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Choose Typical, click Install

<img src=https://i.imgur.com/Q9eK6aF.png"" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Finish, click Next, 

<img src="https://i.imgur.com/dPqoBMl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Select Standard Configuration, click Next

<img src="https://i.imgur.com/2cHUoZy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Create a Password (ex:Password1), click Next, click Execute, click Finish

<img src="https://i.imgur.com/2l1sJ8K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Open Internet Information Services (ISS)
Go to Start Menu inside of Remote Desktop and type in IIS, right click and select "Run as administrator 

<img src="https://i.imgur.com/fuGjZ6j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click on PHP Manager

<img src="https://i.imgur.com/aLgXhgQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Register New PHP verison

<img src="https://i.imgur.com/bMpXeDr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click on box

<img src="https://i.imgur.com/mmT4ybd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Double click on PHP folder, double click on php-cgi, click OK,

<img src="https://i.imgur.com/ioyHixO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go back to the home page by clicking on VM-01 

<img src="https://i.imgur.com/DZUmA6K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Restart 

<img src="https://i.imgur.com/Nihl5mU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go to your folder, click on Download, double click on Installation, double click Installation again, 

<img src="https://imgur.com/a/I7S2sno" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Right click osTickect-v1.15.8, go to Extract All, click Extract, 

<img src="https://i.imgur.com/ALMqPKX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Relocate "upload Folder"
Go to "This PC", go to Windows (C:), double click "inetpub", double click "wwwwroot"

<img src="https://i.imgur.com/DJZw1Ml.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Drag "upload" folder to "wwwroot"

<img src="https://i.imgur.com/jejgPmc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Rename "upload" folder to "osTicket"
<img src="https://i.imgur.com/cBxhzQP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go back to  and click Restart

<img src="https://i.imgur.com/sHAoxM9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Sites, then click Defult Web Site, click Browse *.80 (http)

<img src="https://i.imgur.com/aYQZu5C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

You should get a screen that looks like this 

<img src="https://i.imgur.com/CVBQNHi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go back to Internet Information Services (IIS) Manager, click VMOST, click PHP Manager

<img src="https://i.imgur.com/qvhPvbc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click Enable or disable an extension

<img src="https://i.imgur.com/7YIe6A9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Click on php_imap.dll and then click Enable, then click on php_opache.dll and click Enable, next php_intl.dll and click Enable

<img src="https://i.imgur.com/vUKxClI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Go back to Internet Information Services (IIS) Manager

<img src="https://i.imgur.com/qvhPvbc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
