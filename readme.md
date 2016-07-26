# Session 1

## Software installieren
Es ist notwending, dass für die erste Session gewisse Programme und Softwareumgebungen installiert 
sind. Bitte folgende Programme auf eurem Arbeitsrechner für den Kurs (am besten in der Reihenfolge) installieren:

**Java**
- [Java SE Development Kit 8u101](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) (Achtet bei der Auswahl auf euer Betriebssystem!)

**Editoren/IDE**
- [Netbeans - Version für "HTML/JavaScript"](https://netbeans.org/downloads/index.html)
- [Visual Studio Code](https://code.visualstudio.com/)

*(solltet ihr bereits eine IDE verwenden, wie z. B. Webstorm oder GitHubs ATOM, so könnt ihr auch diese verwenden.)*

**Software**
- [NodeJs 4.4.7 LTS](https://nodejs.org/en/)
- [git](https://git-scm.com/)

Nachdem ihr die oben genannten Programme installiert habt. Öffnet ihr bitte ein Eingabeaufforderungs-Fenster (Windows) 
/ Terminal-Fenster (OS X). Hier checked ihr als erstes ob NodeJs und git korrekt installiert sind.

```shell
git --version
```
Sollte etwas wie `git version 2.9.2.windows.1` ausgeben. (Versionsnummer kann je nach installierten Version variieren)

```shell
node --version
```
Sollte etwas wie `v4.4.7` ausgeben.

```shell
npm --version
```
Sollte etwas wie `3.9.2` ausgeben.

**Plugins**

Grunt installieren mit

```shell
npm install -g grunt-cli
```

Bower installieren mit

```shell
npm install -g bower
```

## Repository clonen (also das Ding hier)
Um die Arbeitsdateien aus diesem Ordner für euch lokal abzuspeichern, habt ihr die Möglichkeit es entweder runterzuladen oder 
auf die elegantere Art, es mit git zu clonen. Im Endeffekt wird dadruch eine Kopie diese Repositories auf eurem Rechner gespeichert.
Was man mit Git noch alles machen kann, folgt in einer späteren Session.

Erstellt euch auf eurer Festplatte einen Ordner für die Übung (Name könnte z. B. *development-sessions* sein). Solltet ihr nur über ein Laufwerk 
verfügen so nutzt euren persönlichen Ordner. Habt ihr ein weiteres Laufwerk (oder Partition) welches nicht nur zur Sicherung 
eures Betriebssystems dient, also größer oder gleich groß wie euer Laufwerk C ist, dann nutzt diese. Egal welche Wahl für euch 
die bessere war, geht in den Ordner den ihr erstellt habt. Öffnet hier ein Terminal Fenster (Eingabeaufforderung). Alternativ
navigiert mit dem noch offenen Terminal dort hin (z. B. cd D:\development-sessions). Führt dort den folgenden Befehl aus:

```shell
git clone https://github.com/fk-mbc/fe-dev-session-01.git
```