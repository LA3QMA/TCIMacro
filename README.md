# TCIMacro
Linux TCI Macro for Expert SDR rigs

Based on https://iw7dmh.jimdofree.com/sunsdr2-pro-pages/tci-macro/

![Alt text](/screenshot/MainMenu.png?raw=true "MainMenu")

* Download and extract
* Run "sudo make install" to install the application or move the "TCIMacro" to where ever you want it.
* ExpertSDR has to be running
* Start TCIMacro - by default it tries localhost:40001
* First time usage select "Prefs" and enter your configuration details.
* After "Submit" the applications quits and you have to start it again.

* In CW mode click the macro button to send.
* To change the WPM, enter value and then click "WPM"
* To stop the macro click "QRT"
* To send free text: type some text in the field and click "TX"

* If you want a light theme start the program like this: FYNE_THEME=light ./TCIMacro

Changelog:

0.0.3
CW characters like colon [:], semicolon [;] and comma [,] are translated to correct TCI commands.

WPM command bug fixed.
