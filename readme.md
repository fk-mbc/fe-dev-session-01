# Session 1

## Software installieren
Es ist notwending, dass für die erste Session gewisse Programme und Softwareumgebungen installiert
sind. Bitte installiere folgende Programme auf deinem Arbeitsrechner für diesen Kurs (am besten in der Reihenfolge):

**Java**
- [Java SE Development Kit 8u101](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) (Achtet bei der Auswahl auf euer Betriebssystem!)

**Server**
- [WAMP Server](http://www.wampserver.com/en/#download-wrapper) (Bitte in den Hauptpfad installieren C: oder D:)

**Editoren/IDE**
- [Netbeans - Version für "HTML/JavaScript"](https://netbeans.org/downloads/index.html)
- [Visual Studio Code](https://code.visualstudio.com/)

*(solltet ihr bereits eine IDE verwenden, wie z. B. Webstorm oder GitHubs ATOM, so könnt ihr auch diese verwenden.)*

**Software**
- [NodeJs 4.4.7 LTS](https://nodejs.org/en/)
- [git](https://git-scm.com/)

Nachdem du die oben genannten Programme installiert hast. Öffneat Du bitte ein Eingabeaufforderungs-Fenster (Windows)
/ Terminal-Fenster (OS X). Hier checkst du als erstes ob NodeJs und git korrekt installiert sind.

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
Um die Arbeitsdateien aus diesem Ordner für dich lokal abzuspeichern, hast du die Möglichkeit diese entweder runterzuladen oder
auf die elegantere Art, sie mit git zu *clonen*. Im Endeffekt wird dadruch eine Kopie diese Repositories auf deinem Rechner gespeichert.
Was man mit Git noch alles machen kann, folgt in einer späteren Session.

Erstelle dir auf deiner Festplatte einen Ordner für die Übungen (Name könnte z. B. *development-sessions* sein). Solltest du nur
über ein Laufwerk verfügen, so nutze deinen persönlichen Ordner um dort den neuen Ordner zu erstellen. Habt ihr ein weiteres
Laufwerk (oder Partition) welches nicht nur zur Sicherung eures Betriebssystems dient, also größer oder gleich groß wie euer
Laufwerk C ist, dann nutzt diese. Egal welche Wahl für dich die bessere war, geh in den Ordner den du erstellt habst. Öffne
hier ein Terminal Fenster (Eingabeaufforderung). Alternativ navigiere mit dem noch offenen Terminal dort hin
(z. B. cd D:\development-sessions). Führe dort den folgenden Befehl aus:

```shell
git clone https://github.com/fk-mbc/fe-dev-session-01.git
```

Sollte alles funktioniert haben, so wirst du in dem Ordner einen neuen Ordner names "fe-dev-session-01" finden.

Wechsele in diese Ordner und führe die "start.bat" aus. Anschließend ruft du im Browser deiner Wahl http://localhost:8888/ auf.
