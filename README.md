KendaliPintuAndroid
====================
### Dimas Rullyan Danu (dimasdanz@gmail.com)

KendaliPintuAndroid is an Android Application as a **controller/notification receiver/and many more** of an Arduino based and connected to Arduino via Web Server.

This is an Android Application of my College Final Project.

The web part is [here] (https://github.com/Dimasdanz/KendaliPintuWeb)  
The Arduino part is [here] (https://github.com/Dimasdanz/KendaliPintuArduino)

This repository is only intended as a backup from my computer.  
I will NOT answer any question regading of this app.

##  Description
Door Control is an Arduino based hardware controlled by a web and an Android Application.  
This hardware is used to control a door, and authorize people and record every user who uses the door.  
The Arduino can be enabled/disabled via Android and Web.  
Door can be opened by tapping an NFC-Enabled Android device to a specific nfc tag.  
There is also a keypad on the hardware for manual password input.  
Every log such as enabling/disabling, people enter or exit will be recorded and will send a notification to Android device.  
To use the Android app, you need to login as user which stored in the database.  
To enable all function of the Android app, you need to login as admin which also stored in the database.  
CRUD operation of user and admin is done via the web.

## License
Copyright (C) 2014 Dimas Rullyan Danu

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
