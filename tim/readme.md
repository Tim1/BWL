Provider
========

## Google Wallet [15]
### Das Unternehmen
- Google Inc.
- präsentiert May 26, 2011 -- gestartet (app) September 19, 2011

### Geschäftsmodell
**Funktionsweise**
- Kreditkarten/Debitkarten hinterlegt in Account
- Mobil (nur bei bestimmten Modellen möglich [17]) und im Web bezahlen möglich
- 24/7 fraud monitoring. Instant transaction notifications. 

- Sicherheit: User-Infos verschlüsselt, zusätzlicher PIN notwendig vor dem Bezahlen, muss PayPass-NFC-Reader berühren, über Website handy disable möglich
- Sicherheits-Risiko: möglichkeit des eavesdropping bei Google Analytics


**Gewinne erwirtschafen**
- keine Abgaben sondern durch Werbung
- über Gmail Geld versenden: für wallet-account kostenlos, sonst 2,9% abgabe


### Strategie
- Zusammenlegung/Konzentation auf ein Dienst (Einstellung von Google-Checkout)
- NFC ausbreiten, Android als Plattform (Android Secure element[13])
- Android Market
- Macht der Größe des Unternehmens nutzen 

### Kernkompetenzen
**Differenzierung**
- NFC
- Gmail geld per email
**Diversifikation**
- breit gefächertes Angebot (Gmail, Checkout, NFC)
**Imitationsschutz**
- im Web viel Konkurrenz daher:
- neue Bereiche wie NFC und Gmail-Geld
**Kundennutzen**
- Wallet-Funktion: 
	- mehrere Karten hinterlegen
	- deaktivieren falls gestolen o.Ä.
	- nachprüfen der Bezahlungen im Web
	- großer Anbieter --> viele Angebote (steigend)

### Kennzahlen
- 300,000+ Mastercard-paypass Stores
- ca. 15 NFC-Handys und Tablets (Nexus, Samsung Galaxy S3-S4)[17]




## Amazon Payments [16]
### Das Unternehmen
- Tochterfirma von Amazon.com 100%
- 2007 gegründet
- alle Zahlinformationen der Mutterfirma, gleiche "checkout experience" wie auf Amazon.com


### Geschäftsmodell
**Funktionsweise**
- "checkout by Amazon" (CBA)
	- direkt auf eigener Website einbinden nur Button (website nie verlassen)
	- Bezahlmethoden und Adressen von Amazon.com nutzen, keine Kreditkarte o.Ä. wieder angeben
	- Anmeldung bei amazon über pop-up
- "Amazon Simple Pay"
	- ähnlich wie CBA
	- nur Bezahlprozess, keine Addressen oder sonstiges
	
**Gewinne erwirtschafen**
- Transaktionsabgaben: 2.9% + $0.30
- Rabatt für große monatliche Raten. Bei 100.000$ -> nur noch 1.9%
- besonderes für Micropayment: 5% + $0.05
- besonderes für Non-profit: 2.2% + $0.30


### Strategie
- große Kundenbasis von amazon.com nutzen (Bezahlinformationen + Adresse)
- Vertrauen durch gleiche "User Experience"
- leichtes einbinden in Website

### Kernkompetenzen
**Differenzierung**
- Bezahlinformationen schon vorhanden
- vertrauter Ablauf
- Zusätzlich auch Adresse
**Diversifikation**
- weite Verbreitung auf Webseiten
**Imitationsschutz**
**Kundennutzen**
- Wenig aufwand
- Sicherheit, da keine neuen Bezahldaten eingegen werden müssen

### Kennzahlen
?



Technologien und Zahlprozesse
=============================

## Einzahlung [8][.]
- Kreditkarte, Debitkarte
- Lastschrift
- Pre-Paid (Guthabenbasiert - Konto aufladen)


## Bezahlmöglichkeiten
### Web
#### virtuelles Konto (payment) [3]
- Überweisungen im Vorraus (Pre-Paid)
- evtl. zustäzlich auch Lastschrift möglich
- Überweisungen zwischen Usern möglich

#### Checkout via Provider [9]
- Webshop hat einen Provider z.B. Amazon Payments
- Provider übernimmt den Bezahlvorgang
- Provider hat Konto-/Kreditkartendaten hinterlegt 

#### Kreditkarte
- Website nimmt direkt Kreditkartendaten entgegen
- kein Dritter beteiligt, aber Kunde muss Kartendaten wieder jemandem abgeben.

#### Email
- Neuigkeit von Google wallet
- über Gmail geld versenden [2]


### Mobile [11]
#### Mobile web payments (Desktop like) [6]
- Einfache Adaption von ePayment auf mobile Geräte über mobiles Internet ist natürlich eine andere Möglichkeit, unterscheidet sich aber nicht wirklich vom oberen Punkt, daher nicht nochmals aufgeführt.

#### premium SMS [4]
- SMS Code an kostenpflichtige Nummer --> Bezahlen über Telefonrechnung
- in Asien und Europa verbreitet gewesen, wird nach und nach ersetzt
- Beispiel: 
	- Klingeltöne, 
	- Dial-a-coke von der Coca Cola Company
		- Ein Kunde kauft an einem Getränkeautomaten ein Erfrischungsgetränk und bezahlt es mit seinem mobilen Telefon. Dazu ruft er eine auf dem Automaten stehende Nummer an und wählt anschliessend an seinem mobilen Telefon ein Produkt aus. Das ausgewählte Produkt wird vom Automaten ausgegeben, die Bezahlung erfolgt über die Telefonrechnung. [11]
	- Touch & Travel (Passt hier?)
		- Vodafone in Zusammenarbeit mit der Bahn AG
		- Erwerb des Tickets überflüssig macht
		- Bezahlen per Lastschrift
		
		
#### Direct mobile billing [5]
- Bezahlen über Handyrechnung (Netzanbieter)
- hohe Abgabenraten von 10-20%
- Handynummer am auf Website angeben --> SMS mit Code --> diesen auf Website eingaben


#### über NFC-Chip (google wallet, Touch&Travel, girogo Sparkasse bis 20 €) [1][7]
- Reichweite von ca. 10 cm. (gewünscht)
- deutscher Personalausweis 2011 ist NFC kompatibel
- zustätzlich PIN eingeben als sicherheit
- Andoid Secure Element API [12][13][14]
	- eigener Chip mit CPU/ ROM/ RAM/ I/O
	- sicheres Speichern von Daten (ausserhalb Main-OS)
	- über NFC lesbar oder interne API ansprechbar
- Sicherheitsgefahr z.B. durch kontaktieren aush geringer Enfernung (Vorüberlaufende Personen)
	
#### (QR-Code) [10]
- keine Echte Zahlmethode
- leitet auf Website, andere App um
- Vorteil: einfach, da nur Barcode-Scannen (NFC o.Ä. nicht notwendig)

```
[.] Quelle notwendig
[1] http://www.google.com/wallet/buy-in-store/
[2] http://www.google.com/wallet/send-money/
[3] http://paypal.com
[4] http://en.wikipedia.org/wiki/Mobile_phone_micropayment#SMS.2FUSSD-based_transactional_payments
[5] http://usatoday30.usatoday.com/tech/news/story/2012-04-04/mobile-billing-boku-zong/54003414/1
[6] http://en.wikipedia.org/wiki/Mobile_phone_micropayment#Mobile_web_payments_.28WAP.29
[7] http://en.wikipedia.org/wiki/Mobile_phone_micropayment#Contactless_Near_Field_Communication
[8] http://en.wikipedia.org/wiki/Online_wallet
[9] https://payments.amazon.com/sdui/sdui/business/cba
[10]http://en.wikipedia.org/wiki/Mobile_phone_micropayment#QR_Code_Payments 
[11]http://link.springer.com/chapter/10.1007/978-3-642-29802-8_9/fulltext.html#Sec15
[12]http://link.springer.com/content/pdf/10.1007%2F978-3-642-30436-1_1.pdf
[13]https://code.google.com/p/seek-for-android/
[14]http://nelenkov.blogspot.de/2012/08/accessing-embedded-secure-element-in.html
[15]http://www.google.com/wallet/index.html
[16]https://payments.amazon.com/sdui/sdui/home
[17]http://support.google.com/wallet/bin/answer.py?hl=en&answer=1347934
```
