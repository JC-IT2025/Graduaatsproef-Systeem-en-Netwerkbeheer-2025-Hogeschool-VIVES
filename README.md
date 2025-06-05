# Graduaatsproef-Systeem-en-Netwerkbeheer-2025-Hogeschool-VIVES

# S&NB Creative Vision – IT-Infrastructuurproject

Dit project vormt het eindwerk van de opleiding "Graduaat Systeem- en Netwerkbeheer" aan Hogeschool VIVES Brugge, gerealiseerd door "Jarno Cardon".

Het doel van dit eindwerk was het ontwerpen, opbouwen en beveiligen van een "volledig functionerende bedrijfsinfrastructuur" voor een fictief grafisch bureau genaamd "S&NB Creative Vision".

---

## 📌 Inhoud van deze repository

Deze repository bevat:

- 📄 `eindwerkboek.pdf`: Het volledige eindwerkboek in PDF-formaat
- 📸 `bijlagen/`: Screenshots en foto's van opstelling, configuraties en testresultaten
- 🖥️ `vm-configuratie/`: Overzichtsbestanden van VM-settings (ESXi), VLAN-ID's en IP-adressen
- 🔐 `gpo-exports/`: Voorbeelden van groepsbeleidsinstellingen (.txt of .xml)
- 🧩 `network-topology/`: Diagrammen (PNG of PDF) van de netwerktopologie
- 📝 `scripts/`: Eventuele CLI-configuraties, rsync-backupscript, loggingregels, enz.

---

## 🛠️ Gebruikte technologieën en componenten

- Firewall: OPNsense (met OpenVPN en DHCP Relay)
- Virtualisatie: VMware ESXi 8
- Storage: TrueNAS Core met iSCSI
- Monitoring: Zabbix in Azure met VPN-tunnel
- Beveiliging: VLAN-segmentatie, 802.1X (RADIUS/NPS), firewallregels
- Directory Services: Windows Server 2025 met Active Directory en GPO’s
- Wi-Fi: Ubiquiti Unifi U7 Lite (VLAN-integratie + controller VM)
- Voice over IP: 3CX Cloud-telefooncentrale
- Backup: Ubuntu Server met rsync via SSH
- DNS Filtering: Pi-hole

---

## 📎 Doelstellingen

- Een bedrijfsnetwerk ontwerpen op basis van de noden van een creatief bureau
- Kritieke diensten redundant opzetten
- Netwerk logisch segmenteren via VLANs
- Authenticatie implementeren met AD-integratie en 802.1X
- Monitoring, logging en back-upstrategieën toepassen
- Realistische testopstelling uitrollen met fysiek materiaal

---

## 📜 Licentie

Dit project is opgesteld in het kader van een onderwijsopdracht en is uitsluitend bedoeld voor educatieve doeleinden. Hergebruik of verspreiding vereist toestemming van de auteur.

---

## 🙏 Dankwoord

Dank aan alle begeleiders, lectoren en ondersteuners die de realisatie van dit project mogelijk maakten.

