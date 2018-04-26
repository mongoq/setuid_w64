# setuid_w64
Lesen und Setzen von Mifare-Karten UIDs (4 Bytes) mit NFC-Interface **ACR122U** unter Windows 7

Zusammengestellt von http://nfc-tools.org

![ACR122U](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZ3LIqSONXUmsjX91ytZOBTPmT7ahA_39kds4XQ4eEChJEk7yGCA)

**--> Auf der Kommandozeile sind die .exe Dateien in /temp (ohne GUI) bereits einsetzbar! <--**

Todo: GUI-Frontend mit Python / GTK (bisher nur Materialsammlung (!)):
* Python GUI mit GTK / Nullsoft Installer / Zadig automatische Treiberauswahl !!?
* http://www.yolinux.com/TUTORIALS/PyGTK.html (unter Windows?)

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
