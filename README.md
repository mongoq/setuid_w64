# w64_setuid
Setzen von Mifare-Karten UIDs (4 Bytes) mit NFC-Interface ACR122U unter Windows

**Auf der Kommandozeile sind die .exe Dateien in /temp (*ohne GUI*) schon einsetzbar (!)**

GUI-Frontend mit Python / GTK (Todo - hier läuft noch nichts (!)):
* GTK / NSIS / Zadig Treiberauswahl !!?

Doku für Nochmaliges Zusammenkopieren von folgendem zusammenstellen:
* https://zadig.akeo.ie/
* https://github.com/peacepenguin/libnfc-unofficialbuilds - nfc-list.exe und nfc-mfsetuid.exe
* Todo: libnfc.dll (woher?)
* Todo: libusb0.dll (woher?)

Zadig:
* Treiber für ACR122U PICC Interface umstellen auf libusbK (zwingend erfordelich!). 
* Danach USB-Stecker des ACR122U rausziehen / reinstecken.

Beispieleinsatz (Dateien in /temp): 
* Ändern von UID **"ab cd ef ef"** auf **"21 22 23 24"** (nur diese 4 Bytes werden meist ausgewertet)

![Alt text](https://github.com/mongoq/wsetuid/blob/master/temp/example_use.png?raw=true "Usage")
 
 Lizenzen: **?!?!**
