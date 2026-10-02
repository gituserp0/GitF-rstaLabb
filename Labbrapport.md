# _Labbrapport_: Virtuell Labbmiljö, Git, CLI och AI

* **Namn:** [Willy Sandstrom]
* **Datum:** 2026-10-02
* **Kurs:** Introduktion till yrkesrollen och grunderna i IT-infrastruktur (MYH 2025/4008)
* **Repository:** `GitF-rstaLabb`

---

## 1. Introduktion & Beskrivning av Labbmiljön

Denna labbrapport dokumenterar uppsättningen och konfigurationen av en virtuell labbmiljö bestående av två virtuella maskiner: en Linux-server och en Windows-klient/server. Jag kommer även att visa hur jag skapat ett git repo och tillhörande filer - detta genom ai-loggen/skärmdumpar/READme.md. 
Syftet med labben är att demonstrera praktiska färdigheter inom nätverskonfiguration, grundläggande kommandoradsarbete (CLI), behörighetshantering i både Linux och Windows, versionshantering med Git samt en kritisk utvärdering av AI som arbetsverktyg.

---

## 2. Labbmiljö & Nätverk (Kursmål 8)

Båda de virtuella maskinerna är placerade på ett gemensamt internt nätverk för att möjliggöra isolerad kommunikation och felsökning.

### Nätverkstabell

| Hostname | Operativsystem | IP-adress | Subnätmask | Standard Gateway |
| :--- | :--- | :--- | :--- | :--- |
| `Linux-Server` | Ubuntu Server / Debian | `192.168.1.50` | `255.255.255.0` (`/24`) | `192.168.1.1` |
| `Win-Klient` | Windows 10/11 / Win Server | `192.168.1.51` | `255.255.255.0` (`/24`) | `192.168.1.1` |

---

## 3. Kommandoradsarbete & Felsökning (Kursmål 9)

### 3.1 Linux (Bash)

1. **Skapa mapp och fil via CLI:**
   ```bash
   sudo mkdir -p /var/systementor/konsultdata
   sudo touch /var/systementor/konsultdata/anteckningar.txt