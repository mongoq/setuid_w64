# wsetuid
Setzen von Mifare UID (Windows) mit NFC-Interface ACR122U

Frontend mit Python / GTK (Todo - hier läuft noch nichts(!))
* GTK / NSIS / Zadig Treiberauswahl !!?

Doku - Zusammenkopieren von folgendem:
* https://zadig.akeo.ie/ - setzen von Treiber (Todo_welcher?)
* https://github.com/peacepenguin/libnfc-unofficialbuilds - nfc-list.exe und nfc-mfsetuid.exe
* Todo: libnfc.dll (woher?)
* Todo: libusb0.dll (woher?)

Bei Zadig:
* Treiber für ACR122U PICC Interface umstellen auf libusbK. 
* Danach USB-Stecker rausziehen/reinstecken.

Beispielnutzung:

![Alt text](https://github.com/mongoq/wsetuid/blob/master/temp/example_use.png?raw=true "Usage")
