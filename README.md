# w32_setuid
Setzen von Mifare-Karten UIDs mit NFC-Interface ACR122U unter Windows

**Auf der Kommandozeile sind die Programme in /temp ohne GUI bereits einsetzbar (!)**

GUI-Frontend mit Python / GTK (Todo - hier läuft noch nichts (!)):
* GTK / NSIS / Zadig Treiberauswahl !!?

Doku - Zusammenkopieren von folgendem:
* https://zadig.akeo.ie/
* https://github.com/peacepenguin/libnfc-unofficialbuilds - nfc-list.exe und nfc-mfsetuid.exe
* Todo: libnfc.dll (woher?)
* Todo: libusb0.dll (woher?)

Bei Zadig:
* Treiber für ACR122U PICC Interface umstellen auf libusbK (zwingend erfordelich!). 
* Danach USB-Stecker des ACR122U rausziehen / reinstecken.

Beispielnutzung (Dateien in /temp):

![Alt text](https://github.com/mongoq/wsetuid/blob/master/temp/example_use.png?raw=true "Usage")
 
 Lizenzen: ?!?!
