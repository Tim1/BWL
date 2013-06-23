Technologien und Zahlprozesse
=============================

# Einzahlung [8][.]
- Kreditkarte, Debitkarte
- Lastschrift
- Pre-Paid (Guthabenbasiert - Konto aufladen)


# Bezahlmöglichkeiten
## Web
- Überweisungen auf virtuelles Konto (payment) [3]
- Email (Google wallet) [2]
- Checkout via Provider (für Webshops), beispiel amazon payment [9]

## Mobile [11]

### Mobile web payments (Desktop like) [6]
- Einfache Adaption von ePayment auf mobile Geräte über mobiles Internet ist natürlich eine andere Möglichkeit, unterscheidet sich aber nicht wirklich vom oberen Punkt, daher nicht nochmals aufgeführt.

### premium SMS [4]
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
		
		
### Direct mobile billing [5]



### über NFC-Chip (google wallet, Touch&Travel, girogo Sparkasse bis 20 €) [1][7]
- Reichweite von ca. 10 cm. (gewünscht)
- deutscher Personalausweis 2011 ist NFC kompatibel
- zustätzlich PIN eingeben als sicherheit
- Andoid Secure Element API [12][13][14]
	- eigener Chip mit CPU/ ROM/ RAM/ I/O
	- sicheres Speichern von Daten (ausserhalb Main-OS)
	- über NFC lesbar oder interne API ansprechbar
- Sicherheitsgefahr z.B. durch kontaktieren aush geringer Enfernung (Vorüberlaufende Personen)
	
### (QR-Code) [10]

```
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
```
