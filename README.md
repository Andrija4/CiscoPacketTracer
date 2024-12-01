# Cisco Packet Tracer Primeri

Ovaj repozitorijum sadrži kolekciju vežbi, primera i topologija kreiranih u **Cisco Packet Traceru**. Namenjen je studentima i entuzijastima koji žele da vežbaju mrežno inženjerstvo i unaprede svoje znanje o mrežama.

## Opis

Primeri u ovom repozitorijumu obuhvataju:
- Osnovne mrežne topologije
- Konfiguraciju rutera i svičeva
- Implementaciju protokola kao što su VLAN, OSPF, EIGRP, i STP
- Bezbednosne konfiguracije koristeći ACL-ove i NAT
- Vežbe za rešavanje mrežnih problema (troubleshooting)

## Kako koristiti

1. Klonirajte repozitorijum: git clone https://github.com/Andrija4/CiscoPacketTracer.git cd CiscoPacketTracer

2. Otvorite `.pkt` fajlove koristeći Cisco Packet Tracer.

3. Pregledajte i testirajte mrežne konfiguracije ili izmenite topologije prema svojim potrebama.

## Sadržaj

- `OsnovneMreze/`  
Jednostavne mreže za početnike, fokus na osnovne komande i konfiguracije.
- `NapredneMreze/`  
Složenije mrežne topologije sa više uređaja i protokola.
- `BezbednosneKonfiguracije/`  
Primeri konfiguracija ACL-ova, NAT-a i drugih sigurnosnih tehnika.
- `Troubleshooting/`  
Fajlovi sa namernim greškama za vežbanje rešavanja problema.

## Primer konfiguracije

Osnovna konfiguracija rutera:
-Router> enable 
-Router# configure terminal 
-Router(config)# hostname R1 
-R1(config)# interface GigabitEthernet0/0 
-R1(config-if)# ip address 192.168.1.1 255.255.255.0 
-R1(config-if)# no shutdown 
-R1(config-if)# exit 
-R1(config)# ip route 0.0.0.0 0.0.0.0 192.168.1.254 

## Zahtevi

- Cisco Packet Tracer (verzija 7.0 ili novija)
- Osnovno poznavanje mrežnih protokola i konfiguracija

## Autor

Ovaj repozitorijum je kreirao [Andrija4](https://github.com/Andrija4). Ako imate predloge ili želite da doprinesete, slobodno otvorite *issue* ili pošaljite *pull request*.

## Licence

Ovaj projekat nema specifičnu licencu i može se koristiti u edukativne svrhe. Ako imate pitanja, slobodno ih postavite u sekciji *issues*.

