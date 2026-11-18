# WhyOff — Network Toolkit · Support

[Datenschutz auf Deutsch](de.lproj/Privacy.md) · [Privacy in English](en.lproj/Privacy.md)

## Hilfe und Kontakt

Bei Fragen zu WhyOff, Fehlern oder Funktionswünschen erreichst du uns unter [whyoff@d-r.dev](mailto:whyoff@d-r.dev).

Bitte nenne die WhyOff-Version, deine macOS-Version, das betroffene Werkzeug und die Schritte, mit denen das Problem auftritt. Zugangsdaten, private Schlüssel und Kopplungscodes benötigen wir nicht. Prüfe Berichte und Screenshots vor dem Senden auf vertrauliche Netzwerkangaben. Öffentliche GitHub-Issues sind für alle lesbar; vertrauliche Angaben gehören dort nicht hinein.

WhyOff ist die Oberfläche für das separat gestartete lokale Kommandozeilenprogramm „aOSnetTools“. Für Messungen müssen App und Programm gekoppelt sein. Eine ausbleibende Antwort allein beweist keinen Ausfall: Firewalls und die Einstellungen der Gegenstelle können Messungen begrenzen.

### WhyOff mit dem Diagnoseprogramm koppeln

Öffne im Terminal den entpackten aOSnetTools-Ordner und führe `./bin/aosnettools serve` aus. Wenn du das Programm bereits im Suchpfad installiert hast, genügt `aosnettools serve`. Lass das Terminalfenster offen. Klicke in WhyOff auf „Verbinden“ und füge den angezeigten Kopplungscode ein. Mit Ping auf `127.0.0.1` kannst du die Kopplung ohne zweite Gegenstelle prüfen.

### Den ersten kostenlosen Automatiklauf starten

1. Sobald der Kopplungsdialog die Version des verbundenen Programms zeigt, schließe ihn und wähle „Automatik“ in der Seitenleiste.
2. Gib für einen Test auf diesem Mac `localhost` ein. Wähle IPv4 und den TCP-Port des Dienstes, den du prüfen möchtest. Klicke auf „Starten“.
3. Lies die drei Ergebnisse einzeln. DNS zeigt die aufgelöste Adresse. Ping zeigt, ob eine ICMP-Antwort kam. TCP prüft, ob sich eine Verbindung zum gewählten Port öffnen lässt. Antwortet Ping und wird TCP abgelehnt, prüfe, ob der Dienst auf diesem Port läuft.

Für einen anderen Rechner trägst du dessen Namen oder IP-Adresse als Ziel ein. Ein Klick auf eine Ergebniskarte bereitet das zugehörige Einzelwerkzeug vor. Mit „Starten“ löst du dort eine eigene Messung aus.

Der Basislauf sowie Ping, DNS Lookup und Verbindungsprüfung sind kostenlos und lassen sich für diese Tests ohne Root verwenden. WhyOff Pro schaltet die weiteren GUI-Werkzeuge und Automatikprüfungen per Einmalkauf frei.

### WhyOff Pro wiederherstellen

Öffne ein Pro-Werkzeug, zum Beispiel den Subnet Calculator, und wähle „Kauf wiederherstellen“. Verwende den App-Store-Account, mit dem du WhyOff Pro gekauft hast. Nach der Freischaltung erscheint das ausgewählte Werkzeug. Die kostenlose CLI benötigt dafür keinen Kauf.

## Help and contact

For WhyOff questions, bug reports or feature requests, contact [whyoff@d-r.dev](mailto:whyoff@d-r.dev).

Include your WhyOff and macOS versions, the affected tool and the steps needed to reproduce the issue. Do not send credentials, private keys or pairing codes. Check reports and screenshots for confidential network details before sending them. GitHub issues are public; do not include confidential information in an issue.

WhyOff is the interface for the separately started local “aOSnetTools” command-line program. Pair the app and program before running measurements. A missing reply alone does not prove an outage: firewalls and endpoint settings can limit measurements.

### Pairing WhyOff with the diagnostic program

In Terminal, open the extracted aOSnetTools folder and run `./bin/aosnettools serve`. If the program is already on your shell’s search path, run `aosnettools serve`. Keep Terminal open. Choose Connect in WhyOff and paste the pairing code shown in Terminal. Run Ping against `127.0.0.1` to check the connection on this Mac.

### Running your first free Automatic check

1. Once the pairing dialog shows the connected program’s version, close the pairing dialog and choose Automatic in the sidebar.
2. To test this Mac, enter `localhost`, choose IPv4 and enter the TCP port used by the service you want to check. Click Start.
3. Read each result separately. DNS shows the resolved address. Ping shows whether an ICMP reply arrived. TCP checks whether a connection can be opened to the chosen port. If Ping succeeds and TCP is refused, check whether the service is listening on that port.

To test another computer, enter its name or IP address. Clicking a result card prepares the corresponding tool. Click Start there to run a separate measurement.

The basic run, Ping, DNS Lookup and Connection Check are free and can run these checks without root privileges. A one-time WhyOff Pro purchase unlocks the remaining GUI tools and additional automatic checks.

### Restoring WhyOff Pro

Open a Pro tool such as Subnet Calculator and choose “Restore Purchase”. Use the App Store account you used to buy WhyOff Pro. Once the purchase is restored, the selected tool appears. The standalone CLI is free to use.

## Anbieter / Provider

DR Development and Media LLC  
Vazha Pshavela Avenue No 20  
0112 Tbilisi, Georgia  
Dimitri Roschkowski  
Telephone: +49 721 8316699  
Email: [whyoff@d-r.dev](mailto:whyoff@d-r.dev)

© 2026 DR Development and Media LLC
