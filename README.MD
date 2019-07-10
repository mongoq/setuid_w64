# Mifare Card UID (Windows)

Lesen und Setzen von Mifare-Karten UIDs (4 Bytes) mit **USB-NFC-Interface ACR122U** unter Windows 7

Zusammengestellt von http://nfc-tools.org

![ACR122U](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZ3LIqSONXUmsjX91ytZOBTPmT7ahA_39kds4XQ4eEChJEk7yGCA)

**--> Auf der Kommandozeile sind die .exe Dateien in /temp (ohne GUI) bereits einsetzbar! <--**

Todo: GUI-Frontend mit Python / GTK (bisher nur Materialsammlung (!)):
* Python GUI mit GTK / Nullsoft Installer / Zadig automatische Treiberauswahl !!?
* http://www.yolinux.com/TUTORIALS/PyGTK.html (unter Windows?)
* https://m.youtube.com/watch?v=MxYl3cnn4yw
* https://stackoverflow.com/questions/25381761/creating-an-installer-for-a-python-gtk3-application
* https://stackoverflow.com/questions/23272184/how-do-you-search-subprocess-output-in-python-for-a-specific-word
* https://stackoverflow.com/questions/6780035/how-to-run-ps-cax-grep-something-in-python
* https://ubuntuforums.org/showthread.php?t=2074290
* http://python-gtk-3-tutorial.readthedocs.io/en/latest/index.html
* http://www.linux-magazin.de/ausgaben/2011/11/gtk/

* PyGTK Installation Windows 7: https://im-coder.com/python-pygtk-windows-7-64-bit.html (es gibt PyGTK nicht für Python 3!)

* Packaging mit py2exe: TODO

Doku durch nochmaliges Zusammenkopieren von Folgendem zusammenstellen:
* https://zadig.akeo.ie/ (Treiberauswahl)
* https://github.com/peacepenguin/libnfc-unofficialbuilds (nfc-list.exe und nfc-mfsetuid.exe)
* Todo: libnfc.dll (woher?)
* Todo: libusb0.dll (woher?)
* Todo: Windows 10 Test

Zadig (Treiberauswahl):
* Treiber für ACR122U PICC Interface umstellen auf libusbK (evtl. nach jedem Windows-Neustart erforderlich!)
* Danach USB-Stecker des ACR122U herausziehen / hineinstecken

Beispieleinsatz (Dateien in /temp): 
* Ändern von UID **"ab cd ef ef"** auf **"21 22 23 24"** (reicht für Zugangskontrollsysteme aus)

![Alt text](https://github.com/mongoq/wsetuid/blob/master/temp/example_use.png?raw=true "Usage")
 
 Lizenzen: **?!?!**
