# Lernportfolio Netzwerktechnik

## 13.05.2025 - Ethernetverkabelung

Heute haben wir Ethernetverkabelung angeschaut. Wir haben gelernt, wie die Uebertragung von Daten in einem Ethernet-Netzwerk funktioniert. Besonders wichtig war der Unterschied zwischen einem logischen und einem physikalischen Aufbau. Wir haben den OSI-Modellbezug besprochen und dass Ethernet auf Schicht 1 und 2 arbeitet.

Es ging auch um die verschiedenen Topologien, z. B. Stern-Topologie und Bus-Topologie. Und wir haben gelernt, was ein Ethernet-Frame ist und was drin ist: Ziel-MAC, Quell-MAC, Typ, Daten und CRC.

**Was habe ich gelernt?**

* Ethernet ist ein Zugriffsverfahren auf ein gemeinsames Medium
* Unterschied zwischen MAC-Adresse und IP-Adresse
* Wie ein Ethernet-Frame aufgebaut ist
* Was eine MAC-Adresse ist und warum sie wichtig ist

**Was fand ich schwierig?**

* Die Vorstellung, wie viele Datenpakete gleichzeitig uebers Kabel gehen und wie das geregelt wird

---

## 20.05.2025 - Netzwerkadressierung

Heute haben wir mit IP-Adressen gearbeitet. Wir haben gelernt, dass es sich dabei um eine logische Adresse handelt und dass sie nicht fest im Geraet eingebaut ist, sondern konfiguriert wird.

Wir haben das IPv4-Format angeschaut (z. B. 192.168.0.1) und die Idee von Netz-ID und Host-ID verstanden. Dazu kamen noch Subnetzmasken wie 255.255.255.0.

**Was habe ich gelernt?**

* IPv4-Adresse besteht aus Netz-ID und Host-ID
* Subnetzmaske zeigt, wo Netz-ID aufhoert und Host-ID anfaengt
* Private IP-Adressen (z. B. 192.168.x.x) darf man im Heimnetzwerk verwenden

**Was war schwierig?**

* Zu verstehen, wie genau die Subnetzmaske mit der IP-Adresse zusammenspielt

---

## 27.05.2025 - Netzwerkadressierung 2

Heute ging es weiter mit IP-Adressen, aber etwas tiefer. Wir haben das Konzept von Subnetting angeschaut. Also wie man ein Netzwerk in kleinere Teilnetze aufteilt. Dazu braucht man etwas Mathe: Anzahl moeglicher Hosts berechnen, Binaerzahlen usw.

Wir haben auch Broadcast- und Netzadressen berechnet und gelernt, wie Routing im Zusammenhang mit IP-Adressen funktioniert.

**Was habe ich gelernt?**

* Subnetting: Aufteilung eines Netzwerks in kleinere
* Wie man Netzadresse, Hostbereich und Broadcastadresse findet
* Warum Routing notwendig ist, wenn man in andere Netze will

**Was war tricky?**

* Umrechnen von IP und Subnetzmaske in Binaer, da muss man echt ueben

---

## 10.06.2025 - Dateizugriffsrechte

Heute haben wir die Rechteverwaltung bei Windows angeschaut. Es ging darum, wie man im Explorer oder in den Eigenschaften von Dateien und Ordnern einstellen kann, welche Benutzer was machen duerfen. Wir haben z. B. angeschaut, wie man Leserechte, Schreibrechte oder Vollzugriff vergibt.

Wir haben gelernt, dass es Benutzer und Gruppen gibt, und dass man Berechtigungen gezielt setzen kann – auch fuer mehrere Dateien oder Ordner gleichzeitig.

**Was habe ich gelernt?**

* Was NTFS-Rechte sind
* Unterschied zwischen Lesen, Schreiben und Vollzugriff
* Wie man Berechtigungen im Explorer anpasst

**Was war neu?**

* Dass man fuer jeden Benutzer oder jede Gruppe eigene Rechte setzen kann
* Dass es Vererbung von Rechten gibt

---

## 24.06.2025 - Zusatzthemen

Heute war der letzte Kurstag und wir haben Zusatzthemen angeschaut. Es ging um verschiedene Netzwerkdienste wie DHCP, DNS, NAT und Protokolle wie TCP und UDP. Wir haben auch einen Vergleich gemacht zwischen Client- und Serverbetrieb.

Wir haben gelernt, dass DHCP z. B. automatisch IP-Adressen vergibt. DNS wandelt Namen wie google.ch in IP-Adressen um. Und NAT hilft, viele interne Geraete mit einer oeffentlichen IP ins Internet zu schicken.

**Was habe ich gelernt?**

* Unterschied TCP (zuverlaessig) vs. UDP (schneller, aber ohne Kontrolle)
* DHCP, DNS, NAT – was sie machen und wofuer sie gut sind
* Unterschied zwischen Peer-to-Peer und Client-Server Modell

**Was nehme ich mit?**

* Netzwerke bestehen aus vielen Komponenten, die zusammenspielen
* Wenn man weiss, wie das alles funktioniert, versteht man auch besser, warum das Internet manchmal spinnt
