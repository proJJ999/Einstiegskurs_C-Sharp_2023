# Visual Studio Setup macOS

## Installation

Gehe auf die Internetseite von Visual Studio: https://visualstudio.microsoft.com/de/ 

![alt text](./Setup_Mac_Images/macinstall_1.png)

Lade den Installer für Visual Studio für Mac Os runter. 

![alt text](./Setup_Mac_Images/macinstall_2.png)

Beim installieren wähle mindestens die Option Core .Net aus.





## Projekterstellung

Wenn du die Installation abgeschlossen hast, starte Visual Studio. Um eine neues Projekt zu erstellen, drücke auf das lila Plussymbol auf der rechten Seite.


![alt text](./Setup_Mac_Images/ProjectErstellungmacOS.png)

Bei der Auswahl des Templates, wähle links unter dem Reiter "Web and Console" den Punkt "App". Wähle rechts unter "General" "Console Application" und im DropDown Menu "C#" aus. 

![alt text](./Setup_Mac_Images/ConsoleApplicationMACOS.png)


Wähle unter Target framework ".Net 6.0" aus.

![alt text](./Setup_Mac_Images/Net60Macos.png)

Ändere den Namen des Projektes zu "MeinErstesCSProjekt".

![alt text](./Setup_Mac_Images/PorjectErstellung2MacOS.png)

Du hast deine Programmierumgebung geöffnet. Links siehst du die Ordnerstruktur deines Projekts. Bis jetzt gibt es nur ein paar Ordner und eine Datei, die "Program.cs" heißt. Diese Datei ist auf der rechten Seite gerade geöffnet. Bis jetzt steht im Programm folgendes:

```cs
// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, World!");
```

![alt text](./Setup_Mac_Images/ErstesProjectMacOS.png)

Ändere in Zeile 2. den Text "Hello, World!" zu "Dies ist mein erstes C# Project!".
```cs
Console.WriteLine("Dies ist mein erstes C# Project!");
```
Nach einem Linksklick auf den schwarzen Playbutton oben links wird "Dies ist mein erstes C# Project!" unten in der Konsole ausgegeben.

![alt text](./Setup_Mac_Images/TerminalAusgabeMacOS.png)

Gratulation, du hast dein erstes C# Programm ausgeführt!
