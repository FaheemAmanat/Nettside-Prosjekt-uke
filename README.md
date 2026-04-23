# Virtuell maskiner med active domain services
Skal få videre oppfølging av lærer/ oppdaters underveis
Prosjekt oppgave uke 11
Dette er dokumentasjon for oppgaven, grundig forklarig på hvordan jeg gjorde det og hvordan jeg tenkte.
-	Planlegging
-	Teknisk Dokumentasjon
-	Readme og github depository
-	Infrastruktur
Database, Flask som kommuniserer med databasen og flask visio i en nettside.
Planlegge nettverksstruktur
Installere router, switch og server
 Konfigurere IP-adresser og LAN
 Sette opp server med fil- og brukertjenester
 Installere nødvendig programvare på klientmaskiner 
 Implementere sikkerhet og backup.
Ikke alle skal ha tilgang til hva du gjør og skriver, sikkerhet vil bli implenteres. Nettverks diagram og en spesifikk operativsystem.
Brannmur som sikkerhets systemet, Så langt.
<img width="785" height="499" alt="image" src="https://github.com/user-attachments/assets/73027639-350b-4b54-8f4d-3f84c0e614d1" />

<Firewall aktiverte en blokkade som ikke lot meg tilkoble linux med windows, fant senere ut at nettverket var public og 
ikke private. Det skyldes på sikkerhetsystemer aktivert i et offenltig nett for beskyttelse mot angrep.

Error: dpkg was
interrupted, you must manually run 'sudo dpkg --configure -a to correct the problem.
faheem@faheem:
sudo apt install mariadb
Error:
dpkg was
interrupted, you must manually run 'sudo dpkg --configure -a' to correct the probtem.
faheem@faheem:
sudo apt install openssh-server
Error: dpkg was
interrupted, you must manually run sudo dpkg --configure -a' to correct the probtem.
faheem@faheem :

Fikk opp også den feilmeldingen, fikk ikke updated noe som helst
<img width="960" height="504" alt="image" src="https://github.com/user-attachments/assets/6cf40c61-32c7-4a60-9c89-320d3aafa481" />
Problem: Den meldingen kommer fra Debians/Ubuntus pakkehåndterer (brukt av systemer som APT). Det betyr at en tidligere installasjon eller oppdatering ble avbrutt, og systemet er nå i en uoverensstemmende tilstand.
Og nei, jeg brukte ikke chatgpt for å skrive denne teksten, jeg oversettet den!

Åpne et terminalvindu og kjør kommandoen sudo dpkg --configure -a. Dette vil gjenoppta og fullføre oppsettet av alle delvis installerte pakker. Det er et standard og trygt gjenopprettingssteg.

Setter opp 2 VM-maskiner, en med Windows client og en med windows server. 
<img width="770" height="540" alt="image" src="https://github.com/user-attachments/assets/40a3b736-ca03-43e7-aed1-a8d625dd1f11" />

Slo av internette når jeg ble spurt om å lage konto for å bypasse det, operativ systemet er lastet ned. Nå skal jeg lage windows client VM'en
<img width="770" height="526" alt="image" src="https://github.com/user-attachments/assets/b5113116-1da8-4096-9a75-c34ee2380ec2" />

Active Directory Domain Services er kjernekomponentet til Windows som har rolle for organisering av brukere, data og andre ressurser på nettverket.
