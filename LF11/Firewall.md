Eine Art Prüfstelle, die zwischen das Internet oder ein anderes Netzwerk und den lokalen Computer geschaltet ist. Sie prüft die Zugriffsrechte von Programmen und fremden Rechnern, und zwar in beide Richtungen

==WICHTIG==: Eine Firewall schützt nicht vor ==Viren==, Trojanern, oder ==Phishing Mail==, alles was der Benutzer  mit "Absicht" reinlässt wird ==nicht== abgefangen
### Arten von Firewalls

##### Paket Firewall #Layer 3
Vergleicht jedes empfangene Paket mit einer Reihe von festgelegten Kriterien wie etwa erlaubten IP-Adressen, Pakettyp oder Portnummer. Pakete, die als problematisch erkannt werden, leitet die Firewall in der Regel nicht weiter

##### Stateful Inspection Firewall (SPI) #Layer 3
Berücksichtigt zusätzlich den Zustand der Verbindung (z.B. ob sie bereits geöffnet oder geschlossen wurde). Dadurch kann sie z. B. einschätzen, ob eine Verbindung vertrauenswürdig ist

##### Next-Generation Firewalls #Layer 3-7
Benutzen Intrusion Prevention Systeme (IPS) und überwachen den Datenverkehr auf verdächtige Aktivitäten und blockieren Angriffsversuche in Echtzeit. 

### Router Verkehr 

(Beim grünen Bereich)
Wenn der Router direkt angesprochen wird, dann handelt sich um eine ==Input Hook==
Wenn ein anderes Gerät angesprochen wird, dann ist es nur eine ==Forward Hook==
![[nf-hooks.png]]
