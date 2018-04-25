# setuid_w64
Setzen von Mifare-Karten UIDs (4 Bytes) mit NFC-Interface ACR122U unter Windows

Zusammengestellt von bzw. für http://nfc-tools.org

**Auf der Kommandozeile sind die .exe Dateien in /temp (*ohne GUI*) ohne weiteres einsetzbar (!)**

GUI-Frontend mit Python / GTK (Todo - hier läuft noch nichts (!)):
* Python GUI mit GTK / Nullsoft Installer / Zadig automatische Treiberauswahl !!?

Doku für Nochmaliges Zusammenkopieren von folgendem zusammenstellen:
* https://zadig.akeo.ie/ (Treiberauswahl)
* https://github.com/peacepenguin/libnfc-unofficialbuilds (nfc-list.exe und nfc-mfsetuid.exe)
* Todo: libnfc.dll (woher?)
* Todo: libusb0.dll (woher?)

Zadig (Treiberauswahl):
* Treiber für ACR122U PICC Interface umstellen auf libusbK (zwingend erfordelich!)
* Danach USB-Stecker des ACR122U herausziehen / hineinstecken

Beispieleinsatz (Dateien in /temp): 
* Ändern von UID **"ab cd ef ef"** auf **"21 22 23 24"** (nur diese 4 Bytes werden meist ausgewertet)

![Alt text](https://github.com/mongoq/wsetuid/blob/master/temp/example_use.png?raw=true "Usage")
 
 Lizenzen: **?!?!**
